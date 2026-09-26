# Invented mixed numbers versus real numbers

Author: Benjamin Stanley Frohman.
Copyright (c) 2026 Benjamin Stanley Frohman.
License: Apache-2.0.
Repo: BenFrohman/Frohman-MixedCorrelators-FJ

This note is the honest split. It is not a table of
⟨α, β, γ⟩_{0,3}^{F,⟨J⟩}.

## What the invention was

In session drafts, the three numerals 0, 1, and 6 were treated as if they
could be written into every mixed cell of the Frohman problem. A screenshot
fragment also mentions 1/6 next to “evaluate [Mbar]^{vir}”.

That is not an evaluation of the virtual class. It is a category error:
taking numbers that are real in *other* tables and pasting them into the
mixed slots.

The live tree at commit 3c3b1061 does **not** contain those fills.
`docs/MIXED_TABLE.md` and `tables/proved_not_proved.csv` already list
“Filling mixed slots with 0, 1, or 6” under **Not proved**.

## What 0, 1, 6, and 1/6 actually are

### 1 — residue coefficient, one block

On Jac(W) = ℂ[u,v]/(∂W), the socle is the monomial u^{3}v^{5} (weighted
degree 8). For three monomials a, b, c with deg a + deg b + deg c = 8,
the structure constant

    ⟨a, b, c⟩_W  :=  coefficient of u^{3}v^{5} in a·b·c

is 1 for most allowed triples. That is Jacobian algebra of one chain
atom. Literature: the B-model of an isolated quasihomogeneous singularity;
see Fan–Shen for the dual-chain ring comparison (p=5, q=6, gcd(4,6)=2).

It is not ∫ [M-bar_{0,3}^{F,⟨J⟩}]^{vir}.

### −6 — same algebra, Euler relation

The Euler identity on W = u^{5}v + v^{6} gives u^{5} = −6 v^{5} in Jac(W)
(characteristic 0). Four unordered triples use that relation and return
−6 instead of 1. Same table: `tables/three_points_W.csv`.
Values live in {1, −6}, not in {0, 1, 6}.

### 0 — vanishing off a constraint, not vanishing of mixed cells

Two real zeros, both cheap:

1. Jac(W): deg a + deg b + deg c ≠ 8 ⇒ residue 0.
2. Decorations: k + ℓ + m ≢ 1 (mod 6) ⇒ the FJRW selection rule kills
   the triple before any virtual class is evaluated.

Neither statement evaluates an *allowed* mixed triple
(BBN, BNN, or mixed-block BBB) on F-spin moduli. Selection-rule zeros
are zeros of the wrong set.

### 6 — geometric volume, narrow line

    ∫_X ω^{4} = 6

is the degree of a sextic hypersurface in ℙ^{5}. It is one pairing on
the Lefschetz / narrow line (the five states J, J^{2}, J^{3}, J^{4}, J^{5}).
It is classical intersection theory, Lefschetz (1,1) plus hard Lefschetz,
not a mixed correlator. Writing 6 in 20,358,075 BBN slots or 31,260 BNN
slots would be a fake result.

### 1/6 — other people’s examples, not this atom

The numeral 1/6 appears in published FJRW tables for *different*
potentials (Francis, *Computational techniques in FJRW theory*, ATMP 2015:
e.g. ⟨1, Z, Z⟩ = −1/6 on some Fermat/chain examples of small Milnor
number). No computation in this lab produced 1/6 for (F, ⟨J⟩).
Seeing 1/6 next to “evaluate [Mbar]^{vir}” in a session screenshot is
contamination from that literature, not a number for this problem.

## What the literature actually supplies for this pair

| Object | Source | What it gives | What it does not |
|---|---|---|---|
| Fan–Shen (5,6) | Fan–Shen, FJRW quantum ring of X^p + XY^q | ring of one dual chain vs Jac of the other; dims 25 / 26 | mixed 3-points of F |
| Guéré chain formula | Guéré 2015–17 | Hodge-integral identity on *one* chain W-spin moduli | a number, or a product formula for F |
| Krawitz reconstruction | Krawitz | reconstruction for G_max | reconstruction for ⟨J⟩ ⊂ G_max |
| Griffiths residue | Griffiths 1968–69 | primitive Hodge dims (1,426,1751,426,1) | a miss class; a mixed correlator |
| Lefschetz volume | classical | ∫ ω^{4} = 6 | the mixed table |
| Thom–Sebastiani | algebra | Jac(F) ≅ Jac(W)^{⊗ 3}, dim 15625 | tensor of *virtual classes* |

## What would be a real mixed number

A real entry in an OPEN cell is a number obtained from one of:

1. the virtual class [M-bar_{0,3}^{F,⟨J⟩}]^{vir} on F-spin moduli, or
2. a reconstruction theorem proved for the group ⟨J⟩ (not G_max, not
   one chain).

Until that computation exists, the cells stay OPEN. WDVV can generate
the rest of genus zero *after* those primary 3-points are known. WDVV
does not invent them.

## Locked integers (unchanged)

μ(W) = 25, μ(W^T) = 26, |det A| = |Aut(W)| = 30.
Cubes: 15625 and 27000.
v^{11} = v^5(5u^4 + v^6) − 5u^{3}(uv^5) ∈ (∂W^T).

Those are not mixed correlators either.
