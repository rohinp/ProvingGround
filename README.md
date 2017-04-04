# ProvingGround
Proving Ground: Tools for Automated Mathematics

A system under development for (semi-)automated theorem proving, with foundations *homotopy type theory*, using
*machine learning*, both by _reinforcement learing_ using backward-propagation and using natural language processing to assimilate part of the mathematics literature.

## Implemented:

* Most of Homotopy type theory.
* Reinforcement learning abstractions.
* Dynamics for learning in a domain-specific case - the andrews-curtis conjecture.
* Most of the dynamics for learning with homotopy type theory.
* An _akka-actor_ based system for continuous learning with tuning and communication.
* Skeletons of:
  * an akka-http server
  * a play-framework server
  * using stanford-corenlp tools.

## Documentation:

There is not much besides the source.

* The [website](http://siddhartha-gadgil.github.io/ProvingGround/) has the most current documentation.
* The [notes](https://github.com/siddhartha-gadgil/ProvingGround/tree/master/notes) folder contains Jupyter notebooks illustrating some of the code.
* Some documentation is in the [project wiki](https://github.com/siddhartha-gadgil/ProvingGround/wiki).

## Running

At present the main way to run the code is to load a console (for an alternative, visit the [website](http://siddhartha-gadgil.github.io/ProvingGround/)). For example, in the home of the project, run
```
sbt mantle/test:console
```
to pop up a nice console (Li Haoyi's ammonite repl), with many imports already in scope.
