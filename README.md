## The Tyr Language Specification

Currently, this is the initial design document written for a type oriented programming language with an estimated effort of three man years to be implemented.
The project, however, stalled after roughly one man year.
Also, some things turned out to be a bad idea for a real language, as their impact on runtime performance would be inacceptable.
Note that generalized binders were not initially planned as they resulted out of symmetry from the substitutions used to implement block parameters and type instantiations.


## On Process
- After an initial 1.0 Realease, new Language Features should be in a "proposed" release state for one release cycle. A proposed feature can be revoked or changed at the end of a release cycle.
- Release cycles should be 3 years for language and 0.5 years for library.
