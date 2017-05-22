---
layout: post
title: "Agile Testing Days 2013 - Day 1 Talk Notes"
modified:
categories: blog
excerpt:
tags: [conferences, agile testing days, testing]
image:
  feature:
date: 2015-01-08T00:00:00
modified:
comments: true
share: true
---
In the first (well technically second if you count the tutorial day) day of the conference I attended the 2 morning talks and in the afternoon I floated between consensus talks and the various workshops and vendor boots. Here are the key points talked about in those talks.

**"How to avoid the testing swiss cheese syndrome" by Marc Rambert**

* We're not born testers - we become testers;
* 2% change in a full release (development effort), how much testing effort is required?:
  * 10 test cases related to new features and bugs fixed in this release
  * 90 regression test cases
  * solution: there is no relation - it's too difficult to align testing and coding
* speed and continuous delivery make it impossible to test everything after each change;
  * change request implemented and tested (build 0)
  * functional regression set #1 (build 1)
  * bug because of last minute effect (build 2)
  * go live!
* strategies to focus testing where it adds value (requirements, risks, experience, collaboration)
* a new opportunity to improve testing in a black box:
  * learning system: learn your tests as usual but capture footprints (link code and test)
  * detection: application changes
  * smart engine
  * you can also add tests that have been run before
* test scoring to prioritise test execution
* avoid the testing swiss cheese syndrome: find a way to make your application speak

**"Be a real team member" by Tony Bruce**

* What makes a good team member:
  * engage, and use that to build a relationship, interest and motivate people (4 keyword framework)
  * motivate: provide someone with a reason for doing something
* Models (engage)
  * Belbin team model - action oriented roles, people oriented roles, thought oriented roles
  * plant is someone that comes up with the idea
  * resource investigator, co-ordinator, shaper, monitor evaluator, team worker, implementer, completer finisher, specialist (they key is balance)
* as you learn more your role will change too
* Margerison-McCann model
* day to day:
  * positive action over positive thinking - do it rather than mention it / think about it
  * ask the questions!
  * feedback: express what you do want, rather than what you don't want!
  * reciprocation: essentially states that if someone gives something to us, we feel obligated to repay that debt; give help; ask for help (give and take)
  * always acknowledge, never dismiss or ignore
  * don't assume that only people with higher jobs than you have valid opinions
  * beware of the curse of knowledge
    - cognitive bias
    - can be off-putting
    - can leave people feeling dejected
    - why the should care?
  * act as a sounding board
  * appreciate any input
  * beliefs followed by behaviours
  * find people who work because they believe people over money
  * always able to offer different perspectives
  * invest time with people whose work crosses organisational boundaries
  * breaking bread - sharing your lunch - best ideas are shared over food
  * remain reliable
  * listen - don't just sit around with your headphones on - listen and eavesdrop
  * do the i's and cross the t's
  * problems don't lie in the philosophy of procedures but in practice, and practice is governed by attitude
  * before you speak think - is it true, helpful, inspiring, necessary, kind?

**Consensus Talks**

**"Group Testing" by Christian Baumann**

* Regression testing, how to overcome its error proneness and boredom?
  * no testers in the team
  * group testing! everyone involved, tests distributed randomly, everything until finish and debrief
* benefits: concurrency and performance issues detected, no one is testing alone, safety net before release;
* how often do you do it and when? it got forgotten;
* lists get too long, big tests vs. small tests;
* regression testing was done in areas where automated tests are lacking;
* executed regularly (frequency depends on findings);
* not too boring or repetitive;
* unsolved issues:
  * decreasing motivation
  * retrospective not done regularly any more
  * number of tests growing
* officially it was meant to happy every 2 weeks but it just didn't;

**"Are we still testing the wrong stuff?" by Stephan Kamper**

* There's more to test than what's desired today
* two values of software:
  * ability to tolerate and facilitate such ongoing change is the primary value of software, it has to be soft
  * build the software without too many bugs (we're ok at this [-ish])
* however, the 1 value people keep saying you ain't gonna need it (yagni);
* everyone (test, ux, ba, managers, etc.) should care about eh primary value too;
* but, few teams do this kind of testing, future readiness not that important after all? relation to software life time?
* we need zebricon: there's no answer but may be a concrete answer isn't the point;
* how about testing future readiness?

**"So I am an Agile test manager now... but what does that mean?" by Mitch (surname unknown)**

* Manager could manage test cases... but you would be a tester in that case;
* could also manage tests... but you would be a test co-ordinator;
* could also manage testers... but you would be a people manager;
* strategies and guidelines: manage environment, boundaries around team, strategy and guidelines for self organised teams, impact mapping;
* 3 amigos idea in a test manager.
