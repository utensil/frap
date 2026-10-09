# Opening conventions

Use `d` for abstract polytope dimension. Reserve `N` for the layer count of
a physical three-dimensional N-by-N-by-N cube when discussing that separate
construction. Neither parameter is an implicit replacement for the other.

For a rank-d abstract polytope, use ranks -1 and d for the least and greatest
faces, and 0 through d-1 for the proper faces. A facet has rank d-1.

Use functional composition: `(ab)(x) = a(b(x))`, so the rightmost move acts
first. Specify explicitly if an external notation uses another order.

Use `R(P)` for Marchetti's set of proper incident pairs `(F,G)` with `F <= G`.
It is the set acted upon, not the generated permutation group. Write
`Gamma_R(P)` for that group in plain text. The notes may use mathematical
typesetting for the same notation.

A move names both its facet `H` and its rotation. When a rotation of the
facet section acts on a face outside that section, explain its extension to
an automorphism of the whole polytope. Do not treat that extension as implicit
in a partial action.

Check rotation-group indices and connectivity hypotheses against the actual
source passages before turning them into formal definitions. These opening
conventions do not freeze a Lean API or settle the unresolved source questions.
