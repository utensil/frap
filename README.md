# FRAP

FRAP stands for **Formalizing Rubik's Abstract Polytopes**.

Its goal is to connect the general mathematics of Rubik puzzles with the
concrete practice of solving them, through mathematical exposition,
formalization in Lean, and executable algorithms.

## Theme

The question is how much the general theory can reveal about the puzzles we
play. Starting with Rubik's abstract polytopes, FRAP proceeds to N-by-N-by-N
cubes, then the 3-by-3-by-3 cube, its solution methods, and gameplay. Each
refinement introduces richer structures, examples, and questions, eventually
bringing the abstract mathematics back to familiar turns and move sequences.

Group theory connects these topics, while the questions lead into broader
mathematics: the combinatorics of configurations, geometry and symmetry,
invariants and reachability, and the search for efficient solutions. The aim
is to understand how these ideas explain one another through the puzzles.

For human solving, formulas must connect recognizable patterns with manageable
move sequences. For computer solving, algorithms pursue explicit optimization
goals, such as the fewest moves under a chosen move metric. Understanding why
a method works, what makes it usable by a person, and how a computer can seek
an optimal solution gives the general theory a concrete purpose.

## Approach

FRAP shares the methodology of [FCAP](https://github.com/utensil/fcap), applied
to a different mathematical subject and its applications. Scholarly sources,
worked examples, and explicit calculations support a gradual passage from
abstract structures to concrete models and executable procedures. Lean serves
both as a language for the mathematics and as a means of implementing and
verifying computations.

Formalization also tests our understanding of the theory. Missing hypotheses,
ambiguous conventions, and useful reformulations found in Lean should feed
back into the mathematical notes. In the other direction, the notes explain
the constructions and questions that give the formal work its purpose.

Reference projects inform the inquiry through mathematical principles,
observed behavior, and technical specifications, with inspiration attributed
where it is used. Lean work should offer a distinct contribution; designs are
developed independently rather than copying existing implementations or their
core ideas.

## Origins and guiding intuition

I began playing the 3-by-3-by-3 cube decades ago, later learning to solve the
2-by-2-by-2 and 4-by-4-by-4. I also own a 5-by-5-by-5, but have yet to take it
up. The initial questions were practical: how to play, how different solution
methods work, and how algorithms solve scrambled cubes. Those questions led
to the group theory behind the puzzles, mathematics for general N-by-N-by-N
cubes, and eventually Giovanni Luca Marchetti's
[*Rubik's Abstract Polytopes*](https://arxiv.org/abs/2502.13518).

FRAP reverses that journey. It begins with the general mathematics and follows
successive refinements back to solving and play, seeking a deeper explanation
of the familiar practice and the wider mathematics encountered along the way.

## Components

- [Forest notes](https://github.com/utensil/forest) develop the mathematical
  explanations, examples, and arguments.
- Lean work will connect mathematical models, executable algorithms, and
  proofs of their properties.
- Solving and gameplay provide the concrete setting for human methods,
  computer algorithms, and their mathematical interpretation.

The repository is currently an initial skeleton; it has no Lean implementation
yet.

Licensed under [Apache-2.0](LICENSE).
