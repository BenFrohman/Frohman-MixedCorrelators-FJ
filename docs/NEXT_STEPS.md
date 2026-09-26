# Next steps to resolve the 36 rooms

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0

Locked: $\mu(W)=25$, $\mu(W^T)=26$, $\lvert\det A\rvert=30$.  
Closed: $180$ empty-stack zeros.  
Constraint: NNN raw sum $7$ versus $13$.  
Still OPEN: mixed BBN/BNN virtual-class numbers.

These five steps are the grind. They do not write $0$, $1$, $6$, or $1/6$ into a mixed cell.

---

## Step 1. Lock the NNN degree split as a lemma, not a fill

Identify $J^k\leftrightarrow\omega^{k-1}$ only after citing the Chiodo–Ruan bidegree map for this $(F,\langle J\rangle)$.

Then the $21$ NNN rooms split:

- raw sum $7$: fifteen rooms, Lefschetz-line candidates
- raw sum $13$: six rooms, degree-forbidden on that line

If the identification holds, the six sum-$13$ rooms are $0$ by degree, not by empty stack.  
That would close $6$ of $36$ without touching BBN/BNN.  
Until the identification is cited for this host, those six stay marked CONSTRAINT, not CLOSED.

Deliverable: one lemma with the age/degree formula written out, or a citation that the map $J^k\mapsto\omega^{k-1}$ is an isometry of state spaces for a degree-$6$ hypersurface in $\mathbb{P}^5$ with group $\langle J\rangle$.

---

## Step 2. Name the pairing-axiom NNN cells

The pairing axiom of Fan–Jarvis–Ruan supplies two-point numbers on dual narrow sectors. The volume $\int_X\omega^4=6$ is one pairing on the Lefschetz line.

A genus-zero three-point on $\overline{\mathcal{M}}_{0,3}$ (a point) becomes that pairing only when one insertion is the CohFT unit. Which of the fifteen sum-$7$ rooms has a unit insertion is a named check, not a blanket $6$.

Deliverable: a $15$-row table

`room | contains unit? | pairing-axiom value or OPEN`

No row may copy $6$ unless the unit identification is written.

---

## Step 3. Cut BBN/BNN by homogeneity, leave survivors OPEN

Broad $J$-invariants are graded $(1,426,1751,426,1)$ in degrees $0,6,12,18,24$.  
Narrow $J^k$ has age $k$.

Virtual dimension of a primary three-point must vanish. That kills most of the $6\,786\,025$ and $2\,605$ slots inside each room. The surviving slots are still OPEN numbers. The cut is a smaller OPEN list, not a fill.

Deliverable: for each of the $15$ mixed rooms, the list of degree triples $(d_{\mathrm{broad}},\mathrm{ages})$ with $\mathrm{vdim}=0$. Counts only. No correlator values.

---

## Step 4. Write the WDVV skeleton on the $36$

WDVV is associativity of the quantum product on the $2610$-space. On decorations it relates a BBN three-point to a sum of BNN three-points (and NNN) once the metric is known.

Shape, not numbers:

$$
\sum_{\varepsilon,\varepsilon'}\langle\alpha,\beta,\varepsilon\rangle\,\eta^{\varepsilon\varepsilon'}\,\langle\varepsilon',\gamma,\delta\rangle
=
\sum_{\varepsilon,\varepsilon'}\langle\beta,\gamma,\varepsilon\rangle\,\eta^{\varepsilon\varepsilon'}\,\langle\varepsilon',\alpha,\delta\rangle.
$$

The metric $\eta$ on the Lefschetz line includes the volume $6$. The metric on the $2605$ is the residue pairing of $\mathrm{Jac}(F)^{\langle J\rangle}$, already an algebra.

Deliverable: the list of independent WDVV equations that mix BBN with BNN. Mark every unknown three-point as a symbol $X_{k\ell m}(\alpha,\beta,\gamma)$, never as $0,1,6$.

Seeds required before the system determines the rest: at least one mixed BBN (or BNN) family from the virtual class. Residues of $\mathrm{Jac}(W)$ are the wrong seeds. Three Guéré integrals of $W$ are the wrong seeds. Krawitz is $G_{\max}$. Basalaev: $\langle J\rangle$ can leave a scale unfixed.

---

## Step 5. Name the actual computer object for Way 1

Genus zero, three marks: coarse moduli is a point. The number is the degree of Witten's top Chern class (Polishchuk–Vaintrob class) of the spin bundle

$$
L_0^{\otimes 5}\otimes L_3 \simeq \omega_{\log},\quad L_3^{\otimes 6}\simeq\omega_{\log}
$$
and the two sibling pairs for blocks $1$ and $2$, with decorations $(k,\ell,m)$.

Guéré's $t$-chain is two steps on one pair $(L_u,L_v)$. $F$ needs three such chains on the same curve. That package is not implemented in this lab and is not a product of three one-chain integrals.

Deliverable: a specification of the six line bundles and the three decorations, ready for an algebraic-geometry computation, with no numerical output claimed.

---

## Order

1 $\to$ 2 can close up to six NNN rooms and name the pairing cells.  
3 shrinks the mixed rooms.  
4 writes the system.  
5 is the evaluation.  
Nothing in 1–4 is permission to fill BBN/BNN.

Score unchanged until a room is closed by a lemma or a virtual-class number: $180$ at $0$, $36$ the Frohman problem.
