# FRAP

FRAP stands for **Formalizing Rubik's Abstract Polytopes**.

Its goal is to connect the general mathematics of Rubik puzzles with the
concrete practice of solving them, through mathematical exposition,
formalization in Lean, and executable algorithms.

## Theme

The question is how a general theory of Rubik puzzles can explain the concrete
methods used to solve them. FRAP begins with Rubik's abstract polytopes,
proceeds to N×N×N cubes, and then studies the 3×3×3 cube, its
solution methods, and gameplay. Each refinement brings additional structure
into view and gives the mathematics more concrete questions to answer.

Abstract polytopes let us study incidence, symmetry, and moves across different
shapes. Layered cubes introduce distinctions between kinds of pieces, their
orientations, and the constraints preserved by turns. The 3×3×3 cube
provides a rich setting for working out those ideas in detail and connecting
them with recognizable solving situations. Comparing descriptions of the same
puzzle helps explain which features come from the puzzle and which depend on
our coordinates, labels, or conventions.

Group theory connects these topics: actions describe moves, orbits and
invariants constrain what is reachable, and subgroups help organize a solve.
The inquiry also encounters geometry, combinatorics, graph theory, and
computational complexity. These areas enter through the questions raised by
the puzzles and their solutions.

Human solving and computer solving give this inquiry two closely related
purposes. For a person, a useful formula connects a recognizable pattern with
a manageable permutation sequence. Understanding conjugation, commutators,
and what a sequence preserves can explain how formulas work and how methods
combine them into a complete solve.

For a computer, the aim is to find solutions according to explicit
optimization goals, such as the fewest moves under a chosen move metric.
Finding a solution, guaranteeing that a method can solve every state in its
domain, and establishing optimality are different mathematical questions.
Studying both human methods and computer algorithms connects structural
understanding with practical choices about how to solve.

## Approach

FRAP shares the methodology of [FCAP](https://github.com/utensil/fcap), applied
to a different mathematical subject and its applications. Scholarly sources,
worked examples, and explicit calculations support a gradual passage from
abstract structures to concrete models and executable procedures. Different
representations and methods are compared through the mathematics they express
and the questions they help answer.

Lean serves both as a language for the mathematics and as a means of
implementing and verifying computations. Formalization is also a way to test
and reshape our understanding of the theory. Missing hypotheses, ambiguous
conventions, and useful reformulations found in Lean should feed back into the
notes; the notes, in turn, explain the constructions and questions that give
the formal work its purpose.

Reference projects inform the inquiry through mathematical principles,
observed behavior, and technical specifications, with inspiration attributed
where it is used. Lean work should offer a distinct contribution; designs are
developed independently rather than copying existing implementations or their
core ideas.

## Origins and guiding intuition

I began playing the 3×3×3 cube decades ago, later learning to solve the
2×2×2 and 4×4×4. I also own a 5×5×5, but have yet to take it
up. The initial questions were practical: how to play, how different solution
methods work, and how algorithms solve scrambled cubes. Those questions led
to the group theory behind the puzzles, mathematics for general N×N×N
cubes, and eventually Giovanni Luca Marchetti's
[*Rubik's Abstract Polytopes*](https://arxiv.org/abs/2502.13518).

FRAP reverses that journey. It begins with the general mathematics and follows
successive refinements back to solving and play, seeking a deeper explanation
of the familiar practice and the wider mathematics encountered along the way.

## Components

- [Forest notes](https://github.com/utensil/forest) develop the mathematical
  explanations, examples, and arguments, connecting the general constructions
  to concrete puzzles and methods.
- Lean work will connect mathematical models, executable algorithms, and
  proofs of their properties, with discoveries feeding back into the notes.
- Solving and gameplay bring the mathematics into use through human formulas,
  computer algorithms, and interactive exploration.

The repository is currently an initial skeleton; it has no Lean implementation
yet.

Licensed under [Apache-2.0](LICENSE).
