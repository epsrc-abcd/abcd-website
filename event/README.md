Action Items
======

Roly to update README with themes.
Garrett to start website.

Introduction
======

* Session types have the potential to transform how we build
  distributed, concurrent systems
* Lots of interesting theoretical work has been done, and several research languages implemented
* Mainstream adoption remains negligible to zero
* Now would be a good time to take stock of where we are in terms of
  adding session types to practical languages

General points
======

* Effort to participate should not be too onerous
* Implementation work to be done in advance of the event
* De-emphasise 1980s internet protocols (boring, unrepresentative).
  Emphasise the wide variety of potential applications. Random example:
  games. Ornela suggested EasyChair.
* Presentations should take the form of demos (running applications,
  type systems, IDE plug-ins, ...)
* What did the session type "world view" bring to the problem?
* Discuss what was easy, what was hard

Basic structure of event
======

Idea #1
------

* We define several "challenge" problems, ranging from easy to hard
* Issue challenge problems 1 month before the event
* Each participating team solves what they can of the challenges

Con: 15 solutions to the same problem will get boring quickly.

Idea #2
------

* Every participating team presents one or more example applications of
  their own choosing

Con: inherently less comparative.

Idea #3 (somewhere between #1 and #2)
------

* Solicit challenge problems from the participants, providing several of our own too
* People can submit problems they know they can easily solve
* Curate the submitted problems into a uniform format
* Then as #1

Con: similar weakness to #1, mitigated somewhat by having more challenge
problems (less overlap on the day).

What we want to accomplish
======

What is the point of the exercise? Let's be clear about this from the outset. For example:

* What's easy (or hard) with particular languages/approaches?
* What is the state of the art in static (and dynamic) protocol-checking?
* What are the main obstacles to rollig out session types to real world languages?
* Do session types suggest new kinds of language?

More specific issues:

* How might dependent types fit in?
* Practical issues relating to expressivity (sync vs. async, binary vs. multiparty)
* Interaction with specific language features, e.g. exceptions
* Inference vs. type checking; global type synthesis vs. projection

Details to work out
======

* Name for event
* How long each presentation? (Maybe 30 min with discussion; CoCo was 10-15 min)
* Can we fill all the presentation slots (potentially 18)
* What could we fill the time with otherwise?
* Are there any potential research outputs?
* Run initial plan past Sam for feedback
* Get basic plan in place _before_ discussing with Simon/Phil in London
* Outline the event at ABCD meeting on 19 April
* Contact https://www.rgu.ac.uk/dmstaff/mccall-john re. SICSA assistance

Tentative Schedule
======

Schedule question: How long should periods be?
* ICFP - 50 minutes, 2 25 minute sessions
* Everything else - 90 minutes, 3 30 minute sessions
* ESOP - 120 minutes, 4 30 minute sessions
Should 'demos' and 'talks' have the same amount of time?

When  | What
---   | ---
08:30 | _Room available_
10:00 | Welcome refreshments (late start to allow people to travel from elsewhere in Scotland)
10:15 | Introduction (TBD)
10:30 | Presentation #1
11:00 | Presentation #2
11:30 | _Short break_
11:45 | Presentation #3
12:15 | Presentation #4
12:45 | _Lunch_
13:45 | Presentation #5
14:15 | Presentation #6
14:45 | Presentation #7
15:15 | _Short break_
15:30 | Presentation #8
16:00 | Presentation #9
16:30 | Discussion (gather points for discussion during the day)
17:30 | _Finish_
18:00 | Pub
19:00 | Dinner

Similar for day 2. Possibly more discussion time if we don't have enough presentations.

Different Schedule
=====

Day 1
-----

When  | What
---   | ---
9:45  | _Breakfast_
10:15 | Talks about tools
11:15 | Coffee
11:30 | Talks about tools
12:30 | _Lunch_
13:30 | Demos
14:30 | Coffee
14:45 | Demos
15:45 | Coffee
16:00 | Demos
16:45 | Roundtable/moderated discussion
17:30 | _Finish_

Day 2
-----

When  | What
---   | ---
9:45  | _Breakfast_
10:15 | Talks about tools
11:15 | Coffee
11:30 | Talks about tools
12:30 | _Lunch_
13:30 |


Event name
======

Assuming we want to follow the usual convention of using a 3-6 letter
acronym for the event, here's a set of words we might like to choose from:

>> *A*pplied
>> *A*spects
>> *B*ehavioural
>> *C*ommunication
>> *C*oncurrency
>> *D*istribution
>> *I*mplementation
>> *L*anguages
>> *P*ractical
>> *P*ractice
>> *P*rogramming
>> *S*ession
>> *T*ypes

Some ideas:

Corny idea | Short for
---        | ---
PSST       | *P*ractical *S*ystems for *S*ession *T*ypes
STIPL      | *S*ession *T*ypes *i*n *P*ractical *L*anguages
PAST       | *P*ractical *A*spects of *S*ession *T*ypes
