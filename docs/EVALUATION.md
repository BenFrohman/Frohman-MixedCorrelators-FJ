# Evaluation of the Frohman problem

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0

The object to evaluate:

$$
\langle\alpha,\beta,\gamma\rangle_{0,3}^{F,\langle J\rangle}
=
\int_{\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}}
\bigl[\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}\bigr]^{\mathrm{vir}}.
$$

$W=u^5v+v^6$, $F=W\oplus W\oplus W$, $J$ scales every coordinate of $\mathbb{C}^6$ by a primitive sixth root. State space dimension $2610=2605+5$. Selection rule $k+\ell+m\equiv 1\pmod{6}$.

This file records every number that can be written without inventing a mixed virtual-class integral.

---

## Closed numbers

| quantity | value | why it is closed |
|---|---|---|
| off-rule decoration triples | $180$ of $216$ | $k+\ell+m\not\equiv 1\pmod{6}$ $\Rightarrow$ empty $F$-spin stack $\Rightarrow$ the integral is $0$ because the domain is empty |
| volume on the narrow Lefschetz line | $\int_X\omega^4=6$ | degree of a sextic hypersurface in $\mathbb{P}^5$; one pairing, not the mixed table |
| $\mu(W)$ | $25$ | LTs $v^6,u^5,u^4v$; monomials $4\cdot 6+1=25$ |
| $\mu(W^T)$ | $26$ | LTs $u^4,uv^5,v^{11}$; $11+15=26$; $v^{11}=v^5(5u^4+v^6)-5u^3(uv^5)$ |
| $\lvert\det A\rvert=\lvert\mathrm{Aut}(W)\rvert$ | $30$ | $A=\begin{pmatrix}5&1\\0&6\end{pmatrix}$ |
| $\mu(F)$ | $15625=25^3$ | Thom–Sebastiani of Jacobians |
| $\lvert\mathrm{Aut}(F)\rvert$ | $27000=30^3$ | product of groups |
| $\hat{c}(F)$ | $4$ | $3\times 4/3$ |
| Hilbert of $J$-invariants of $\mathrm{Jac}(F)$ | $(1,426,1751,426,1)$ | degrees $0,6,12,18,24$; sum $2605$ |
| full $h^{2,2}$ | $1752=1751+1$ | extra $1$ is $\omega^2$, algebraic |
| $b_4$ | $2606=2605+1$ | same extra $1$ |
| state space | $2610=2605+5$ | five narrow Lefschetz states $J,\ldots,J^5$ |
| $\mathrm{Jac}(W)$ residue triples | $42$ unordered, values in $\{1,-6\}$ | $\mathrm{Counter}(\{1{:}38,\,-6{:}4\})$; coeff of socle $u^3v^5$; algebra, not $[\overline{\mathcal{M}}]^{\mathrm{vir}}$ |

The four residue triples that evaluate to $-6$ use the relation $u^5=-6v^5$:

- $(1,\,u^4,\,u^4)=-6$
- $(u,\,u^3,\,u^4)=-6$
- $(u^2,\,u^2,\,u^4)=-6$
- $(u^2,\,u^3,\,u^3)=-6$

Full list: `tables/three_points_W.csv` (42 rows).

On pure tensors of $\mathrm{Jac}(F)\simeq\mathrm{Jac}(W)^{\otimes 3}$ the residues factor:

$$
\langle a_1\otimes a_2\otimes a_3,\;
b_1\otimes b_2\otimes b_3,\;
c_1\otimes c_2\otimes c_3\rangle_{\mathrm{Jac}(F)}
=
\prod_{k=1}^{3}\langle a_k,b_k,c_k\rangle_{\mathrm{Jac}(W)}.
$$

That identity is about Jacobian algebras. It is not an identity about $F$-spin moduli.

---

## Not evaluated (the Frohman problem itself)

Every allowed mixed triple from the virtual class stays OPEN.

| kind | decoration rooms | basis slots (size, not a correlator) | status |
|---|---|---|---|
| BBN / BNB / NBB | $3$ | $3\cdot 2605^2=20{,}358{,}075$ | OPEN |
| BNN and permutations | $12$ | $12\cdot 2605=31{,}260$ | OPEN |
| NNN | $21$ | $21$ | one pairing is the volume $6$; the other twenty NNN cells are not filled |

Those slot counts are room sizes. They are not intersection numbers.
Writing $0$, $1$, $6$, or $1/6$ into a mixed BBN/BNN cell is not an evaluation.

---

## What the literature actually computes

- Fan–Shen (arXiv:0902.2327, Michigan Math. J. 2013). FJRW quantum ring of one chain $X^p+XY^q$ against the Milnor ring of the dual. Here $p=5$, $q=6$, $\gcd(4,6)=2$. Group in that paper is typically $G_{\max}$, not $\langle J\rangle$ of the six-variable sum.
- Guéré (arXiv:1509.07047). Hodge integrals $\lambda_g\cup c^{\mathrm{PV}}_{\mathrm{vir}}$ of one chain, any $G$, any genus. Formula yes. Raw genus-zero primary three-points of $F=W\oplus W\oplus W$ not run.
- Krawitz reconstruction. Written for $G_{\max}$ (order $27000$ here). The group of the problem is $\langle J\rangle$ (order $6$).
- Basalaev (arXiv:1610.07428). Non-maximal groups can leave an overall scale unfixed if one uses axioms alone.
- Klemm–Pandharipande (math/0702189). Gromov–Witten of Calabi–Yau fourfolds, including a sextic in $\mathbb{P}^5$, via holomorphic anomaly. That is $\overline{\mathcal{M}}_{g,n}(X,\beta)$, not $\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}$. LG/CY matches the vector spaces $2610=2605+5=\dim H^\bullet(X)$. It does not evaluate the mixed FJRW three-points.

---

## Two ways still required

**Way 1.** Compute the integral on every room that passes $k+\ell+m\equiv 1\pmod{6}$. Thirty-six decoration rooms.

**Way 2.** A reconstruction theorem for $\langle J\rangle$, not $G_{\max}$, whose seeds come from $[\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}]^{\mathrm{vir}}$. WDVV then writes the rest of genus zero. WDVV is a system of equations. It does not invent the seeds.

Locked ranks stay $25$, $26$, $30$.
