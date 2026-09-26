# Locked integers

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0

Source visual: session file `Grok Table.pdf`. Same rows as TWO_ZEROS_AND_WDVV.md §2.
CSV: `tables/locked_integers.csv`.

These are ranks, Betti numbers, and one volume. They are not structure constants of the A-model on F-spin moduli. They are not mixed correlators.

| Integer | Name | What it is, in one sentence |
|---|---|---|
| 25 | μ(W) | Dimension of ℂ[u, v]/(∂W). Also b₁ of the Milnor fibre of the plane-curve germ (a bouquet of 25 circles). |
| 26 | μ(W^T) | Same for the transpose germ. The extra monomial is v^{11} ∈ (∂W^T). |
| 30 | |det A| = |Aut(W)| | Order of the maximal diagonal symmetry group. Preserved by BHK transpose. Not μ. |
| 15625 = 25³ | dim Jac(F) | Thom–Sebastiani: three copies of the Jacobian algebra. |
| 27000 = 30³ | |Aut(F)| | Product of the three symmetry groups. |
| (1, 426, 1751, 426, 1) | Hilbert of Jac(F)^J | Graded pieces of the J-invariants, degrees 0, 6, 12, 18, 24. Classical primitive Hodge numbers of any smooth sextic in ℙ⁵ (Griffiths 1968–69). |
| 2605 | dim Jac(F)^J | 1 + 426 + 1751 + 426 + 1. The ordinary room. |
| 1752 = 1751 + 1 | h^{2,2}(X) | Primitive piece plus ω². |
| 2606 = 2605 + 1 | b₄(X) | Same extra 1. |
| 5 | narrow line | Fixed loci of J, J², J³, J⁴, J⁵ are the origin. One Lefschetz state each: 1, ω, ω², ω³, ω⁴. |
| 2610 = 2605 + 5 | dim ℋ_{F,⟨J⟩} | Both rooms. Equals dim H•(X). |
| 6 = ∫_X ω⁴ | degree | Volume of a sextic in ℙ⁵. One pairing on the narrow line. |
| {1, −6} | 42 residue triples | Structure constants of Jac(W) against the socle u³v⁵. |

Matching the diamond on this three-chain Jacobian says the B-model vector space of this special sextic has the same dimension, grade by grade, as the B-model of a general one. Hodge numbers are constant in the smooth locus, so that match was expected. It does not compute ⟨α, β, γ⟩_{0,3}^{F,⟨J⟩}.
