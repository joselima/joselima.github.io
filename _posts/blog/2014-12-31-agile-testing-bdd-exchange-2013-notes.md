---
layout: post
title: "Agile Testing & BDD Exchange 2013 - Notes"
modified:
categories: blog
excerpt:
tags: [conferences, agile testing, bdd, testing]
image:
  feature:
date: 2014-12-31T15:39:55
modified:
comments: true
share: true
---
Last year, in November (2013), I went to the Agile Testing & BDD eXchange that was held in London and hosted by SkillsMatter.

Here are the notes and main takeaways I took/found during the day, organised by each of the 6 talks.

**"How I learned to stop worrying and love flexible scope" by Gojko Adzic and Christian Hassa**

* Get organisations to benefit more from iterative delivery, allowing flexibility. You can see flexibility is everywhere apart from software, e.g. plane tickets where you can choose to pay more to be allowed to change details of the flight at a later date.
* "Software people" tend to complain about not having enough time, even though most times it's perceived that money is the problem where in fact time available is.
* It's important to change the mental model around flexibility and starting to engage with the business - this will avoid peaks in the backlog.
We need to change the ways to write user stories in order to avoid them becoming issues.
* [Adapt: Why success always starts with failure](http://www.amazon.co.uk/Adapt-Success-Always-Starts-Failure-ebook/dp/B004XCFJ4S/ref=tmm_kin_swatch_0?_encoding=UTF8&sr=8-1-fkmr0&qid=1385112329) book recommendation.
* Palchinsky principles:
  * first thing is to plan for variation: see out new ideas and try new things;
  * survivability: when trying something new, do it on a scale where failure is survivable;
  * selection: seek out feedback and learn from your mistakes as you go along.
* The role of user stories is survivability, we have to get the most of them and make them survive.

Gojko then talked a bit about road maps and related back to survivability of user stories. He explained that road maps are only what we think road maps are when we talk to "software people". For those people, roads maps are just roads, not maps. And actually they are not even roads - you go out one way and you come out the other, so they are more tunnels than they are roads. Features are delivered linearly, and for road maps to stay truthful to its meaning we need different routes, where stories are survivable experiments. User stories would then become our turn by turn navigation, instead of becoming just a destination. The sat nav analogy is quite apt here, where the more sources of feedback (GPS signal, traffic information, peer to peer information, etc.) we have the better the navigation is.

User story example:

As a sales manager<br>
In order to monitor inventory<br>
I want [...] report<br>

"In order to monitor inventory" is the part we have to change - there is no space for feedback here and there needs to be, otherwise we don't know if we have made the right "turn". Once we have a change in our story, we have a success criteria.

* Stop prioritising features and start prioritising business goals.
* Business people that ask for control just want visibility, and we should offer it to them.
* [Gibb Drexler Weisbord team building model: Why, who, what, how?](http://c.ymcdn.com/sites/www.odnetwork.org/resource/resmgr/2012_conf_presentations/david_sibbet.pdf) (Slide #13).

Impact mapping
<figure class="half">
  <img src="/images/bddex_001.jpg" alt="image">
  <img src="/images/bddex_002.jpg" alt="image">
</figure>

* Slice your backlog for impacts
* How much would you pay for information on whether this thing you are working on is giving you what you want? We can probably change how budgeting works.

**"Whose truth is it anyway." by Matt Wynne and Seb Rose**

I was really looking forward to this talk, I had met and listened to Seb Rose only a few weeks before at Agile Testing Days 2013 in Potsdam, Germany and I had started a few months before to read Matt's "The Cucumber book".

Here are some of the highlights:

* Differences between technical and business people demonstrate the value of establishing trust between everyone.
* Iterate on a feature and show the value of it to the business - new features or changes are feedback from the business on their own.
* Writing BDD scenarios will help you keep in the problem domain.
* Most people that are excited by BDD and start practising it are coming from the point of view of test "automation", which makes it a problem.
* Declarative vs. imperative examples.
* web_steps are dead.
* Ubiquitous language is one of the biggest BDD selling points.
* If we can understand the problem, the solution should take care of itself - apply problem solving skills.
* ["Whose domain is it anyway"](http://dannorth.net/2011/01/31/whose-domain-is-it-anyway/) Dan North's blog post.
* In order to write BDD scenarios you have to find a compromise between everyone in the team.
* The need for detail might indicate a lack of trust.
* Level of detail is hard to define - where are you in the pipeline: know all the details in the system or know nothing, it's important to establish the compromise.
* Business people do care about the behaviour of the system.
* Easy is different than simple:
  * Understanding this, and getting there, helps you understand the project and your tests;
  * Time saved at the beginning is the most important of the project.

The testing iceberg:

<figure>
  <img src="/images/bddex_003.jpg" alt="image">
</figure>

**"What do testers do?" by Tony Bruce**

Tony is a good friend of mine, someone that I also met at my first ever conference, Agile Testing Days 2013. He blogs [here](http://dancedwiththesoftware.blogspot.co.uk/), and you can find the "slides" for this presentation [here](http://www.mindmeister.com/348518942/what-do-testers-do-bddx).

Main points:

* Testers don't:
  * randomly click things;
  * check off requirements;
  * represent a safety net or a gateway;
  * if automation works "well" people might not believe you need to do anything;
  * policing developers and nagging them with your defects.
* Testers do:
  * we ask questions - in order to investigate so we can make a decision;
  * we are information hunters;
  * "A tester is somebody who knows that things can be different" - Jerry Weinberg.
  * think in different perspectives:
    * user;
    * troublemaker;
    * stakeholder;
    * developer.
  * apply critical thinking (e.g. 6 thinking hats);
  * sometimes we use silliness;
  * we build relationships;
  * we use experience and irrationality;
  * we communicate, we tell stories and ask questions at the same time;
  * we coach, we mentor, we teach and we learn;
  * we make use of our senses (sad, angry, etc.);
  * we use our technical skills and our humour;
* Testers are not:
  * a safety net (again!);
  * a gateway (again!);
  * a judge.

One thing to take into consideration is that even though testers are not judges, they could consider themselves as an expert witness at the trial. And we can't judge quality because quality is relative from person to person.

The final slide from Tony's presentation illustrates quite well what testers do, I recommend you give it a look!

**"Two sides of the story" by David Evans and Brindusa Axon**

David and Brindusa talked about user stories, the pros and cons and about using them and techniques for improving them.

* The current path to stories is flawed, as we always end up biting off more than we can chew.
* Good story characteristics:
  * INVEST
    * independent;
    * negotiable;
    * valuable;
    * "estimatable";
    * small;
    * testable.
* Typically however we lack the V for valuable.
* The template for story stinks:
  * "Who?" there is almost never just one stakeholder;
  * "What?" what is the benefit of forcing an awkward style?;
  * "Why?" why does the last phrase always sound so weak?;
  * Use templates if it helps get the team going, but once you're going then you don't need templates. Leave them behind.
* Possible alternative for user story writing:
  * `<verb>` a `<noun>`
  * in order to `<improve quality>`, we will do `<some thing>`
  * in order to help `<someone>`
  * achieve `<some value>`
  * we will do `<some thing>`
  * plain language!
* Liz Keogh's blog post ["They're not user stories"](http://lizkeogh.com/2010/02/02/theyre-not-user-stories/)
* A story is a promise to hold a conversation - if you story card is too small to write everything, get yourself a small card. You don't need all the details, have conversations instead.
* Don't let agile be an excuse to ignore documentation.
* Don't let documentation be an excuse to avoid a conversation.
* Documentation: "like a lady's skirt - long enough to cover the subjects, short enough to create interest"
* Short lived (burn this):
  * story;
  * change;
  * acceptance criteria;
  * cards/tasks.
* Long lived (keep this):
  * specification;
  * effect;
  * acceptance tests;
  * living documentation.
* There's no way you can say "I've written the perfect story".
* Signs of success with stories:
  * finding elegantly simple, not simplistic solutions;
  * Product Owner satisfied with doing less than intended;
  * transparent decisions on trade-offs;
  * fewer boomerangs and re-works;
  * highly collaborative creation process.
* Collective product ownership idea in the team.

**"BDD & The business analysts" with Kent McDonald, Jeffrey Davidson, Olaf Lewitz, Jake Calabrese, Leslie Morse and Christ Matts.**

This talk was actually a conversation instead of your standard conference talk. Chris Matt was acting as the "host" and here's a picture of what it looked like from the seats.

<figure>
  <img src="/images/bddex_004.jpg" alt="image">
</figure>

Here are some of the key points talked about:

* Using BDD for scope definition (this was actually my first takeaway from BDD when I first used it, and I will at some point blog about it!).
* BDD is a conversation and it should be easy - it's how we interact with people!
* There are 2 parts: work out what the questions are, and then find the answers.
* You also need to structure it in a way so that the "conversation" doesn't lose fidelity.
* The "given when then" is necessary but not sufficient - conversations need to happen.
  * The necessity comes from offering consistency.
* Real analysis still has to happen, just capturing stories isn't enough as users may not be telling you what reality actually is.
* If you're only writing things down then you are not a business analyst, you're a transcriber.
* Mention of Liz Keogh again, and her blog post on "Estimating complexity".
* BDD focuses on behaviour and needs of stakeholders.
* BDD is only of part of the "Analysis" toolkit, which is not a role.
* We're all doing BDD everyday (or should be doing), we just may not be writing it down and instead are hiding it from everyone.


**"Successful collaboration and MOFF - Applied" by Chris Priest, Jenny Martin and Pete Buckney**

They spoke about using the feedback onion (which apparently wants to become the feedback aubergine (less barriers between layers and won't make you cry so much) and the MOFF collaboration framework.

MOFF - Maximise opportunities for feedback: opportunities, value and quality of interactions and using different techniques to achieve this, such as impact maps.

You can see the models [here](https://prezi.com/pt4lxawofplb/great-big-feedback-onion/).
