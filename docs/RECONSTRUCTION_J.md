# What would close the line

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0

The object:

$$
\langle\alpha,\beta,\gamma\rangle_{0,3}^{F,\langle J\rangle}
=
\int_{\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}}
\bigl[\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}\bigr]^{\mathrm{vir}}.
$$

Two ways to close it. Neither is written.

---

## Way 1. Evaluate the virtual class

For every ordered decoration triple \((k,\ell,m)\) with

$$
k+\ell+m \equiv 1 \pmod{6}
$$

and every basis triple \((\alpha,\beta,\gamma)\) in the corresponding room of
\(\mathcal{H}_{F,\langle J\rangle}\) (dim 2610), compute the integral above.

36 decoration rooms. Coarse split: BBN 3, BNN 12, NNN 21.
180 off-rule triples are empty-stack zeros. They are already closed.

Guéré's chain formula computes Hodge integrals of *one* chain, any G.
It does not evaluate this integral on the three-block sum F.
Krawitz's axioms are written for \(G_{\max}\).

---

## Way 2. A reconstruction theorem for \(\langle J\rangle\)

**Theorem (not proved).**
Let \(W = u^5 v + v^6\) and \(F = W \oplus W \oplus W\).
Let \(J\) scale every coordinate of \(\mathbb{C}^6\) by a primitive sixth root.
The pair \((F,\langle J\rangle)\) is an admissible Landau–Ginzburg orbifold.

There exists a finite list of seed correlators

$$
S \subset \bigl\{\langle\alpha,\beta,\gamma\rangle_{0,3}^{F,\langle J\rangle}\bigr\}
$$

such that every other genus-zero primary number of \((F,\langle J\rangle)\)
is uniquely determined by S together with WDVV, the pairing, and the
selection rule \(k+\ell+m \equiv 1 \pmod{6}\).

The list S must be computed from
\([\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}]^{\mathrm{vir}}\),
not from \(\mathrm{Jac}(W)\) residues and not from three Guéré integrals of W.

After S is known, WDVV writes the rest of genus zero.

---

## Seeds we have, seeds we do not

Have:
- pairing on the narrow Lefschetz line, one number \(\int_X \omega^4 = 6\)
- state-space grading \((1,426,1751,426,1)\) plus 5 narrow states
- 42 residue triples of \(\mathrm{Jac}(W)\), values in \(\{1,-6\}\) — algebra, not F-vir
- selection rule and the 216/36/180 census

Do not have:
- any mixed BBN or BNN number from the virtual class of F-spin moduli
- a theorem that the FJRW axioms plus pairing determine the \(\langle J\rangle\)-ring of this six-variable sum uniquely (Basalaev 2017: for some non-maximal groups the axioms reconstruct only up to scaling)
- Krawitz for this G (Krawitz is \(G_{\max}\), order 27000, not order 6)

Basalaev, *6-dimensional FJRW theories of the simple-elliptic singularities*, arXiv:1610.07428:
non-maximal groups can leave an overall scale unfixed if one uses axioms alone.
Particular numerical values need an extra evaluation. That is the situation here,
in six variables and dimension 2610 rather than 6.

---

## What WDVV is on this host

WDVV is a system of quadratic relations among the 36 rooms.
It relates BBN cells to BNN cells once a few seeds exist.
It does not invent the seeds.
Writing 0, 1, 6, or 1/6 into an OPEN cell is not WDVV.

---

Locked ranks remain \(\mu(W)=25\), \(\mu(W^T)=26\), \(|\det A|=30\).
The line stays open until Way 1 or Way 2 is supplied.
