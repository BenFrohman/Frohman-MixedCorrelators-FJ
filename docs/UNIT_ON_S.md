# Unit axiom on S

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0

Seed family, still OPEN except the unit slice below:

$$
S=\bigl\{
X_{001}(\alpha,\beta,\varphi_J),\;
X_{010}(\alpha,\varphi_J,\beta),\;
X_{100}(\varphi_J,\alpha,\beta)
\bigr\}.
$$

---

## Unit

The CohFT unit is the identity-sector vacuum

$$
\mathbf{1}\in\mathrm{Jac}(F)^{\langle J\rangle}_{\deg 0},
\qquad
\dim=1.
$$

That is the first slot of the Hilbert tuple $(1,426,1751,426,1)$.  
It is not the numeral $1$ written into a mixed cell. It is a state.

String / unit axiom of a CohFT:

$$
\langle\mathbf{1},\,\alpha,\,\beta\rangle_{0,3}=\eta(\alpha,\beta).
$$

---

## Unit slice of $X_{001}$

Put $\alpha=\mathbf{1}$:

$$
X_{001}(\mathbf{1},\beta,\varphi_J)=\eta(\beta,\varphi_J).
$$

The right-hand side is a two-point. It is nonzero only if $\beta$ is Poincare-dual to $\varphi_J$.

On the Lefschetz line, $\varphi_J$ is identified with $\omega$ (age $1$) and the dual of $\omega$ is $\omega^3$, which is narrow $J^4$, not a broad class. The pairing of a broad class against $\varphi_J$ is therefore $0$:

$$
\eta(\beta,\varphi_J)=0
\qquad\text{for every broad }\beta.
$$

Hence the unit slice closes:

$$
X_{001}(\mathbf{1},\beta,\varphi_J)=0,
\qquad
X_{001}(\alpha,\mathbf{1},\varphi_J)=0.
$$

Same for the two permutations $X_{010}$, $X_{100}$ when a broad insertion is $\mathbf{1}$.

This $0$ is the unit axiom plus sector pairing. It is not an empty-stack $0$, and it is not a dummy $6$.

---

## What stays OPEN

Every pair $(\alpha,\beta)$ in which *neither* broad insertion is the unit.  
Those are the mixed-block tensors that Way 1 still has to evaluate. They are $S$ minus the unit slice.

WDVV still needs that remainder. The unit slice does not determine it.

---

## Not closed by this pass

- $X_{001}(\alpha,\beta,\varphi_J)$ for $\alpha,\beta$ both non-unit in the $2605$
- any BNN room
- Hodge Term A or Term B

Locked ranks: $25$, $26$, $30$.  
Score: $180$ empty-stack zeros, plus the unit slice of $S$ at $0$ by $\eta$. The remainder of $S$ is OPEN.
