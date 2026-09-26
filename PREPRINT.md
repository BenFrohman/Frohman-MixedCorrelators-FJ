# Mixed-sector FJRW correlators of a three-block chain sum

**Author:** Benjamin Stanley Frohman  
**Copyright:** (c) 2026 Benjamin Stanley Frohman  
**License:** Apache-2.0  
**Status:** problem statement and bookkeeping. Correlators of F are not computed.

## Who Guéré is

Jérémy Guéré is a mathematician (Institut Fourier / algebraic geometry) who proved a formula for Hodge integrals in Fan–Jarvis–Ruan–Witten theory of *one chain polynomial*, with any admissible symmetry group, in any genus, with no semisimplicity hypothesis.

- J. Guéré, *Hodge integrals in FJRW theory*, arXiv:1509.07047 (2015); Michigan Math. J. 66 (2017), 831–854.

A chain is one path of variables. The output is an identity in the Chow ring of the moduli of (W,G)-spin curves. It is named Guéré because he proved that formula. It is not the author’s theorem.

## Why that name appears next to a new problem

The locked sextic is not one chain. It is three disjoint copies F = W ⊕ W ⊕ W with W = u^5 v + v^6. Guéré applies to each block. It does not, as stated, apply to F. Thom–Sebastiani tensors Jacobian algebras. It does not tensor virtual classes.

## Textbook statement of the Frohman problem

**Problem (Frohman, mixed correlators of (F, ⟨J⟩)).** Compute every genus-zero primary three-point number

    ⟨α, β, γ⟩_{0,3}^{F,⟨J⟩} = ∫_{[M-bar_{0,3}^{F,⟨J⟩}]^{vir}}

where α, β, γ run over the 2610-dimensional state space (2605 + 5), including mixed broad–narrow triples, subject to the selection rule that decorations multiply to J.

## Decoration census (new on disk)

`6^3 = 216` ordered triples. `36` allowed, `180` off-rule zeros (empty stack).

- `tables/all_216_decoration_triples.csv`
- `tables/allowed_36.csv`
- `docs/ALL_216.md`
- `docs/TWO_ZEROS_AND_WDVV.md` — why the 180 zeros are not the 36 values; WDVV as equations not fills; locked integers as ranks not correlators.

BBB `(0,0,0)` is among the 180. Three identity decorations fail the selection rule.

Allowed mixed cells (BBN 20,358,075 slots, BNN 31,260 slots) stay OPEN. They are not filled by 0, 1, 6, or 1/6.

## What has been proved (on disk)

1. W is the Fan–Shen chain of type (p,q)=(5,6), gcd(4,6)=2.
2. μ(W)=25, μ(W^T)=26, |Aut(W)|=30. Cubes: 15625 and 27000.
3. Guéré’s hypotheses hold for each block separately.
4. Jac(F) ≅ Jac(W)^{\u2297 3}. Identity-sector residue 3-points on pure tensors factor. 42 triples, values in {1,-6}.
5. J-invariants of Jac(F) have Hilbert series (1,426,1751,426,1), matching Griffiths primitive Hodge of a smooth sextic fourfold.
6. Narrow ⟨J⟩ sectors are the Lefschetz line; one pairing is ∫_X ω^4 = 6.
7. Selection rule: 216 = 36 + 180. The 180 are real zeros by empty stack. The 36 are rooms, not numbers.

Nothing in (1)–(7) evaluates a mixed integral.

## What would count as a solution

A finite table of all nonzero ⟨α, β, γ⟩_{0,3}^{F,⟨J⟩}, obtained from the virtual class on F-spin moduli (or from a reconstruction theorem proved for ⟨J⟩, not quoted from G_max or from one chain), plus the WDVV-generated remainder of genus zero.

That table is not written.
