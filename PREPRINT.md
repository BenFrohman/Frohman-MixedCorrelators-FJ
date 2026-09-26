# Mixed-sector FJRW correlators of a three-block chain sum

**Author:** Benjamin Stanley Frohman  
**Copyright:** (c) 2026 Benjamin Stanley Frohman  
**License:** Apache-2.0  
**Status:** problem statement and bookkeeping. Correlators of F are not computed.

## Who Guéré is

Jérémy Guéré is a mathematician (Institut Fourier / algebraic geometry) who proved a formula for Hodge integrals in Fan–Jarvis–Ruan–Witten theory of *one chain polynomial*, with any admissible symmetry group, in any genus, with no semisimplicity hypothesis.

- J. Guéré, *Hodge integrals in FJRW theory*, arXiv:1509.07047 (2015); Michigan Math. J. 66 (2017), 831–854.

A chain is one path of variables:

$$
W_{\mathrm{chain}}=x_1^{a_1}x_2+\cdots+x_{N-1}^{a_{N-1}}x_N+x_N^{a_N}.
$$

The output is an identity in the Chow ring of the moduli of (W,G)-spin curves: the Polishchuk–Vaintrob virtual class capped with the top Hodge class λ_g equals a limit of Chern characters of the spin line bundles along the chain. That is a recipe for numbers on *that* spin moduli space.

It is named Guéré because he proved that formula. It is not the author’s theorem.

## Why that name appears next to a new problem

The locked sextic is not one chain. It is three disjoint copies:

$$
F=W\oplus W\oplus W,
\qquad
W=u^5v+v^6,
\qquad
a_1=5,\;a_2=6.
$$

Guéré applies *to each block*. It does not, as stated, apply to F. Thom–Sebastiani tensors Jacobian algebras and state spaces. It does not tensor virtual classes. Mixed insertions — a state from block 1 and a state from block 2 on the same marking, or a broad state tensored with a narrow Lefschetz state — live on *F-spin* moduli, which is not a product of three copies of W-spin moduli.

So: Guéré is the tool for the atom. The new problem is the three-block theory.

## Textbook statement of the Frohman problem

**Setup.** Let

$$
W=u^5v+v^6,\qquad
F=W(x_0,x_3)+W(x_1,x_4)+W(x_2,x_5).
$$

Let J scale every coordinate of C^6 by a primitive sixth root of unity. The pair (F,⟨J⟩) is an admissible Landau–Ginzburg orbifold with ĉ(F)=4.

**State space.** The FJRW state space of (F,⟨J⟩) splits as

- one broad sector, dimension 2605 = dim Jac(F)^J, graded (1, 426, 1751, 426, 1);
- five narrow sectors J^k, k=1..5, each of dimension 1, identified with Lefschetz powers ω^{k-1}.

Total dimension 2610, matching dim H^\u2022(V(F)).

**Problem (Frohman, mixed correlators of (F,⟨J⟩)).** Compute every genus-zero primary three-point number

$$
\langle\alpha,\beta,\gamma\rangle_{0,3}^{F,\langle J\rangle}
=
\int_{\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}}
[\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}]^{\mathrm{vir}}
$$

where α,β,γ run over a basis of the 2610-dimensional state space, including mixed broad–narrow triples and mixed-block broad tensors, subject to the selection rule that the decorations multiply to J.

**What is not this problem.**

- Guéré’s formula on one copy of W.
- Krawitz reconstruction for G_max = Aut(F), order 27000.
- The 42 residue triples of Jac(W) against the socle u^3 v^5.
- The pure-tensor product ⟨a1⊗a2⊗a3, …⟩_Jac(F) = ∏_k ⟨ak,bk,ck⟩_W.
- Clay Term A or Term B on V(F).

## What has been proved (on disk)

1. W is the Fan–Shen chain of type (p,q)=(5,6), gcd(4,6)=2.
2. μ(W)=25, μ(W^T)=26, |Aut(W)|=30. Cubes: 15625 and 27000.
3. Guéré’s hypotheses hold for (W,G) with G ≤ Aut(W), and separately for (W^T,G).
4. Jac(F) ≅ Jac(W)^{⊗ 3}. Identity-sector residue 3-points on *pure tensors* factor.
5. J-invariants of Jac(F) have Hilbert series (1,426,1751,426,1), matching Griffiths primitive Hodge of a smooth sextic fourfold.
6. Narrow ⟨J⟩ sectors are the Lefschetz line; pairing/string among them is axiom-fixed, including ∫_X ω^4 = 6.
7. Mixed broad–narrow virtual-class numbers are *not* a product of the 42 triples and are *not* given by Guéré as stated.

Nothing in (1)–(7) evaluates a mixed integral. Filling those slots with 0, 1, or 6 would be a fake result.

## What would count as a solution

A finite table of all nonzero ⟨α,β,γ⟩_{0,3}^{F,⟨J⟩}, obtained from the virtual class on F-spin moduli (or from a reconstruction theorem that is proved for this group, not quoted from G_max or from one chain), plus the WDVV-generated remainder of genus zero.

That table is not written.
