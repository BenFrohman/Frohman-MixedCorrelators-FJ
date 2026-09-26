# The three seed rooms

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0

$$
S=\bigl\{
X_{001}(\alpha,\beta,\varphi_J),\;
X_{010}(\alpha,\varphi_J,\beta),\;
X_{100}(\varphi_J,\alpha,\beta)
\bigr\}
$$

These are the same integral on the same stack, with the three markings permuted.

$$
X_{k\ell m}(\alpha,\beta,\gamma)
=
\int_{\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}(J^k,J^\ell,J^m)}
\bigl[\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}(J^k,J^\ell,J^m)\bigr]^{\mathrm{vir}}.
$$

Decoration triples:

| symbol | $(k,\ell,m)$ | marks 1,2,3 | kind |
|---|---|---|---|
| $X_{001}$ | $(0,0,1)$ | broad, broad, $J^1$ | BBN |
| $X_{010}$ | $(0,1,0)$ | broad, $J^1$, broad | BNB |
| $X_{100}$ | $(1,0,0)$ | $J^1$, broad, broad | NBB |

Selection: $0+0+1=1\equiv 1\pmod{6}$. Stack nonempty. Not an empty-stack zero.

---

## What lives on the markings

Broad ($J^0=1$): a state $\alpha$ or $\beta$ in the $2605$-dimensional space $\mathrm{Jac}(F)^{\langle J\rangle}$, graded $(1,426,1751,426,1)$ in degrees $0,6,12,18,24$. This is where mixed-block tensors of $\mathrm{Jac}(W)^{\otimes 3}$ sit.

Narrow $J^1$: the one-dimensional Lefschetz state $\varphi_J$. Age of $J$ on $\mathbb{C}^6$ is $1$.

---

## Way 1 data (not a number)

Genus $0$, three marks: coarse moduli is a point. The number is the degree of the Polishchuk–Vaintrob / Witten class of six orbifold line bundles on that orbicurve.

$F=W\oplus W\oplus W$ with $W=u^5v+v^6$ gives three chain pairs:

$$
\begin{aligned}
L_{u_0}^{\otimes 5}\otimes L_{v_0}&\simeq\omega_{\log},&
L_{v_0}^{\otimes 6}&\simeq\omega_{\log},\\
L_{u_1}^{\otimes 5}\otimes L_{v_1}&\simeq\omega_{\log},&
L_{v_1}^{\otimes 6}&\simeq\omega_{\log},\\
L_{u_2}^{\otimes 5}\otimes L_{v_2}&\simeq\omega_{\log},&
L_{v_2}^{\otimes 6}&\simeq\omega_{\log}.
\end{aligned}
$$

Decorations $(0,0,1)$ assign monodromy $1,1,J$ at the three marks on every coordinate. Guéré's $t$-chain is two steps on *one* pair $(L_u,L_v)$. Here there are three pairs on the same curve. The class does not factor as a product of three one-chain integrals.

Index-zero / concave formulae that need all markings narrow do not apply: two markings are broad.

---

## What these rooms are not

- Not $0$ from an empty stack.
- Not $\int_X\omega^4=6$.
- Not a Jac$(W)$ residue in $\{1,-6\}$.
- Not a product of three Guéré integrals of $W$.
- Not Krawitz input ($G_{\max}$, order $27000$).

After a homogeneity cut, only those $(\alpha,\beta)$ with virtual dimension $0$ remain. Survivors are still symbols in $S$.

Evaluating $S$ is this Witten class on those three decoration triples. Until that class is computed, $S$ stays OPEN.

Locked ranks: $25$, $26$, $30$.
Score: $180$ closed at $0$; these three rooms generate the mixed side of the remaining $36$.
