---
layout: post
title: "Agile Testing Days 2013 - Day 2 Keynotes Notes"
modified:
categories: blog
excerpt:
tags: [conferences, agile testing days]
image:
  feature:
date: 2015-01-05T00:00:00
modified:
comments: true
share: true
---
There were again 3 keynotes during the second day of the conference. Here are some of the notes I took:

**"Live it - or leave it! Returning your investment into Agile" by Christian Hassa**

* fixed time, budget and score: what do we do?
* SAP Business by design disaster
  * target: 10000 customers
  * 1bn / year
  * started in 2003, 2-3bn investment announced in 2007
  * merged in 2013, first release only in 2010, <1000 customers by 2013
* fixed time and budget are not the problem, lack of frequent validation is;
* be prepared that the best laid plans don't work out;
* your job as a tester is not to verify software, your job is to verify the world is actually changing (fast enough);
* scaling TDD to the enterprise - it's not about how to do more work with more people;
<figure>
  <img src="/images/atd_2013_001.jpg" alt="image">
</figure>
* impact maps: goal -> actors -> impacts -> deliverables
  * encourage collaboration with stakeholders
  * break down the goal and turn it into impact map
  * example: business says they want to increase yearly revenue by 3%
    * goal: keep market share in blockbuster concerts; reduce call-center load from blockbuster concerts
    * actors: mobile phone shop users; customers calling to order by phone
    * impacts: reduce bounce rate; order blockbuster tickets
    * deliverables: introduce mobile platform for concert tickets web shop; static information on blockbuster concerts; order one particular blockbuster concert
* influence vs. control
  * influence - goal, actors and impacts
    * define roadmap of goals
    * test goals and impacts as early and as often as possible using:
      * scale - what to measure
      * meter - how to measure
      * range - benchmark, constraint and target
  * control - deliverables
    * smaller deliverable slices into production
    * easier to parallelise
    * across systems and departments
    * prioritised with business sponsors
* impact maps and story maps for different levels of collaboration
* story maps should allow to describe the product to anyone
* specification vs. assumptions:
<figure>
  <img src="/images/atd_2013_002.jpg" alt="image">
</figure>
* [agile fluency model](http://martinfowler.com/articles/agileFluency.html);
* conclusion: scaling agile doesn't mean doing more stuff with more people; it means what to do with higher agile methods;
* don't just focus on delivering larger backlogs with larger teams;
* apply principles to next level: focus on impacts and business goals;
* elevate your practices: build, measure and learn.

**"Accelerating Agile Testing" by Dan North**

In terms of delivering the presentation Dan North was my favourite. Dan is considered to be by many the father of BDD and my admiration for his work grew even higher after listening to his keynote.

* testing isn't a thing that testers do - it's a mindset, a capability, it should be on everybody (but it isn't);
* scrum gets product owners wrong - they should be IN the team;
* "bla bla bla test done!" - blahterfall software process;
* blacklogs shouldn't be groomed;
* exploratory testing is for the cool kids;
* what we do reveals what we value
  * values and believes <-> capabilities <-> behaviour
* which capabilities are missing?
  * https://twitter.com/lisacrispin/status/395537793335578624/photo/1
  * https://twitter.com/tumma72/status/395537853138370560/photo/1
* don't automate tests until they are boring to perform;
* the goal is confidence, not automation;
* what UX is, is dealing with people's emotions: people don't buy apply products because they are actually $400 better than the device before, the UX is that people actually feel about it and queue the night before;
* emotional response: anger, frustration, delight, curiosity;
* load and soak testing;
* where should we test:
  * where the likelihood of failure has a big impact! low likelihood/impact...
  * low risk stuff: need to know enough about it not to care!
  * know about impact/likelihood before worrying about coverage
* what should we test:
  * likelihood and impact are meaningless without context: business rightness, security
  * consider operations as a first class stakeholder
  * security type planning poker
  * ask who cares, if the answer is noone either find someone (stakeholders) or stop doing the work
* when should we test:
  * now we have a strategy we can feed forward
  * how we test determines when we test
* explore other testing methods;
* consider opportunity costs - is the payoff of this worth it? don't automate all the things!
* test deliberately - how where what when;
* waste is any non-adding economic value to the final product;
* testing software increases its economic value;
* become good at something so you know the tradeoffs and the suitanability of a method
  * level of experience needed to understand tradeoffs
  * good choices come from experience, and experience comes from bad choices!

**"Who says we can't be faster?" by Matt Heusser**

* testers: safety net, someone looks after it and after your back...
* system 1 vs. system 2 (Daniel Kahneman "Fast and Slow" book);
* "Black Swan" by Nassim Nicholas Taleb;
* every test ends with "And I'm not going to check anything else" or "And I hope nothing else important happens";
* if the risk is outside the risk model you can't see it - great value to add testing into the model;
* ten kinds of tests:
  * quality factors, creative ideas, states, taxonomies, previous failures
* coverage decays over time;
* create and put test ideas on the board to make it visible! (test kanban!);
* test smarter - perception any change needs full retest so automate more;
* pair or team exploratory testing offers different people that highlight ideas, bugs, surprises and questions;
* coach, continue to help other people and keep looking for problems - it's where software is going and its great to be that safety net.
* economical benefits of retesting something that things have changed.
