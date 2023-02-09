# SAT Competition 2023: Call for Solvers and Benchmarks

The 2023 SAT Competition is a competitive event for solvers of the Boolean Satisfiability (SAT) problem. It is organized as a satellite event to the 26th International Conference on Theory and Applications of Satisfiability Testing and stands in the tradition of the annual SAT Competitions and Races. The deadline for *submitting benchmarks and solvers* is April 15, 2023 (23:59 GMT -12). More details will be available at the competition website https://satcompetition.github.io/2023/.

The area of SAT solving has seen tremendous progress over the last years. Many problems in applications such as hardware and software verification that seemed to be completely out of reach a decade ago can now be handled routinely. Besides new algorithms and better heuristics, refined implementation techniques turned out to be vital for this success.
To keep up the driving force in improving SAT solvers, we want to motivate developers to present their work to a broader audience and to compare it with that of others.

The 2023 SAT Competition will consist of the following tracks:

* Main Track (including "New Proof Checkers" subtrack, see below)

* Parallel Track

* Cloud Track


## New This Year

**New Proof Checkers**

We received several proposals as a response to our call for verified proof checkers.
More details, including specifiations of input formats, will be available at the competition website.
There will be a special track in which you can select the checker tool-chain to be used for verifying your unsat certificates.


## Aspects to Highlight

**Bring Your Own Benchmarks (BYOB)**

Each Main track participant (team) is required to submit 20 new benchmark instances (not seen in previous competitions). At least 10 of those benchmarks should be "interesting": not too easy (i.e., not solved by MiniSat within one minute on modern hardware) or not too hard (unsolvable by the participant's own solver within one hour on a computer similar to the nodes of the StarExec cluster).

**PAR-2 Scoring Scheme**

The solvers will be ranked based on their penalized average runtime (PAR-2). The PAR-2 score of a solver is defined to be its average runtime over all instances, whereby unsolved instances contribute twice the time limit.

