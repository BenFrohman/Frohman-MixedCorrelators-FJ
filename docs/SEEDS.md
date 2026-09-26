# Seeds

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0

The only mixed seed family is

$$
S=\bigl\{
X_{001}(\alpha,\beta,\varphi_J),\;
X_{010}(\alpha,\varphi_J,\beta),\;
X_{100}(\varphi_J,\alpha,\beta)
\bigr\}.
$$

Right seeds stay right. Dummy seeds are omitted.

---

## In the seed list

| object | what it is |
|---|---|
| $S$ | three rooms $(0,0,1)$, $(0,1,0)$, $(1,0,0)$; must come from $[\overline{\mathcal{M}}]^{\mathrm{vir}}$ |
| unit $1$ | CohFT unit in the identity sector |
| $\eta$ | pairing: Lefschetz line includes $\int_X\omega^4=6$; broad side is the residue pairing of $\mathrm{Jac}(F)^{\langle J\rangle}$ |

The unit and $\eta$ are structure. They are not mixed three-points and they do not fill $X_{001}$.

---

## Out of the seed list

| omitted | reason |
|---|---|
| $42$ Jac$(W)$ residues in $\{1,-6\}$ | one-block algebra, not $F$-vir |
| three Guéré integrals of $W$ | one chain, not three on one curve |
| $0$, $1$, $6$, $1/6$ in a BBN/BNN cell | invented fills |
| Krawitz $G_{\max}$ seeds | wrong group |

Those rows live in `tables/not_seeds.csv`. They are not inputs to WDVV for $(F,\langle J\rangle)$.

---

## After $S$ and $\eta$

WDVV writes the $12$ BNN rooms as output.  
NNN pairing-axiom cells use the unit, not a dummy $6$ in $S$.  
Every unknown $X$ stays a symbol.

Locked ranks: $25$, $26$, $30$.  
Score: $180$ at $0$; $S$ OPEN.
