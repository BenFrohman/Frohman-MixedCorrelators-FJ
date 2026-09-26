# Frohman findings, theorems, and methods

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0

This file documents what this lab has closed, what it has named, and what it has not computed.  
Citations mark prior theorems. Unmarked statements are lab bookkeeping or the Frohman problem itself.

Locked ranks stay $25$, $26$, $30$.  
Score stays: $180$ closed at $0$; the $36$ allowed rooms are the Frohman problem.

---

## A. Closed in this lab

### A1. Empty-stack vanishing (Frohman, selection lemma)

**Statement.** Let $F=W\oplus W\oplus W$ with $W=u^5v+v^6$ and $J$ the diagonal sixth-root action on $\mathbb{C}^6$. For genus zero and three marks, if

$$
k+\ell+m\not\equiv 1\pmod{6},
$$

then $\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}$ with those decorations is empty, and

$$
\langle\alpha,\beta,\gamma\rangle_{0,3}^{F,\langle J\rangle}=0
$$

because the domain is empty.

**Status.** Closed. $180$ of $216$ ordered triples.  
**Not.** Vanishing of an allowed mixed triple.

### A2. Locked atom ranks (Frohman bookkeeping of a known chain)

$$
\mu(W)=25,\qquad \mu(W^T)=26,\qquad \lvert\det A\rvert=\lvert\mathrm{Aut}(W)\rvert=30.
$$

Leading terms: $W$ has $v^6,u^5,u^4v$; $W^T$ has $u^4,uv^5,v^{11}$.  
Membership: $v^{11}=v^5(5u^4+v^6)-5u^3(uv^5)\in(\partial W^T)$.  
Cubes: $\mu(F)=25^3=15625$, $\lvert\mathrm{Aut}(F)\rvert=30^3=27000$.

**Status.** Closed.  
**Prior.** Milnor–Orlik weighted formula; Berglund–Hübsch transpose.  
**Not.** A Hodge miss. Not $\lvert\det A\rvert=\mu$.

### A3. Hilbert match (lab check of Griffiths)

$J$-invariants of $\mathrm{Jac}(F)$ are graded $(1,426,1751,426,1)$ in degrees $0,6,12,18,24$, sum $2605$.  
State space $2610=2605+5$. Full $h^{2,2}=1752=1751+1$, $b_4=2606=2605+1$.

**Status.** Closed as a dimension match.  
**Prior.** Griffiths residue calculus for a smooth sextic in $\mathbb{P}^5$ (1968–69); Chiodo–Ruan LG/CY for the vector-space identification.  
**Not.** A table of mixed three-points.

### A4. One-block residue table

$42$ unordered triples of $\mathrm{Jac}(W)$ against the socle $u^3v^5$, values in $\{1,-6\}$, Counter $\{1{:}38,\,-6{:}4\}$.  
On pure tensors, $\mathrm{Jac}(F)\simeq\mathrm{Jac}(W)^{\otimes 3}$ multiplies those residues.

**Status.** Closed as algebra.  
**Not.** $[\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}]^{\mathrm{vir}}$.

### A5. BBB excluded by selection

The only three-broad decoration is $(0,0,0)$. It fails $k+\ell+m\equiv 1\pmod{6}$. Three identity-sector insertions are one of the $180$ zeros.

**Status.** Closed.

---

## B. Named methods (Frohman), not evaluations

### B1. The Frohman problem

**Problem (Frohman, mixed correlators of a three-block chain sum).**  
Compute every genus-zero primary three-point

$$
\langle\alpha,\beta,\gamma\rangle_{0,3}^{F,\langle J\rangle}
=
\int_{\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}}
\bigl[\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}\bigr]^{\mathrm{vir}}
$$

on the $2610$-dimensional state space, including mixed broad–narrow and mixed-block tensors, subject to decorations multiplying to $J$. Show these numbers are not a product of three Guéré integrals of $W$. Produce the table, or prove vanishing, for every allowed triple.

**Status.** Named. $36$ rooms OPEN.  
File: `TEXTBOOK.md`.

### B2. Seed method (Frohman)

Minimal mixed seeds from the virtual class:

$$
S=\bigl\{X_{001}(\alpha,\beta,\varphi_J),\;X_{010}(\alpha,\varphi_J,\beta),\;X_{100}(\varphi_J,\alpha,\beta)\bigr\}.
$$

WDVV plus $\eta$ would write the $12$ BNN rooms after $S$ is known.  
**Status.** Named as symbols. Not evaluated.  
File: `docs/SEEDS.md`.

### B3. Two-zero method (Frohman)

Distinguish empty-stack $0$ (off-rule, domain empty) from a possible virtual-class $0$ on an allowed room. The second $0$ has not been proved for mixed BBN/BNN.

**Status.** Method named. First zero closed ($180$). Second zero not written into mixed cells.

### B4. Homogeneity cut (Frohman method)

Grade the $2605$ as $(1,426,1751,426,1)$. Keep only degree triples with virtual dimension $0$. Survivors stay OPEN symbols.  
**Status.** Method named. Counts not yet enumerated in a kernel-checked file.

---

## C. Prior theorems used, not claimed as Frohman

| result | who | what it does here | what it does not |
|---|---|---|---|
| FJRW CohFT | Fan–Jarvis–Ruan | defines the integral | evaluate $S$ |
| chain Hodge integrals | Guéré, arXiv:1509.07047 | one chain $W$, any $G$ | run on $F=W\oplus W\oplus W$ |
| chain quantum ring | Fan–Shen | $(X^p+XY^q)$ vs dual Jacobian; here $(5,6)$, $\gcd(4,6)=2$ | mixed $F$-vir table |
| reconstruction | Krawitz | written for $G_{\max}$ | $\langle J\rangle$ of order $6$ |
| non-maximal scale | Basalaev, arXiv:1610.07428 | axioms may leave a scale unfixed | pin $S$ |
| LG/CY state spaces | Chiodo–Ruan | $2610=2605+5=\dim H^\bullet(X)$ | mixed three-points |
| residue calculus | Griffiths 1968–69 | diamond $(1,426,1751,426,1)$ | a miss class |
| BHK transpose | Berglund–Hübsch | $W\leftrightarrow W^T$, $\lvert\mathrm{Aut}\rvert$ kept | a Fourier–Mukai fourfold $Y$ |
| Milnor number | Milnor; Milnor–Orlik | $\mu=(d/p-1)$ product | $\lvert\det A\rvert$ |

---

## D. Explicitly not proved

- Any mixed BBN/BNN number $X_{001},X_{010},X_{100}$ from the virtual class
- A product formula for correlators of $F$ in terms of Guéré integrals of $W$
- A reconstruction theorem for $\langle J\rangle$ with numerical seeds
- Rational Hodge Term A or Term B
- A fourfold partner $Y\not\simeq V(F)$ with Fourier–Mukai kernel

Writing $0$, $1$, $6$, or $1/6$ into a mixed cell is not a Frohman theorem.

---

## E. Files

| claim | file |
|---|---|
| textbook problem | `TEXTBOOK.md` |
| evaluation score | `docs/SCORE.md`, `docs/EVALUATION.md` |
| $36$ rooms | `docs/THIRTY_SIX.md` |
| seeds | `docs/SEEDS.md` |
| next steps | `docs/NEXT_STEPS.md` |
| closed quantities | `tables/closed_quantities.csv` |
| this ledger | `docs/FROHMAN_THEOREMS.md` |
