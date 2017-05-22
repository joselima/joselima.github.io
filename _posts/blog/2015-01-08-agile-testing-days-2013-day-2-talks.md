---
layout: post
title: "Agile Testing Days 2013 - Day 2 Talk Notes"
modified:
categories: blog
excerpt:
tags: [conferences, agile testing days, agile testing, exploratory testing, SBTM, James Bach]
image:
  feature:
date: 2015-01-08T01:00:00
modified:
comments: true
share: true
---
The second day of the conference, and when I was already feeling quite exhausted, I attended a couple of talks in the morning and just sat down in the main room during the afternoon to see what the consensus were about. Here are my notes for the day.

**"BDD - Live coding sessions" by Carlos Ble**

Carlos' idea for this session was that he would be coding scenarios in real time a web app so that the audience could participate in giving him feedback and come up with requirements. He would then use this to write up his scenarios before translating them to Cucumber. Unfortunately there were too many problems at the start of the session to due with the network and his server so we only had limited time. Carlos still managed to explain what he intended to do and as easy as it would be to say that he could have prepared it better, those things can happen (live demo gods) and it was brave to do something like that in front of a packed room. I caught up with Carlos in the evening as we were both having dinner in the same restaurant and we had a little chat about BDD and his experiences with it, and I got plenty of resources to go and look at, so it was definitely worth attending. Also, my brain got a bit of a break :)

**"Myths of exploratory testing" by Luis Fraile and Jose Aracil**

This was one of the most discussed talks (at least on Twitter) of the conference, partly because of some of the very controversial claims the presenters made during the talk, but also because they seemed to have a slight different idea of what exploratory testing was for them than to most people in the audience. Despite this, here are their key points.

* when you explore it you want to come back;
* keys to success: inspects and adapt, be creative! take advantage of your team and skill set, additional to other testing, quickly find defects, add value to your customer and test early/test often;
* myth 1: same as ad-hoc testing
  * must be planned and documented
  * you must know: what has been tested; when it was tested; what defects were logged
  * some ideas: testing tours by James Whitaker (!); session based from James Bach; your own method
* myth 2: can't be measured
  * multiple measurement techniques: SBTM; amount of logged defects; defects vs. user story complexity
  * you must be creative
  * warning.. warning! don't be fooled by metrics
* myth 3: endless
  * difficult to focus on long tasks (> 25 mins)
  * endless = useless
  * must focus on specifics; requirements, problems and complex parts
  * stay focused for burst periods (25 mins)
  * pomodoro testing
* myth 4: can't reproduce defects
  * how do you reproduce a defect: be an explorer, like David Livingstone
  * toolset: record video/audio; screen capture; analog recording
* myth 5: only for agile teams
  * inspect and adapt
  * insanity is doing the same thing over and over again and expecting different results
  * look for new ways of testing
  * empower your team by allowing creativity
  * do you trust your team?
* myth 6: not documented
  * tester "lonely planet": user manual; online help (F1 tour); help from third parties
  * alternative tester: goes outside the tour (cancelling processes halfway, using undo, doing things twice); use uncommonly used functionality or processes; always with an objective in mind
  * second visit: you need pictures/notes

**Consensus Talk**

**"Organization, Roles and Responsibilities of Testers and Test Managers on Agile Projects" by Dr. Jennifer Blechar**

* 2 projects which were virtually the same, yet they evolved differently - here are the learning points:
  * there's no I in team:
    * testers must be part of the team
    * test managers outside of teams useful to co-ordinate across teams
    * consider dedicated technical testers
    * consider dedicated test automation experts
    * communication essential
  * use the right tool for the job:
    * everyone in the team must use the same tools
    * user stories in the tool - linked to tests created by testers, users, devs, etc.
    * careful evaluation of tools for test automated prior to implementation
  * never underestimated the value of socialising
    * people are much more likely to "go along" with your ideas if they know you
    * make time to get to know key stakeholders in the project - this includes the customer as well as developers
    * create opportunities for socialising
  * get everyone on board - and keep them on board!
    * the test plan is useless if only the testers agree with it - everyone needs to buy-in to the test plan and be commited to their role in the process
    * relationships needs to be constantly maintained
    * don't be afraid to change course if needed - use lessons learned
  * reporting
    * customers and other key stakeholders need to be aware of the progress at all times - consider  "light" but often reporting
    * reporting is also motivational and useful to get and keep everyone on-board
* five factors identified as influencing the success of agile testing effort
* additional factors likely, most important factor is to be agile!
