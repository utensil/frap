# Sources and reference roles

## Literature

| Source | Role |
| --- | --- |
| Giovanni Luca Marchetti, [*Rubik's Abstract Polytopes*](https://arxiv.org/abs/2502.13518), 2025, v1 | Starting incidence-pair construction, facet moves, and Rubik groups. The hypercube argument is described as a sketch; the opening does not depend on completing it. |
| Egon Schulte, [*Regular Incidence Complexes, Polytopes, and C-Groups*](https://arxiv.org/abs/1711.02297), 2017 | Incidence and flag-connectivity background; distinguish general incidence complexes from polytopes. |
| Peter McMullen and Egon Schulte, *Abstract Regular Polytopes*, Cambridge University Press, 2002 | Canonical book reference for the abstract theory. Exact passages must be inspected before attributing a specific claim to it. |
| Stefano Bonzio, Andrea Loi and Luisa Peruzzi, [*On the n×n×n Rubik's Cube*](https://arxiv.org/abs/1708.05598), arXiv 2017 / journal 2018 | N-cube configurations and solvability under the authors' conventions. |
| Daniel Salkinder, [*n×n×n Rubik's Cubes and God's Number*](https://arxiv.org/abs/2112.08602), 2021 | N-cube structure and the later connection between groups and move-count questions. |

Notes should identify the version and precise passage supporting a claim,
explain changed notation, and distinguish a source theorem from a derivation
added in the exposition. A bibliography entry alone does not settle a claim.

## Reference projects for contribution assessment

| Project | Intended comparison |
| --- | --- |
| [ooovi/AbstractPolytopes](https://github.com/ooovi/AbstractPolytopes) | Existing abstract-polytope formalization coverage. |
| [TauCetiProject/TauCeti](https://github.com/TauCetiProject/TauCeti) | General algebra, permutations, and group-action APIs. |
| [vihdzp/rubik-lean4](https://github.com/vihdzp/rubik-lean4) | Existing 3-by-3 Rubik formalization coverage, if a future contribution overlaps it. |
| [omar826/N_Rubiks_Cube](https://github.com/omar826/N_Rubiks_Cube) | Existing N-cube formalization coverage, if a future contribution overlaps it. |
| [joom/rubik](https://github.com/joom/rubik) | Certified-solver behavior and proof-boundary comparison, if solving enters scope. |

This is an initial comparison inventory, not an exhaustive novelty audit,
dependency list, or statement that these projects have been built and checked
by FRAP. Pin revisions and inspect relevant public behavior/specifications
when assessing a concrete contribution. Record unknown coverage as unknown.
No implementation files are imported by this skeleton.
