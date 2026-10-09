# FRAP

FRAP studies Rubik-style puzzles on abstract regular polytopes: how incidence
data determines the objects that move, how facet rotations act on them, and
what can be said about the resulting permutation groups.

The mathematical study moves from general Rubik abstract polytopes to
N-by-N-by-N cubes, then to the 3-by-3-by-3 cube, solution methods, and gameplay.
Each concrete refinement supplies richer examples and questions. Group theory
connects the stages: actions and generators, orbits and invariants, then
subgroups, commutators, and move sequences.

The project begins with literature-grounded mathematical notes. A companion
note suite is being prepared in [Forest](https://github.com/utensil/forest).
This repository currently contains the project outline and contribution
guidelines. It has no Lean implementation or machine-checked results yet.

The starting point is Giovanni Luca Marchetti's
[*Rubik's Abstract Polytopes*](https://arxiv.org/abs/2502.13518), supported by
the abstract-polytope literature. See [sources](docs/sources.md) for their
roles and [scope](docs/scope.md) for the first mathematical questions.

Future Lean work must follow a precise statement developed in the notes and
offer a distinct contribution beyond the designated reference projects.
Designs are derived independently from literature, mathematical principles,
and behavioral or technical specifications. Reference inspiration is
acknowledged; reference implementations are not copied or ported.

- [Conventions](docs/conventions.md)
- [Contribution assessment](docs/contribution-map.md)
- [Contributing](CONTRIBUTING.md)
- [Attribution](NOTICE.md)

Original repository material is licensed under [Apache-2.0](LICENSE).
