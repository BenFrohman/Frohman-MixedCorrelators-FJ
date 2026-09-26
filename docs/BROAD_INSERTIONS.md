# Broad insertions in S

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0

Remainder of the seed family after the unit slice:

$$
X_{001}(\alpha,\beta,\varphi_J)
\qquad
\alpha,\beta\in\mathrm{Jac}(F)^{\langle J\rangle},\quad
\alpha\neq\mathbf{1},\;\beta\neq\mathbf{1}.
$$

Same for the two permutations. Those pairs are the broad insertions. They stay OPEN.

Locked ranks: $25$, $26$, $30$.

---

## What a broad state is

The identity sector of $(F,\langle J\rangle)$ is the $J$-invariants of the Jacobian algebra:

$$
H_{\mathrm{broad}}
=
\mathrm{Jac}(F)^{\langle J\rangle}
=
\bigl(\mathrm{Jac}(W)^{\otimes 3}\bigr)^{\langle J\rangle},
\qquad
\dim=2605.
$$

$J$ scales every coordinate of $\mathbb{C}^6$ by $\zeta_6$. Invariants are the summands whose Jacobian degree is $0\bmod 6$. Hilbert function:

| Jacobian degree | dim | Hodge piece (Griffiths) |
|---:|---:|---|
| $0$ | $1$ | $H^{4,0}$ |
| $6$ | $426$ | $H^{3,1}$ |
| $12$ | $1751$ | $H^{2,2}_{\mathrm{prim}}$ |
| $18$ | $426$ | $H^{1,3}$ |
| $24$ | $1$ | $H^{0,4}$ |

Check: $1+426+1751+426+1=2605$.  
The first $1$ is the line $R_0$. It is the unit slice already closed in `docs/UNIT_ON_S.md`. It is not a dummy numeral in a mixed cell.

Non-unit broad space: dimension $2604$.

---

## Pure tensor versus mixed-block

A monomial basis vector of $\mathrm{Jac}(F)$ is a pure tensor

$$
a\otimes b\otimes c,
\qquad
a,b,c\in\mathrm{Jac}(W).
$$

$J$-invariant pure tensors satisfy $\deg a+\deg b+\deg c\equiv 0\pmod{6}$.  
Their three-point algebra on *pure tensors* factors through the $42$ residue triples of $\mathrm{Jac}(W)$. That product is algebra. It is not $X_{001}$.

A mixed-block vector is any linear combination that is not a pure tensor of three one-block classes. Those directions are why Thom–Sebastiani does not evaluate $S$. They remain in the OPEN list.

---

## Homogeneity cut (Degree Axiom)

Primary genus-zero three-points of an FJRW theory vanish unless

$$
\hat{c}(F)\,(g-1)+\sum_i \deg_W(\gamma_i)=3(g-1)+n.
$$

Here $g=0$, $n=3$, $\hat{c}(F)=4$, no $\psi$-classes:

$$
\deg_W(\alpha)+\deg_W(\beta)+\deg_W(\varphi_J)=4.
$$

Only pairs $(\alpha,\beta)$ whose FJRW degrees hit that line can be nonzero.  
That thins $2604^2$. It does not compute the survivors. Survivors stay symbols $X_{001}(\alpha,\beta,\varphi_J)$.

The Degree Axiom is a vanishing constraint. It is not a fill by $0$, $1$, $6$, or $1/6$.

---

## Lefschetz orthogonality is also a constraint

The $2605$ contains the Lefschetz class $\omega^2$ as the extra $1$ in $h^{2,2}=1752=1751+1$. Primitive classes in the $1751$ are orthogonal to complementary Lefschetz powers under $\eta$. That statement is about the *metric* $\eta$. It does not evaluate a three-point with two primitive insertions and $\varphi_J$.

---

## What this pass removes

Dummy fills of the remainder of $S$:

- $0$, $1$, $6$, $1/6$ written into $X_{001}(\alpha,\beta,\varphi_J)$ for non-unit $\alpha,\beta$
- a product of three $\mathrm{Jac}(W)$ residues called $F$-vir
- a product of three Guéré integrals of $W$
- the box counts $31$ and $35$ (already off the record)

What stays:

| object | status |
|---|---|
| unit slice $X_{001}(\mathbf{1},\beta,\varphi_J)$ | $0$ by $\eta$, already on disk |
| $X_{001}(\alpha,\beta,\varphi_J)$, both non-unit | OPEN |
| mixed-block directions inside the $2604$ | OPEN |
| homogeneity survivors | shorter OPEN list |

Evaluating the remainder is Way 1 on decorations $(0,0,1)$ with two non-unit broad states. Witten / Polishchuk–Vaintrob class of six line bundles. Not a numeral.

Score: $180$ empty-stack zeros, plus the unit slice of $S$. Remainder of $S$ open.
