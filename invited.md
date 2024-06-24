## Invited Speakers

### Martina Seidl (Johannes Kepler Universität Linz, AT)
#### July 2, 09:00 - 10:00

Talk: TBA

Abstract: TBA

### André Platzer (Karlsruhe Institute of Technology, DE)
#### July 2, 14:00 - 15:00

Talk: Uniform Substitution.<br>
or: How I Learned to Stop Worrying and Love the Substitution.

Abstract: Virtually every first-rate logician defined the operation of substitution, and almost everyone got it wrong at some point. Uniform substitutions are Alonzo Church's substitutions that uniformly replace function symbols with terms and predicate symbols with formulas in first-order logic. Uniform substitutions mark the difference between an infinite axiom schema and a finite concrete formula as axioms. This philosophical difference impacts practical theorem provers by being the secret to small soundness-critical prover microkernels. Uniform substitutions replace soundness-critical inference algorithms with mere finite table lookups. With suitable generalizations, uniform substitutions have been shown to succeed in differential dynamic logic for hybrid systems, differential game logic for differential hybrid games, and dynamic logic for communicating hybrid programs. Maybe uniform substitutions can come to a prover near you in the near future?

This talk introduces a relatively complete proof calculus for differential dynamic logic (dL) that is entirely based on uniform substitution, a proof rule that substitutes a formula for a predicate symbol everywhere. Uniform substitutions make it possible to use axioms instead of axiom schemata, substantially simplifying implementations. Instead of subtle schema variables and soundness-critical side conditions on the occurrence patterns of logical variables to restrict infinitely many axiom schema instances to sound ones, the resulting calculus adopts only a finite number of ordinary dL formulas as axioms, which uniform substitutions instantiate soundly. The static semantics of differential dynamic logic and the soundness-critical restrictions it imposes on proof steps is captured exclusively in uniform substitutions and variable renamings as opposed to being spread in delicate ways across the prover implementation. In addition to sound uniform substitutions, this approach introduces differential forms for differential dynamic logic that make it possible to internalize differential invariants, differential substitutions, and derivations as first-class axioms to reason about differential equations. The resulting axiomatization of differential dynamic logic is proved to be sound and relatively complete. This differential-form differential dynamic logic is the theory behind the KeYmaera X theorem prover, an axiomatic tactical theorem prover for hybrid systems.

References:
  + André Platzer. A complete uniform substitution calculus for differential dynamic logic. Journal of Automated Reasoning 59(2), pp. 219-265, 2017. DOI:10.1007/s10817-016-9385-1
  + André Platzer. Uniform substitution at one fell swoop. In Pascal Fontaine, editor, International Conference on Automated Deduction, CADE-27, volume 11716 of LNCS, pp. 425-441. Springer, 2019. DOI:10.1007/978-3-030-29436-6_25


