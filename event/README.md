Action Items
======

* Garrett: start website
* Roly: solicit feedback from various people (e.g. Sam, Edwin Brady)
* Garrett \& Roly: discuss with Simon/Phil in London
* Garrett \& Roly: outline the event at ABCD meeting on 19 April
* Garrett: contact https://www.rgu.ac.uk/dmstaff/mccall-john re. SICSA assistance

Other potential invitees
------

* Susan Eichenbach (s.eisenbach@imperial.ac.uk)

Event goals
======

The blockquote below contains the draft website content.

>> CoCoPoP
>> ======

>> **8-9 June, 2015. School of Computing Science, University of Glasgow**

>> Behavioural types, such as session types, have the potential to
   transform how we build distributed, concurrent systems. Theoretical
   progress continues apace, but the impact on real-world systems has
   thus far been minimal.

>> The aim of this colloquium is to explore the nascent frontier where
   session types meet practical programming. By examining the state of
   the art, we hope to shed light on the strengths and weaknesses of
   existing approaches, identify obstacles to adoption, and explore the
   challenges of integration with existing programming models. We are
   particularly eager for submissions of tool and compiler
   demonstrations, but also welcome workshop-style talks on related
   issues.

>> Themes
>> ------

>> We solicit demos and talks on any topic that fits within the overall
   focus of the colloquium. The following areas are of particular
   interest, but feel free to surprise us.  Theoretical content is
   welcome as long as its relevance to programming practice is made
   clear.

>> **Dynamic vs. static typing.** Languages with gradual or dynamic
     behavioural typing. Application domains where static typing is
     impractical or where parts of the protocol are hard to enforce
     statically.

>> **Dependent session types**. Value-dependency in protocols is common:
     an SMTP session, for example, starts with a negotiation of buffer
     sizes and features supported by the server.  How do advanced type
     systems, like those of Agda or Haskell, improve the expressivity of
     session types.  How expressive are Idris protocols, compared to
     session types?

>> **Binary and multiparty session types**. Multiparty session types
     provide safety and termination guarantees that cannot be expressed
     by a web of binary sessions. However, work on logical foundations
     for session types, as well as some implementations, have focused
     exclusively on the binary case.  Can these approaches be adopted
     multiparty session types?  Do multiparty session types have a
     logical interpretation?

>> **Interaction with other language features**, such as exceptions,
     and other effects; transactions and error recovery; concurrency
     features like actors and futures.

>> **Unfamiliar application areas** that showcase the wide applicability
     of behavioural types. Possible ideas include computer games; online
     knowledge-sharing engines such as Stack Exchange; workflow systems
     such as EasyChair. Systems not easily captured by existing
     behavioural type systems are also of interest.

>> **IDE and editor features** specific to behavioural typing, such as
     type-directed code completion and syntax highlighting; meaningful
     error messages; debugging and runtime monitoring.

>> **Type inference, type synthesis and type abstraction** techniques
     that check that programs are consistent without requiring the
     programmer to write out onerous types in full.

>> For more information, please contact Garrett Morris
   (garrett.morris@ed.ac.uk) or Roly Perera (roly.perera@glasgow.ac.uk)

Other items we might want to incorporate into the above:
------

* sync vs. async

Discarded ideas
------

An earlier idea was to pose "challenge" problems and invite each
participating team to present solutions to several of these. This would
probably lead to repetition on the day; it would also require some
lead-time and coordination prior to the event. Allowing the participants
to propose the challenge problems would mitigate the problem of
potential repetition, but require even more lead-time and coordination
ahead of the event. Either variant also involves additional work for
participants, which might discourage submissions.

Better to take things one step at a time: first an event emphasising
programming over theory. If that is a success, we can think about a
follow-up event with a less conventional (and more explicitly
comparative) structure.

Programme
======

Schedule questions:

* How long should each session be?
* Should 'demos' and 'talks' have the same amount of time?

Some reference points:

* ICFP - 50 minutes (2 x 25 min)
* ESOP - 120 minutes (4 x 30 min)
* CoCo - 75 minutes (5 x 15 min)
* Typical conference - 90 minutes (3 x 30 min)

Tentative schedule
------

### Day 1

When  | What
---   | ---
08:30 | _Room available_
09:45 | _Breakfast_
10:10 | Introduction (TBD)
10:15 | Talks about tools
11:15 | _Coffee_
11:30 | Talks about tools
12:30 | _Lunch_
13:30 | Demos
14:30 | _Coffee_
14:45 | Demos
15:45 | _Coffee_
16:00 | Demos
16:45 | Roundtable/moderated discussion
17:30 | _Finish_
18:00 | _Pub_
19:00 | _Dinner_

### Day 2

When  | What
---   | ---
9:45  | _Breakfast_
10:15 | General talks
11:15 | _Coffee_
11:30 | General talks
12:30 | _Lunch_
13:30 | Demos
14:30 | _Early finish TBD_


Event name
======

We will follow the familiar, if predictable, convention of using a 3-7
letter acronym for the event. Here's a set of suitable words:

>> *A*pplied
>> *A*spects
>> *B*ehavioural
>> *C*aledonian
>> *C*olloquium
>> *C*ommunication
>> *C*omputation
>> *C*oncrete
>> *C*oncerns
>> *C*oncurrency
>> *D*istribution
>> *I*mplementation
>> *L*anguages
>> *P*ractical
>> *P*ractice
>> *P*rogramming
>> *S*eminar
>> *S*ession
>> *S*ystems
>> *T*ypes

Some possibilities:

Corny idea    | Short for
---           | ---
PSST          | *P*ractical *S*ystems for *S*ession *T*ypes
STIPL         | *S*ession *T*ypes *i*n *P*ractical *L*anguages
PAST          | *P*ractical *A*spects of *S*ession *T*ypes
C<sup>7</sup> | *C*aledonian *C*olloquium on *C*oncrete *C*oncerns in *C*ommunication and *C*oncurrent *C*omputation
CoCoPoP       | *C*ommunication-based *C*omputation: *P*racticalities of *P*rogramming
CoCoNUT       | *C*ommunication-based *C*omputation: *N*ew *U*ses for *T*ypes
