Action Items
======

* Dimitris: organise catering.
* Roly: email all invitees for final confirmation of attendance.
* All: finalise programme.

Talk proposals
======

Name                             | Title                                                                          | Abstract?
---                              | ---                                                                            | ---
Simon Fowler, Edinburgh          | Monitoring Distributed Erlang/OTP Applications with Multiparty Session Types   | Yes
Conor McBride, Strathclyde       | Traffic-Dependent Session Types                                                | Yes
Edwin Brady, St. Andrews         | (TBC)                                                                          | Yes
Raymond Hu, Imperial             | (TBC)                                                                          | Requested
Luca Padovani, Torino            | Linearity and the Pi Calculus, Revisited                                       | Yes
                                 |
Dennis Griffith, Illinois        | Introduction to Sill                                                           | Yes
Massimo Bartoletti, Cagliari     | A contract-oriented middleware                                                 | Yes
Dimitris Kouzapas, Glasgow       | (TBC)                                                                          | Yes
Garrett Morris, Edinburgh        | (TBC)                                                                          | Requested
Nicholas Ng, Imperial            | (TBC)                                                                          | Requested
                                 |
Phil Wadler, Edinburgh           | Propositions as Sessions: An Open Question                                     | N/A

TOTAL 11

Attending
=====

Confirmed or likely to attend
-----

Name                  | Email
---                   | ---
Roly Perera           | roly.perera@glasgow.ac.uk
Rob Stewart	      | r.stewart@hw.ac.uk
Craig McLaughlin      | 1002524M@student.gla.ac.uk
Simon Fowler	      | simon.fowler@ed.ac.uk
Philip Wadler	      | wadler@inf.ed.ac.uk
                      |
Conor McBride	      | conor.mcbride@cis.strath.ac.uk
Bob Atkey	      | bob.atkey@ed.ac.uk
Dimitris Kouzapas     |	dimitris.kouzapas@googlemail.com
Ornela Dardha	      | ornela.dardha@glasgow.ac.uk
Sam Lindley	      | sam.lindley@ed.ac.uk
                      |
Edwin Brady	      | ecb10@st-andrews.ac.uk
Simon Gay	      | simon.gay@glasgow.ac.uk
Wim Vanderbauwhede    | wim.vanderbauwhede@glasgow.ac.uk
Dennis Griffith       | dgriffi3@illinois.edu
Raymond Hu            | raymond.hu05@imperial.ac.uk
                      |
Garrett Morris        | garrett.morris@ed.ac.uk
Massimo Bartoletti    | bart@unica.it
Luca Padovani         | luca.padovani@di.unito.it

TOTAL 18

Not everyone on the list has confirmed that they will attend, so we will
need to check before making the final catering arrangements.

Other potential attendees (awaiting response)
-----

Name                   | Email
---                    | ---
Jack Williams          | s0938550@sms.ed.ac.uk

Catering notes
======

Need to organise:

* Coffees (when, how many)
* Fruit/snacks (buying our own?)
* Dinner reservation for Monday night
* Lunch orders once we have final numbers

Programme
======

Tentative schedule
------

### Day 1

When  | What
---   | ---
08:30 | _Room available_
09:30 | _Welcome_
09:45 | Talk 1
10:30 | Talk 2
11:15 | _Coffee_
11:45 | Talk 3
12:30 | _Lunch_
14:00 | Talk 4
14:45 | Talk 5
15:30 | _Coffee_
16:00 | Talk 6
16:45 | _Finish_
18:00 | _Pub_
19:00 | _Dinner_

### Day 2

When  | What
---   | ---
9:30  | _Arrival_
09:45 | Talk 7
10:30 | Talk 8
11:15 | _Coffee_
11:45 | Talk 9
12:30 | _Lunch_
14:00 | Talk 10
14:45 | Talk 11
15:30 | _Coffee_
16:00 | Discussion
16:45 | _Finish_

Titles and abstracts
======

### Simon Fower. Monitoring Distributed Erlang/OTP Applications with  Multiparty Session Types

Just as data types encode the data used in applications, session types encode
communication patterns, providing guarantees that protocols are safe and
that programs conform to their prescribed protocols. Traditionally, session
types have been checked statically at compile time.

An alternative approach is to use session types as a tool for lightweight
runtime verification. This is especially useful in languages with
dynamically-checked types, and in languages where session participants
cannot always be assumed to be available.

In this talk, I'll explain my work on adding dynamic monitoring of session
types to distributed Erlang/OTP server applications. Building on the work
on Multiparty Session Actors by Neykova and Yoshida, I'll talk about how
session types fit into standard OTP design patterns such as supervision
trees, how to detect and handle failures, and demonstrate some larger
case studies such as a DNS server.

### Conor McBride. Traffic-Dependent Session Types

Sending and receiving in session types resonate with the dependently
typed notions of Sigma and Pi types, respectively. However, when we try
to build a higher-order notion of session type from Sigma and Pi, we
find we must take care upon what exactly dependent session types can
depend. What gets substituted for the bound variables when we
instantiate the range of such a type? I argue that the correct answer to
this question is not the session *participant*, but the session
*traffic*. I show how to construct in Agda a universe of session types
which enforce dependency only on traffic, and I offer some
interpretations of these types as sets of participating processes.

### Edwin Brady. Type-driven Development for Games and Protocols

Idris (http://idris-lang.org/) is a general purpose pure functional
programming language with dependent types. In Idris, types are a first
class language construct, meaning that they can be manipulated and
computed like any other language construct. It encourages a type-driven
style of development, in which programmers give types first and use
interactive editing tools to derive programs. Introductory examples
typically involve length preserving operations on lists, or ordering
invariants on sorting.

Realistically, though, programming is not so simple: programs interact
with users, communicate over networks, manipulate state, deal with
erroneous input, and so on. In this talk I will show how advanced type
systems allow us to express such interactions precisely, and how they
support verification of stateful systems as a result.

The talk will include several examples, leading to a verified
implementation of a word game (Hangman). I will show how Type-driven
Development allows programmers to specify the game rules in a direct and
concise style, and how it leads to an implementation, guaranteed to
correctly follow the rules by type checking.

### Luca Padovani. Linearity and the Pi Calculus, Revisited

We discuss a type system that extends the linear pi calculus with pairs,
disjoint sums, and regular data types. The type system adopts a
different approach to linearity: on the one hand, it allows parallel
processes to simultaneously access a data structure containing linear
values; on the other hand, it provides stronger guarantees on the fact
that linear channels are actually used. We demonstrate the type system
at work on a series of examples and present a tool that implements the
corresponding type reconstruction algorithm.

### Dennis Griffith. Introduction to Sill

This talk will provide an overview of the language SILL, a session typed
language currently under development at UIUC and CMU. SILL provides
monadic process expressions, branching subtyping, both affine and linear
types, and an integration of both synchronous and asynchronous
communication. After an overview of the language, we will work through
some examples demonstrating how these features play out in practice.

### Massimo Bartoletti. A contract-oriented middleware

Developing distributed applications typically requires to integrate new
code with preexisting third-party services, e.g., e-commerce facilities,
maps, etc. These services cannot always be assumed to smoothly
collaborate with each other; rather, they live in a “wild” environment
where they must compete for resources, and possibly diverge from the
intended behaviour in case they find it convenient to do so.

To overcome this issue, some recent works have proposed to discipline
the interaction of mutually distrusting services through behavioural
contracts. The idea is a bottom-up composition, where only those
services with compliant contracts can establish sessions through which
they interact. We exploit a theory of timed behavioural contracts to
design and implement a message-oriented middleware where distributed
services can be dynamically composed, and their communications monitored
so to guarantee safe interactions.
