---
layout: post
title: "Agile Testing Days 2015"
modified:
categories: blog
excerpt:
tags: [conferences, agile testing, agile testing days, black stories, context, exploratory testing, heuristics, pen game, testing, games, set game]
image:
  feature:
date: 2015-11-29T00:00:00
modified:
comments: true
share: true
---
November in my work calendar means only one thing: Agile Testing Days 2015.

This was the 3rd time I participated in ATD, although this time as a speaker which was a really interesting experience.

As usual what is always great at ATD are the conversations and I was lucky enough to speak to Anne-Marie Charrett and find out how she has been coaching testers at her organisation and the challenges she has faced hiring new testers. The MIATP award party on Tuesday night was also brilliant and it was good to meet some new people from around the world.

One of the highlights of the conference was playing the pen game with my colleague Andrew Fraser (who has also published his conference notes on his blog, which are a far better representation than mine! check them out [here](https://medium.com/@tuxt3r)) and playing some testing games on the Wednesday night!

I will write a separate blog post about the talk I presented but here are my (short) notes taken during some of the keynotes and talks I attended.

This year I also missed the tutorials day due to schedule restrictions so I'll go straight to day 1. I hope you find these notes useful, but if you have any questions or want some clarification feel free to leave a comment!

### Day 1

**"Where words fail music speaks" Keynote by Huib Schoots and Alexandra Schladebeck**

* what's common between music and testing
  * instant feedback
  * reduce complexity to practice
  * learn fundamentals (own them)
  * muscle memory
  * you don't practice from front to back
* teams have the same soundtracks, they are on the waves (i.e. understanding)
* hero complex, music teams and their contexts
  * solo
  * trios/quartets
  * bands
  * orchestras
  * sessions
* STAR heuristic
  * structure
  * tune
  * accompaniment
  * rhythm
* know what your cadences are... (authentic and deceptive, like musical notes)
* exploratory testing and music:
  * scripting versus improvisation
  * communication over documentation
  * standards and music
* experiments: outcome is unsure
* non-deterministic and non-reproducible
* models: based on experience, culture, etc.
* lessons:
  * learn your team's tune
  * finish your sprints on a good cadence
  * recognise your role and context
  * practice, patterns, adapting = you'll be a star

**"Experimenting in context for Exploratory Testing" Talk by Maaret Phyajarvi**

* replacing a test case driven style with a learning tester driven style in two organisations
* what testing gives us:
  * unit testing: spec, feedback, regression, granularity, testing as artefact creation
  * exploratory testing: guidance, understanding, models, serendipity, testing as performance
* data intensive application
  * things that couldn't be changed at certain organisations (the "givens")
    * waterfall process
    * contractual distance between acceptance testers and subcontractor
    * test case metric based reporting
    * manage, don't test
    * business end users as testers
  * things that have changed (the "experiments")
    * acceptance tester degree of freedom
    * test cases from step by step scripts to test data with process outline for notes
    * making change requests acceptable
    * reporting ~20% of testing to 3rd party
    * unofficial tips sharing sessions with the subcontractor
* Function intensive application:
  * "Givens"
    * roadmapping creating disconnect to current priorities
    * tendency for remote work
    * developers doing majority of testing
    * requirements / specifications format as UI spec
  * "Experiments"
    * no test cases or wasteful documentation
    * tester with developer tools
    * removing "acceptance testing" by moving testing to the team
    * continuous delivery (without test automation)
    * holding space for testing to happen
    * true teamwork with mob programming
* PROOF
  * past
  * results
  * obstacles
  * outlook
  * feelings
* vision, current charter, other charters, details (bug reports)
* charters to give ideas of exploration

**"A happy marriage between context-driven and agile" Talk by Ilari Henrik**

* Automate everything?
* checking vs. testing
* checking the algorithmicly catchable stuff
* TDD is not testing
* automated check:
  * passed - ok or missing a bug
  * failed - there is a problem or false alarm
* "Embedded testers"
* Context-driven and agile manifesto
* context driven testers will "click" really well in agile teams
* ilari.com/agile PTE Agile Testing Manifesto
* how we do it:
  * get involved early
  * bridge between developers and testers
  * pair on tasks
  * educate the team about testing
  * technical awareness "I comment my code - but I still don't know what I did or why"
  * domain knowledge
  * willingness to learn
  * when crafstpeople meet other craftspeople, that's when the magic happens

**"Testers are dying" Keynote by Karen Greaves and Sam Laing**

* There's more demand than there's capacity - testers aren't dying
* 6 steps:
  * awareness
  * punishment (different tariffs, rates going up)
  * personal responsibility
  * remove barrier
  * visible impact
  * start a movement
* trends:
  * pressure at the end of the sprint
  * often asked to release without testing
  * testing is always behind development
  * blame around bugs
  * automation is at least a sprint behind
* personal responsibility by different boards - different columns like "show me", "review (in pairs)", different colour coding

**"The human refactor experiment" Keynote by Bryan Beecham**

* horizon of predictability: we can only see so far into the future
* moment of maximum ignorance
* get past mental limits - other people will start buying in
* 23 1/2 hour challenge
* refactoring:
  * exercise
  * diet
  * continuous improvement
* make the world a kanban board

### Day 2

**"If I can do it so can you" Keynote by Dr. Sue Black**

Dr. Black told the audience the story of her life right from growing up in the suburbs of London to forming a campaign that helped save Bletchley Park, the home of the World War II code breakers. Really inspirational.

**"Shift left and shift right - the testing swing" Talk by Laurent Py**

* journey from waterfall to agile
* breaking silos
  * speed of feedback loop
* put value before correctness
  * why? is it worth doing?
  * how to ensure quality of deliverables?
* testing matrix
  * build / production
  * what should we buid and why? is it really worth it?
  * how to automate? is it really reliable and does it scale?
* good for challenging business assumptions

**"There is no secret sauce" Keynote by Ben Williams and Tom Roden**

* investing in impact model
* are we investing in the right things?
* what aren't we going to do now?
* investing in impact - a leaner approach to investing in software
  1. decide to invest - explicitly acknowledge hypothesis (between writing software and making money), consider this investment in the context of others
    * diversification: people's skills, technical component
  2. establish performance boundaries
    * ranged planning
    * pro actively manage risk
  2. measure income
  3. measure impacts
  4. decentralised decision making
    * steer by exception
  6. learn

**"Test beyond quality, beyond software" Keynote by Mike Sutton**

* Steve Blank's book "Startup Owners Manual Step: The Step-By-Step Guide for Building a Great Company
* agile teams are a place to cultivate behaviours and cultures for a new reality
* it's time for agile teams and testing discipline to go beyond software, beyond testing and into organisations
* ask questions, go where they lead
  * "Why does it take so long?"
  * "What if?"

### Day 3

Unfortunately, after giving my talk I didn't take any notes from the two keynotes I attended. The first one was by Tom Bradford "Nowhere and back again: a software engineer's tale" in which he described his career in software (development) and how he tried to quit before only to go back and hope to make things better. The second one, which was also the final keynote of the conference was from Olaf Lewitz "Integral Quality" in which he talked about quality across all parts of the system and the organisation and what we could do to change that.
