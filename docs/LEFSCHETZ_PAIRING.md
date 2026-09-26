# Lefschetz pairing

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0

Host: $X=V(F)\subset\mathbb{P}^5$, smooth sextic fourfold, $\deg X=6$.  
Kaehler class $\omega=c_1(\mathcal{O}_X(1))$, the hyperplane class.

---

## Classical pairing

Poincare duality on a compact oriented $8$-real-manifold:

$$
H^{k}(X,\mathbb{Q})\times H^{8-k}(X,\mathbb{Q})\longrightarrow\mathbb{Q},
\qquad
(\alpha,\beta)\longmapsto\int_X\alpha\cup\beta.
$$

Hard Lefschetz says $L^{4-m}:H^m(X)\xrightarrow{\sim}H^{8-m}(X)$ with $L(\alpha)=\omega\cup\alpha$.  
The Lefschetz line is the span of powers of $\omega$:

$$
\mathbb{Q}\langle 1,\;\omega,\;\omega^2,\;\omega^3,\;\omega^4\rangle
\subset
H^0\oplus H^2\oplus H^4\oplus H^6\oplus H^8.
$$

On that line the pairing is completely determined by one integer, the volume:

$$
\int_X\omega^4=\deg(X)=6.
$$

So

$$
\bigl(\omega^i,\omega^{4-i}\bigr)=\int_X\omega^4=6
\qquad(i=0,1,2,3,4).
$$

Explicit matrix, ordered $(1,\omega,\omega^2,\omega^3,\omega^4)$:

$$
\eta_{\mathrm{Lef}}
=
\begin{pmatrix}
0&0&0&0&6\\
0&0&0&6&0\\
0&0&6&0&0\\
0&6&0&0&0\\
6&0&0&0&0
\end{pmatrix}.
$$

Off-diagonal zeros: $\int_X\omega^i\cup\omega^j=0$ unless $i+j=4$.

That $6$ is a two-point number. It is the metric $\eta$ on the five narrow FJRW states once those states are identified with the Lefschetz line.

---

## Primitive pairing is different

Middle cohomology splits

$$
H^4(X,\mathbb{C})\simeq P^4\oplus L P^2\oplus L^2 P^0.
$$

$L^2 P^0=\mathbb{C}\omega^2$. The Hodge-Riemann form on the primitive summand $P^4$ is

$$
(\alpha,\beta)_{\mathrm{HR}}=\int_X\alpha\cup\beta,
$$

restricted to primitives, not the same pairing as $\eta_{\mathrm{Lef}}$ on the line.  
Full $h^{2,2}=1752=1751+1$: the extra $1$ is $\omega^2$, already algebraic, and it is the middle vector of $\eta_{\mathrm{Lef}}$.

---

## What this pairing is not

- Not $X_{001}(\alpha,\beta,\varphi_J)$. That is a three-point on two broad states and $J^1$.
- Not a Jac$(W)$ residue.
- Not permission to write $6$ into a BBN or BNN cell.
- Not Term B of Hodge. $\omega^2$ hits $\mathrm{im}(\mathrm{cl}_X)$.

In the seed list this pairing is structure: it contracts legs in WDVV. It does not evaluate $S$.

Locked ranks: $25$, $26$, $30$.
