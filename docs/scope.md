# Scope

FRAP develops mathematical notes along one progression:

**Rubik abstract polytopes → N-by-N-by-N cubes → 3-by-3-by-3 → solution
methods → gameplay.**

The starting point is general. Each refinement adds concrete structures,
examples, and methods. Group theory is the underlying thread, introduced
through the puzzles rather than as a separate prerequisite textbook.

| Stage | Content | Group-theoretic thread |
| --- | --- | --- |
| Abstract polytopes | Incidence data, regularity, facet moves, and the Rubik construction | Automorphisms, stabilizers, group actions, and generators |
| N-by-N-by-N cubes | Pieces, moves, orbit types, odd/even behavior, and conventions | Permutation actions, orbits, orientation structure, invariants and quotients |
| 3-by-3-by-3 | Concrete configurations, legal moves, and reachability | Corner/edge permutations, orientation, parity and subgroup structure |
| Solution methods | Move sequences that solve selected subproblems and organize a complete solve | Conjugation, commutators, subgroup chains, cosets and Cayley-graph paths |
| Gameplay | Notation, scrambling, replay, solving and visualization | The same group action and move words give interaction its meaning |

The introduction explains the connections between these topics:
why the starting point is general, what each refinement adds, and how the
mathematics eventually explains solving and gameplay. Detailed constructions,
convention comparisons, and worked facet turns follow in later contributions.

At each refinement, explain the objects, moves, conventions, and particular
claims that connect it to earlier mathematics.

The first substantive Lean target is not selected. The notes and reference
comparison must identify a useful distinct contribution before implementation
begins. A worked exposition of an existing theorem is valuable as a note even
when it does not justify a new implementation.

The present repository is a documentation skeleton. It does not contain a
Lean package, verified puzzle model, or solver.
