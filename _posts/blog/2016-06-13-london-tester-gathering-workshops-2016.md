---
layout: post
title: "London Tester Gathering Workshops 2016"
modified:
categories: blog
excerpt:
tags: [workshops, london tester gathering, exploratory testing, quality assistance, coaching, mentoring]
image:
  feature:
date: 2016-06-13T00:00:00
modified:
comments: true
share: true
---
Last week I attended the London Tester Gathering Workshops.

I was lucky enough to be given a ticket by Jean-Paul Varwijk ([@arborosa](https://twitter.com/arborosa)) who was giving a workshop on "Agile Exploratory Testing".

I couldn't attend the first day of the workshops but I went down to London on the Friday to take part in Jean-Paul's workshop and in the afternoon attend the "Get into Coaching and Mentoring" which would be a nice fit into my new job role at Redgate - Quality Coach.

You can find my notes below, I thought overall it was a great day - I remember attending it a few years ago and was good to see a few old friends. It was also great to meet up with some of the guys from Atlassian, including Andrew who I have been exchanging emails with for a while, trying to understand their QA Model better and how we can incorporate some of its aspects at Redgate. I am really grateful to Andrew for his time chatting and all the information he has provided me over the last few weeks.

**Agile Exploratory Testing - Jean-Paul Varwijk**

* He started off asking people to write 10 things they noticed about the room (didn’t matter what they were, just write them down as soon as it comes up in your brain).
* He proceeded to define what exploration is: the act of searching, for the purpose of discovery of information or resources.
  * Searching - activity
  * Purpose of discovery - goal/direction
  * Information - Something worth knowing
  * Resources - something that helps to advance
* “In exploration you aim to create a sense-making model instead of a categorisation model”.
  * Resource: Myers Briggs Type Indicator: Categorisation Model, Jon Bach (Agile 2010) “Telling your exploratory story”
* We then proceeded to explore two different applications:
  * https://getdoneapp.com/
  * http://www.arborosa.com/games/Horse_Lunge_Game_With_Dressage_by_eponagirl.swf
* Oracles: Heuristic principle or mechanism by which you recognise a potential problem. They help you evaluate test results.
  * Tacit - Testers: experience, your feelings and mental models
  * Explicit - Testers: inference, observable, consistencies
  * Tacit - Other people: conference, stakeholders, feelings and mental models
  * Explicit - Other people: Reference, shared artefacts (specs, tools, etc.)
* We then played the ColorGame (http://arborosa.com/colorGame/colorGame.html) :
  * Asked to use oracles
* We also touched on the various definitions of exploratory testing:
  * The wikipedia definition (which is very similar to James Bach’s)
  * James Bach
  * Michael Bolton
  * Jean-Paul’s own one
* Heuristics: Oracles are heuristics, but not all heuristics are oracles.
  * SFDIPOT
* Session-Based Test Management was also covered very quickly as we were running out of time.
* Planning:
  * Strategy: test plan, coverage risks
  * General: heuristics, test ideas, risk catalog
  * Ongoing planning: weekly planning session, charters
  * Issues, bugs and session sheets
  * Daily Test sessions: low tech dashboard
* Test story: art of storytelling is pretty important in exploratory testing.
* Agile testing → Concurrent testing: analysis, design and dev throughout a sprint. Breaking down in small items, improving awareness and responsibility of all team members for the software quality.

**QA at Atlassian - Andrew Prentice**

* Does your business really want testers? (or do they want something else and call them testing?)
* If quality was there, there would be no need for testers
* Testers can’t be gatekeepers
* Quality assistance (model) introduction: co-pilot role: goal is to go really fast. Great analogy if you think about the role of a co-pilot
* Difference between a “10x developer” and a “1x developer” is a quality assistance engineer
* When developers fail, QA fails too
* Centralised QA Function:
  * Different team for sharing knowledge, people and resources across products
  * Efficient recruitment, onboarding process, development and management
* 4 factors:
  * Eradication: cross site request forgery protection across Atlassian
  * Prevention: QA kickoffs, testing notes and demos
  * Detection: automated tests, Developers in Test, blitz testing
  * Mitigation: progressive deployments, feature flags, controlled releases (limited by number of people that get it)
* 3 different QA Phases:
  1. QA only did critical testing (changes), pair with devs for the rest and provide resources
  2. devs only doing critical testing, QA focus on kickoffs, root cause and defect analysis
  3. no manual testing, QA focus on eradication

**Get into Coaching and Mentoring - Tony Bruce and Dan Ashby**

I didn’t take any notes during this session as it was very hands on.

* We started with an ice-breaker (game of "Swoosh") and then moved to definitions of coaching, mentoring, leadership and teaching.
* There were a couple of games played:
* Communications game (that felt mostly about leadership) where everyone in the room got a piece of paper with a picture - the point was that we had to put ourselves (around 22 people) in order from start to finish to tell a story with our pictures: figure out the pattern, figure out the relationship between the pictures and then manage to self-organise so the story made sense.
* Writing about a shape/picture: there were a lot of circles in my example and I had to describe in 5 minutes how to achieve the same shapes/picture without talking to my colleague (we actually got taken out of the room so my colleague only had access to my poorly handwritten piece of A4 paper)


As usual, these are very rough notes, so some information may not be entirely accurate, or representative of what was said/shown during the day. Feel free to tweet me any questions [@joseglima](https://twitter.com/joseglima).
