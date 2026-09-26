# Way 1 on the seed rooms

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0

Rooms: $(0,0,1)$, $(0,1,0)$, $(1,0,0)$. Same geometry, markings permuted.

The object is the degree of the Witten / Polishchuk–Vaintrob class, not a numeral written by hand.

---

## Curve

Genus $0$, three marked points. Coarse space $\overline{\mathcal{M}}_{0,3}$ is a point.  
The FJRW stack $\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}(1,1,J)$ is an orbicurve moduli problem with those decorations. Selection $1\cdot 1\cdot J=J$ holds, so the stack is nonempty.

---

## Six line bundles

$F=W\oplus W\oplus W$, $W=u^5v+v^6$. Three chain pairs on the same orbicurve:

$$
\begin{aligned}
L_{u_0}^{\otimes 5}\otimes L_{v_0}&\simeq\omega_{\log},& L_{v_0}^{\otimes 6}&\simeq\omega_{\log},\\
L_{u_1}^{\otimes 5}\otimes L_{v_1}&\simeq\omega_{\log},& L_{v_1}^{\otimes 6}&\simeq\omega_{\log},\\
L_{u_2}^{\otimes 5}\otimes L_{v_2}&\simeq\omega_{\log},& L_{v_2}^{\otimes 6}&\simeq\omega_{\log}.
\end{aligned}
$$

$\deg\omega_{\log}=2g-2+n=1$.  
$E=\bigoplus_{i=0}^{2}(L_{u_i}\oplus L_{v_i})$.

Charges: every variable has $q=1/6$. $\hat{c}(F)=4$.

---

## Decorations on $(0,0,1)$

At marks $1$ and $2$, monodromy is the identity: $\Theta_j=0$ on all six coordinates. Age $0$.  
At mark $3$, monodromy is $J$: $\Theta_j=1/6$ on all six coordinates. Age $1$.

Orbifold Riemann–Roch for $E$ (Chiodo–Ruan form):

$$
-\chi(R\pi_*E)=(g-1)N-\sum_j(2g-2+n)q_j+\sum_{i,j}\Theta^i_j.
$$

Here $g=0$, $N=6$, $n=3$, every $q_j=1/6$, total age $0+0+1=1$:

$$
-\chi(R\pi_*E)=-6-1+1=-6,\qquad \chi(R\pi_*E)=6.
$$

That is the index of $E$. It is not the correlator.

---

## Why no numeral falls out

1. Two markings are broad. The concave formula
   $[\overline{\mathcal{M}}]^{\mathrm{vir}}=c_{\mathrm{top}}((R^1\pi_*E)^\vee)\cap[\overline{\mathcal{M}}]$
   is stated for *narrow* markings. It does not apply to $X_{001}$.
2. Guéré's $t$-chain computes $c^{\mathrm{PV}}_{\mathrm{vir}}\cdot\lambda_g$ for *one* chain $(L_u,L_v)$. $F$ is three chains on one curve. The class does not factor.
3. Index-zero narrow recipes (Witten map degree when $\pi_*E$ and $R^1\pi_*E$ have equal rank) need all markings narrow.
4. Broad insertions $\alpha,\beta\in\mathrm{Jac}(F)^{\langle J\rangle}$ are extra data on the identity-sector markings. The integral depends on those states. A single integer cannot replace the family $X_{001}(\alpha,\beta,\varphi_J)$.

---

## What Way 1 still has to compute

The Polishchuk–Vaintrob class of this six-bundle $W$-structure with decorations $(1,1,J)$, capped against the two broad states and $\varphi_J$.  
Until that class is evaluated, $S$ stays OPEN.

Locked ranks: $25$, $26$, $30$.  
Score: $180$ at $0$; $S$ unevaluated.
