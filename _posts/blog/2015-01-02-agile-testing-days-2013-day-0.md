---
layout: post
title: "Agile Testing Days 2013 - Day 0 (Tutorials) Notes"
modified:
categories: blog
excerpt:
tags: [conferences, agile testing days, battleships, Cern Kaner, context, dice, exploratory testing, heuristics, michael bolton, mind maps, SFDPOT]
image:
  feature:
date: 2015-01-02T15:11:00
modified:
comments: true
share: true
---

Agile Testing Days in 2013 was the first conference I went to since I started my professional career in the software industry.

For those of you that don't know Agile Testing Days is an annual conference held in the beautiful city of Potsdam, which is situated around 15 miles south west of Berlin, Germany. It's considered by many as the best software testing conference in Europe, perhaps on a similar level to EuroSTAR (its location changes every year as far as I know).

So the conference is held Monday to Thursday with the first day being full of tutorial tracks. In this post I will cover the full day tutorial which I attended which was called "Exploratory Testing in Practice" by [Matt Heusser](http://xndev.com/) and [Pete Walen](http://rhythmoftesting.blogspot.co.uk/). Being quite new to the whole testing community, I did not know a lot about these 2 guys, but since then I've learned an awful lot from them and I am really pleased I picked the tutorial I did back then.

The day started off with people arriving in the tutorial room which was a mess. Well, a mess on purpose. The game we played, alongside the dice game which at first did my head in, was to rearrange the room following different rules and instructions, and also working out who else was in the tutorial (from a professional point of view and also personal). It certainly set the tone up for the day as the rest of it was again full of games and activities rather than listening to Matt and Pete speak about testing, which in my opinion is how a tutorial should be run!

One of the best activities we did during the day was play battleships. If you are not familiar with the game, it's purpose is that you play against someone else (or pair with someone else so you play 2v2 like we did) and you have both an attacking and a defensive grid that is 10 by 10. In the defensive grid you set up your ships and other "vehicles" (jet fighters, etc.) and in the attacking grid you plot out the hits or misses you've got from the team you playing against. Each team has a go at a time and the first team to successfully defeat the other team's vehicles wins.

The point of the exercise was that one team had to follow a previously planned script. So for example, you could roll the dice to add some randomness into your script, then follow a path to get picks on the opposing team chart. The opposition in our case was allowed to take an exploratory approach, so they would be basing their attacks on previously learnt information (if they had hit something on position B8, then they would most likely try to hit something else again on B9 and B7, and possibly on A8 and C8 (you weren't allowed to position vehicles diagonally. To our surprise, we actually managed to defeat the opposition team even though we had to follow a script. In fairness, our script crashed after a few goes and we had to make some changes - so exploratory was the default winner I guess.

Since then, I have actually used the battleships exercise during an interview, where the interviewee was someone with a lot of experience in software testing but one of the things we wanted to find out was around exploratory testing practises and what this person thought exploratory testing was all about. I truly recommend this as a possible testing kata or to use during an interview (although bear in mind that not all cultures are familiar with this game and it can take some time, even though it covers a lot of ground, from the "is this candidate asking questions before he jumps in the puzzle and solve it?" point of view to the more concrete exploration vs. script one).

The second part of the tutorial we were given a fair bit of information like:

* [quick attacks](http://searchsoftwarequality.techtarget.com/tip/Ten-quick-attacks-for-web-based-software) that can be used during exploratory testing sessions;
* Michael Bolton's [stopping heuristics](http://www.developsense.com/blog/2009/09/when-do-we-stop-test/);
* mind map tools: xmind, mindmup;
  * mind maps allow for visibility and to create conversations;
* SF D(I)POT mnemonic:
  * Structure: view source, ss/https;
  Functionality: change colours, drag and drop, search, duplicate;
  (I)nterface: csv export, credit card, slow connections;
  Platform: browser;
  Operations: resize browser, back and forth between pages;
  Timings: logout timings, real time updates;
  (User types): user, guest, owner;
* Cern Kaner [website](http://testingeducation.org/wordpress/);

I also recorded 3 quotes from Matt:

* "When sequence makes a difference we have to consider it"
* "You are guaranteed to miss things that are not in the context."
* "In a competitive market place you need software that is beautifully crafted, rather than a set of screws together tap tap tap done! kind of thing"

I thoroughly enjoyed the tutorial day, and hopefully did it justice with this set of notes. But most importantly I got to meet 2 guys (amongst many others during the day) who have become people I admire in the software testing community.
