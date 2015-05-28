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
Phil Wadler, Edinburgh           | Extending CP to pi-calculus (TBC)                                              | Requested

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

### Edwin Brady.

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
