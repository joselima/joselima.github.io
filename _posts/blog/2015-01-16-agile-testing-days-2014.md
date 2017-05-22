---
layout: post
title: "Agile Testing Days 2014"
modified:
categories: blog
excerpt:
tags: [conferences, agile testing, agile testing days, automated testing, games, set game]
image:
  feature:
date: 2015-01-16T00:00:00
modified:
comments: true
share: true
---
Last November I attended Agile Testing Days 2014. If you read my previous posts you would recognise this was the second time I attended the conference.

It was great being back in Potsdam, Germany, and see many familiar faces, including some from across the pond whilst also meeting new ones from all over the place.

This time I had decided I would pace myself in terms of the number of talks I attended, the tweets I posted and the notes I took, just so I could enjoy more of the conversations and attempt to take less information in but at the same time hoping I would be able to retain it for longer and use it more consistently afterwards.

Below are the notes I took during the 4 days, which started off with a tutorial day on a Monday.

### Tutorial day

**"Technical testing in an agile environment" by Alan "The evil tester" Richardson**

* Technical testing:
  * reminder to keep going deeper
  * tool augmentation
  * technical details will:
    * inspire more testing
    * identify more risks
    * identify different problems
  * not limit our testing to acceptance criteria
* MORIM:
  * Model: understand different viewpoints
  * Observer: corroborate, invalidate model
  * Reflect: find gaps, lack of depth, derive intent
  * Interrogate: focussed, deep dive observation with intent
  * Manipulate: hypothesis exploration and "how we do stuff"
* tool augmentation:
  * is not automation, it uses automation
  * passively observe, maintain history of observations
  * alert specific conditions
  * observe the unobserved, and interrogate the inaccessible
  * help model, reflect and manipulate
  * never tools to control, tools to augment
* go beyond the surface structure
  * transformational grammar
  * surface and deep structure
  * chomsky
  * multiple surface structures
  * single deep structure
    * filtered, biased, distorted -> surface structure
  * questions operate as tools to investigate surface to deep mapping people
* how to do technical testing:
  * identify tools
  * questioning systems at different surface levels
  * learning system structure technology
  * model system surface structures
  * observe system surface structures
* automation? sure if you have time;
* "EditThisCookie" plugin;
* fiddler and use of its breakpoints feature;
* burpsuite;
* WebHackers handbook;
* "The tangled web: a guide to securing modern web applications";
* retrospectives:
  * don't just pat on the back
  * raise process issues that impact
  * agree what to do about them
  * treat broken windows
  * you might have to be mr. nag and mrs. nasty
* standups:
  * pay attention to changes
  * describe in value terms
  * see help, pairing
* acceptance tests:
  * abstraction layers
  * re-use abstraction layers for adhoc automation as well as acceptance tests
  * seek to understand technicalities as well as domain
  * pair

I really enjoyed this tutorial day - it was probably my first tutorial where the majority of our time we spent doing what we do on a day to day basis which is testing software. Yes we got stopped and had some time limits, but those breaks were used very effectively not just by Alan but also by everyone in the room where we shared our experiences and different tools we use in our technical testing role. The only improvement I would suggest to this tutorial would be more pairing and different pairs for the testing exercises as it could spur up more conversations and it would set the tone up for more people to carry on doing it during the break and also during the rest of the conference. But I must say a big thank you to Alan for this tutorial as it was certainly the most useful tutorial I've been to so far in my career :)

### Day 1

**"Welcome to the future! Preparing for our agile testing journeys" by Lisa Crispin and Janet Gregory**

* Preparing for the future, or the agile future...;
* what are the challenges, what can testers do? How can we change conversations?;
* ability to broaden t-shape skills (breadth and depth);
* ability to learn, become a t-shaped tester, cognitive learning skills, take charge of your career;
* customers assume that we know what they want and they want us to deliver exactly what they are thinking;
* sometimes it's better to train people than automate certain processes, ask good questions, walk people through;
* borrow from other disciplines, like business analysis (the 7 product dimensions);
* change it:
  * from counting bugs
  * from counting metrics that do not matter
* we have to start thinking about all kinds of risks - call for more risk assessment?;
* models can help us chose how to attack a problem;
* serious play is a great way to learn about new things (play, observe, innovate);
* inspect and adapt: try again, scrap it and try again - what's next for you?

**"A poet's guide to acceptance testing" by George Dinwiddie**

* We want tests to last over time;
* not just automated tests, the way you express yourself counts;
* you need to start thinking about the theme, then start analysis each part;
* without context words can be confusing;
* "Given Mary had a little lamb, When Mary went to school, Then the lamb went to school";
* purpose is to be picky so words can stand the test of time;
* some words like everywhere can be quite hard to test against - use examples that cover a good range of options;
* when a scenario has too much setup that's a clue - you may not need all that;
* why do we write tests that ask question of what we should do? We should ask what the system should do;
* purpose of this talks is that words matter - pay attention to them.

**"From good to great: Combining session and thread-based test management into xBTM" by Michael Albrecht**

* SBTM/TBTM/xBTM: models, mindmaps and automatic reporting;
* xBTM in a nutshell is both session and thread based test management;
* James Bach's exploratory testing spectrum;
* session: test charter - what and what problems;
  * produce a session report (time, bugs, setup, defects, issues and notes);
* PROOF - past, results, obstacles, outlook and feelings;
  * past and results are very similar in the report
* ratio for session based test management is 15 minutes test design, 90 minutes test execution or 10/60 minute ratio;
  * fixed length
  * planned (charters, key areas)
  * reviewable (reports)
* TBTM - threads are a test activity or test idea;
* use mindmaps to generate threads;
* to do list, no timeboxing, working in parallel, mind maps;
* xBTM - models for test design (you show a map to point a country for example);
* "yed" tool;
* using a mindmap, navigate through the flow of the system to guide your session/test design.

**"Strategy testing // building a product users want" by Roman Pichler**

* What a boss wants vs. what programmers want - programmers just want to give it a go, build a prototype and see if it files;
* vision - your goal;
* strategy - path to the goal;
* details - steps;
* who are the users and who are the customers?
* "find an itch that's worth scratching";
* test your strategy - areas of uncertainty, risk assessment;
* go and talk to your users about the experiences and how they use (your) product today;
* create a failure tolerant environment.

**"The antimatter principle" by Bob Marshall**

* Golden rule - treat as you want to be treated;
* platinum rule - treat people as they want to be treated;
* the antimatter principle - antimatter is the most expensive/rare substance known to man;
* attend to people's needs;
* why do we do software development? Why do we do testing?
  * to attend to people's needs
* autonomy, mastery and purpose - Dan Pink;
* Non-violent Communication by Mark Rosenberg;
* our default mode when we are "not thinking about anything" is to think about ourselves in relation to others - neuroscience research;
* theory x or theory y organisation.

**"Testing the untestable" by Peter Thomas**

* You don't know what you don't know;
* Dan North's "deliberate discovery;
* blue green deployments (continuous delivery);
* the third way;
* sometimes "The best testers... are your users";
* monitoring over testing...;
* look for abnormal patterns in your data, usage, etc.

**"The pillars of testing" by David Evans**

* Model: a (sub) set of things to create or improve within a development or testing process;
* "all models are wrong, some of them are useful";
* Confidence, above safety and courage;
* stronger evidence, better test design, greater coverage, faster feedback;
* collaboration and communication, business engagement, team structures, test techniques, skills and experience, effective automation, application testability, configuration management;
* there's also the bottom layer which represents the strong base;
* then there's the foundation layer;
* this model can be used to discover or apply root cause analysis;
* it can also be used to assess, survey teams and organisations, rate the perceived success and importance of each element and look for hotspots and for variances;
* confidence is the balance of safety and courage.

**"Don't put me in a box" by Anthony Marcano**

* Most people tell you what they are instead of what they do;
* categorisation still defines what we do for example mum and dad duties;
* quality comes from people and not from processes;
* sharing the responsibility within the team doesn't stop people having expertise or being the expert/reference point, but we may not need him/her all the time, we can all do it.

**"Pull requests and testing can be friends" by Alan Parkinson**

* Use files changed in pull requests to guide your charters and your exploratory testing;
* ask questions in the pull requests comments feature to learn about risks;
* learn from history;
* see who contributed what.

**"Lateral and critical thinking for testers" by Dan Ashby**

* Left and right side of the brain;
* left - critical thinking;
* when we got the information upfront it's a lot easier to ask questions
  * it's hard to use critical thinking alone!
* lateral thinking is when thinking leads the information;
* "Lateral thinking" by Ed de Bono;
* Lateral = side thinking.

**"Communication: What are you thinking about?" by Shachar Shiff**

* Bad communication causes failure;
* "Visual aids improve communication";

**"Helping testers add value to Agile projects" by Alan "The evil tester" Richardson**

* Testers adapt different filters to different systems;
* waterfall projects:
  * removed waste
  * responding to need, not want
  * exploring more
  * taking responsibility for my testing rather than conforming to the process
* view it as systems rather than agile;
* testing needs to remain viable and needs to add value;
* steal from other disciplines (systems thinking, cybernetics, etc.);
* ownership for testing;
* exploration beyond acceptance criteria;
* we need strategies that cope with things coming fast and things getting delayed.

In summary, Agile Testing Days was yet again a great conference and a great week spending some quality learning time with people that I previously admired and new people I met and learn to admire. Tuesday night I saw Matt Heusser getting his Most Influential Agile Testing Person award for 2014, which I was happy for as I voted for him, and also the Brazilian National Team was awarded 1st place in the Software Testing World Cup. Most of the other nights were spent in the bar chatting with people from all over the place, whilst also helping out at the Games Night on Wednesday where I was (as you would expect) one of the people co-ordinating the SET game table. Also had the chance to act as the coach in the infamous Pen game to two of my Redgate colleagues. What can also seem as an off topic to some people, and hopefully on topic for some others, we also went to one of the "Lock rooms" in Berlin where you have to solve a variety of puzzles in order to get out of a locked room - that also opened my eyes to the variety of skills testers have and it was great to further meet some people and chat some more in a slightly more relaxed environment (except for the fact we were locked in a room!).

Hopefully see you at Agile Testing Days 2015!
