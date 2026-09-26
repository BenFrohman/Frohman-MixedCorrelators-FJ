# Seeds

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0

Locked ranks: $25$, $26$, $30$.  
Score: $180$ closed at $0$; the $36$ are the Frohman problem.

A seed is a three-point that must be supplied from geometry before WDVV can write the rest.  
A seed is not a numeral written into an OPEN cell.

Write

$$
X_{k\ell m}(\alpha,\beta,\gamma)
:=
\langle\alpha,\beta,\gamma\rangle_{0,3}^{F,\langle J\rangle}
=
\int_{\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}}
\bigl[\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}\bigr]^{\mathrm{vir}}
$$

for a decoration $(k,\ell,m)$ that passes $k+\ell+m\equiv 1\pmod{6}$.

---

## Already numbers (not mixed seeds)

| symbol | value | role |
|---|---|---|
| empty-stack $X_{k\ell m}$ off-rule | $0$ | $180$ cells |
| $\eta(\omega^i,\omega^{4-i})$ | includes $\int_X\omega^4=6$ | metric on the Lefschetz line |
| $\eta$ on the $2605$ | residue pairing of $\mathrm{Jac}(F)^{\langle J\rangle}$ | B-model metric |
| $42$ triples of $\mathrm{Jac}(W)$ | $\{1,-6\}$ | algebra of one block; wrong input for $X_{k\ell m}$ |

These do not evaluate a mixed BBN or BNN room.

---

## Minimal mixed seed list $S$

The smallest family that has to come from the virtual class is the BBN room and its two permutations.

$$
S
=
\bigl\{
X_{001}(\alpha,\beta,\varphi_{J}),\;
X_{010}(\alpha,\varphi_{J},\beta),\;
X_{100}(\varphi_{J},\alpha,\beta)
\bigr\}
$$

where $\alpha,\beta$ run over the $2605$-dimensional broad space and $\varphi_{J}$ is the narrow state of sector $J^1$.

After the homogeneity cut of Step 3, only those $(\alpha,\beta)$ with virtual dimension $0$ remain. That is still a list of *symbols*. It is not $0$, $1$, $6$, or $1/6$.

Why this family is the seed, not BNN:

- Two broad insertions are the first place mixed-block tensors appear.
- The third insertion is the lowest nontrivial narrow state $J^1$.
- WDVV with the metric $\eta$ contracts one broad leg against the $2605$ and produces BNN three-points as outputs.

Krawitz would take $G_{\max}$ and a different seed list. Basalaev (arXiv:1610.07428): for a non-maximal group the axioms can leave an overall scale unfixed. So even after $S$ is known up to scale, one extra Way-1 evaluation may be required to pin the scale. That extra evaluation is still an element of $S$, not a Jac($W$) residue.

---

## What WDVV would then write

Once $S$ and $\eta$ are known:

| family | rooms | status after seeds |
|---|---:|---|
| BBN / BNB / NBB | $3$ | input $S$ |
| BNN / NBN / NNB | $12$ | output of WDVV $+$ $\eta$ $+$ $S$ |
| NNN sum $7$ | $15$ | pairing axiom $+$ unit check; leftovers OPEN until $S$ or Way 1 |
| NNN sum $13$ | $6$ | constraint $0$ if $J^k\mapsto\omega^{k-1}$ is cited |

Schematic identity, no fills:

$$
\sum_{\varepsilon,\varepsilon'}
X_{k\ell r}(\alpha,\beta,\varepsilon)\,\eta^{\varepsilon\varepsilon'}\,X_{r'mn}(\varepsilon',\gamma,\delta)
=
\sum_{\varepsilon,\varepsilon'}
X_{\ell m r}(\beta,\gamma,\varepsilon)\,\eta^{\varepsilon\varepsilon'}\,X_{r'kn}(\varepsilon',\alpha,\delta).
$$

Every unknown $X$ stays a symbol.

---

## Wrong seeds (do not use)

- A product of three Guéré integrals of $W$
- A product of three $\mathrm{Jac}(W)$ residues, except as a comparison on *pure tensors of the algebra*
- $\mathrm{cl}=0$ on $\mathrm{Rat}$
- $0$, $1$, $6$, $1/6$ written into $X_{001}$

---

## What “grind seeds” has produced

The seed list is named. It is not evaluated.  
Evaluating $S$ is Way 1 on the three rooms $(0,0,1)$, $(0,1,0)$, $(1,0,0)$.  
That is the next geometric computation, not a numeral.
