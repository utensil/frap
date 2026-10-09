# Contributing

Start with a mathematical question and the relevant literature. Develop the
definitions, hypotheses, conventions, argument, and an informative example
in the notes before proposing a Lean implementation.

For substantive Lean work, the contribution assessment must explain what is
absent from the designated reference projects. A new namespace, a port to a
different prover, or an independent rewrite of an existing core idea is not
enough. Independently designed ideas and literature ideas not implemented
in the reference set are candidates, not automatic novelty claims.

Use reference projects through observed behavior, technical specifications,
and mathematical principles. Do not copy implementation text, source-derived
pseudocode, representations, or proof architecture. Record which references
informed the work and derive the design independently. Ordinary mathematical
facts remain ordinary mathematical facts; cite them without claiming them
as innovations.

Keep code changes small and tied to the selected contribution. Reuse general
library APIs where appropriate instead of rebuilding standard group theory.
Pin actual dependencies when implementation begins.

For notes, check load-bearing formulas against the source pages and explain
convention changes. For Lean, check the actual theorem statement against the
note, build the relevant package, and inspect admitted assumptions. Executable
tests and external comparisons supplement proofs; they do not replace them.

Open a pull request with the problem, resulting behavior or mathematical
statement, attribution, and relevant validation. The initial skeleton requires
explicit human approval before merge. This is a maintainer decision, not an
automatic consequence of passing checks.
