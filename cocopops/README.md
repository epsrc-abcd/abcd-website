Action Items
======

* Dimitris: organise catering.
* Roly: email all invitees for final confirmation of attendance.
* Garrett: add programme to website.

Talk proposals
======

Abstract/titles still required from:

Name                             |
---                              |
Dimitris Kouzapas, Glasgow       |
Garrett Morris, Edinburgh        |

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
Victor Dumitrescu     | s1107546@sms.ed.ac.uk
Nicholas Ng           | nickng@imperial.ac.uk

TOTAL 20

Not everyone on the list has confirmed that they will attend, so we will
need to check before making the final catering arrangements.

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

When          | What
---           | ---
08:30         | _Room available_
09:30         | _Welcome_
**Session 1** | **Chair: Dimitris Kouzapas**
09:45         | Raymond Hu
10:30         | Massimo Bartoletti
11:15         | _Coffee_
11:45         | Garrett Morris
12:30         | _Lunch_
**Session 2** | **Chair: Roly Perera**
14:00         | Conor McBride
14:45         | Dennis Griffith
15:30         | _Coffee_
16:00         | Phil Wadler
16:45         | _Finish_
18:00         | _Pub_
19:00         | _Dinner_

### Day 2

When          | What
---           | ---
9:30          | _Arrival_
**Session 3** | **Chair: Garrett Morris**
09:45         | Nicholas Ng
10:30         | Luca Padovani
11:15         | _Coffee_
11:45         | Simon Fowler
12:30         | _Lunch_
**Session 4** | **Chair: Simon Gay**
14:00         | Dimitris Kouzapas
14:45         | Edwin Brady
15:30         | _Coffee_
16:00         | Discussion
16:45         | _Finish_

Titles and abstracts
======

9 TOTAL + 2 PENDING

#### Monitoring Distributed Erlang/OTP Applications with  Multiparty Session Types
##### Simon Fower, Edinburgh.

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

#### Traffic-Dependent Session Types
##### Conor McBride, Strathclyde.

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

#### Type-driven Development for Games and Protocols
##### Edwin Brady, St. Andrews.

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

#### Linearity and the Pi Calculus, Revisited
##### Luca Padovani, Torino.

We discuss a type system that extends the linear pi calculus with pairs,
disjoint sums, and regular data types. The type system adopts a
different approach to linearity: on the one hand, it allows parallel
processes to simultaneously access a data structure containing linear
values; on the other hand, it provides stronger guarantees on the fact
that linear channels are actually used. We demonstrate the type system
at work on a series of examples and present a tool that implements the
corresponding type reconstruction algorithm.

#### Introduction to Sill
##### Dennis Griffith, Illinois.

This talk will provide an overview of the language SILL, a session typed
language currently under development at UIUC and CMU. SILL provides
monadic process expressions, branching subtyping, both affine and linear
types, and an integration of both synchronous and asynchronous
communication. After an overview of the language, we will work through
some examples demonstrating how these features play out in practice.

#### A Contract-Oriented Middleware
##### Massimo Bartoletti, Cagliari.

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

#### Generating endpoint APIs from multiparty session types
##### Raymond Hu, Imperial.

We will demonstrate a work-in-progress tool for generating Java endpoint
APIs from multiparty session types written in Scribble. The aim is to
automatically produce APIs similar to those used in current practices,
to minimise restrictions on endpoint implementation or integration with
other development facilities, while promoting session type safety via
the native type system of the target language. As much of the static
session typing constraints for the source protocol is captured in the
native Java API as possible, with the remainder of the session safety
aspects handled by lightweight run-time checks built into the generated
API.

#### Protocols by Default: Safe MPI Code Generation based on Session Types
##### Nicholas Ng, Imperial.

In this talk I will present a code generation framework for type-safe
and deadlock-free Message Passing Interface (MPI) programs. The code
generation process starts with the definition of a global topology using
Pabble, a protocol specification language based on parameterised
multiparty session types (MPST). An MPI parallel program backbone is
automatically generated from the global specification. The backbone code
can then be merged with the sequential code describing the application
behaviour, resulting in a complete MPI program. This merging process is
fully automated through the use of an aspect-oriented compilation
approach. In this way, programmers only need to supply the intended
communication protocol and provide sequential code to automatically
obtain parallelised programs that are guaranteed free from communication
mismatch, type errors or deadlocks.

#### Propositions as Sessions: An Open Question
##### Phil Wadler, Edinburgh.
