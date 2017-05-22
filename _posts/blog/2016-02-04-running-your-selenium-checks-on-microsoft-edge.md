---
layout: post
title: "Running your Selenium checks on Microsoft Edge"
modified:
categories: blog
excerpt:
tags: [selenium, automated testing, automated checks, web driver, edge]
image:
  feature:
date: 2016-02-04T00:00:00
modified:
comments: true
share: true
---
For the last week or so, after spending some time upgrading some of our existing selenium client machines I thought it would be a good idea to find out more about Selenium checks (tests...) on Microsoft's new browser, Edge.

It's the first time that Microsoft have released a web driver themselves, officially supporting it.

Below are some of the issues I've found whilst using it, and since I had to spend some time digging around GitHub/Google I thought I'd collate them here.

The first problem I found was trying out the example given by Microsoft themselves on their blog (https://blogs.windows.com/msedgedev/2015/07/23/bringing-automated-testing-to-microsoft-edge-through-webdriver/)

The first thing you do is install the web driver (link is in the url above).

Then all of a sudden, without modifying the code posted by Microsoft, the tests would just hang. Upon inspecting the output I could see that:

"Existing Microsoft Edge (pid: xxx) terminated forcibly"

In this case, the problem was with Edge itself. By default, Edge has a startup page rather than a url, and it appears that the web driver struggled to understand that, quitting straight away. Simply go to Edge's options and change this to a url you want (Google or Bing should do just fine).

The next problem I faced when I tried to run those checks was that Edge couldn't be launched if the user was builtin\Administrator. This is a security issue implemented in Windows 10 and to work around it have a look here: https://4sysops.com/archives/why-the-built-in-administrator-account-cant-open-edge-and-a-lesson-in-uac/
(hint: the solution is actually only described half way down the page).

To add Edge as a browser that can be run on a selenium grid, edit the node's configuration file by adding the following (and changing as you wish):
```xml
{
"browserName": "MicrosoftEdge",
"maxInstances": 4,
"platform" : "WINDOWS"
}
```
Next issue was that Selenium couldn't detect the Edge web driver. One workaround is to move the place where the installer places the web driver to where you running your Selenium node from (i.e. the same folder). After that, add this to your node startup file (where you also tell it where Selenium lives for example):
```xml
-Dwebdriver.edge.driver=.\MicrosoftWebDriver.exe
```
This should allow you to run your checks using remote capabilities, and here's how I've done it:
```csharp
var capabilities = new DesiredCapabilities("internet explorer", "11", new Platform(PlatformType.Windows))
var edgeProfile = new EdgeOptions();
edgeProfile.PageLoadStrategy = EdgePageLoadStrategy.Eager;
capabilities.SetCapability("edge_profile", edgeProfile);
```
The one thing to bear in mind is that Microsoft's Web Driver doesn't yet support all commands that you're potentially used to, like xpath (you probably shouldn't use xpath anyway, but sometimes there is no easy alternative). You can try a newer version ("for windows insiders") of the webdriver that has a preview of the getelement by xpath but it's obviously not in the official release yet, so use it with caution. Check this url to find out what you can and can't do: https://dev.windows.com/en-us/microsoft-edge/platform/status/webdriver/details/ For all the above I have been using Selenium 2.48.2 but I believe bindings were introduced in 2.47.0 to support the new Microsoft Web Driver. I tried to use the latest (2.50.1) but found it too unstable so reverted back to 2.48.2. Hope you find some of this information helpful.
