# The remaining 36 rooms

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0

The object on every allowed decoration triple:

$$
\langle\alpha,\beta,\gamma\rangle_{0,3}^{F,\langle J\rangle}
=
\int_{\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}}
\bigl[\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}\bigr]^{\mathrm{vir}}.
$$

Selection rule: $k+\ell+m\equiv 1\pmod{6}$.  
$k=0$ is the broad sector (dim $2605$).  
$k=1,\ldots,5$ are narrow Lefschetz states (dim $1$ each).

BBB is missing on purpose. The only three-broad decoration is $(0,0,0)$, and $0\not\equiv 1\pmod{6}$. Three identity-sector insertions have an empty $F$-spin stack. That is one of the $180$ zeros, not an OPEN mixed room.

---

## Census of the 36

| kind | count | raw sums that occur | slots per room |
|---|---:|---|---:|
| BBN / BNB / NBB | 3 | $1$ | $2605^2=6\,786\,025$ |
| BNN / NBN / NNB | 12 | $7$ | $2605$ |
| NNN | 21 | $7$ (fifteen rooms) or $13$ (six rooms) | $1$ |

### The three two-broad rooms (BBN family)

| $k,\ell,m$ | kind | sum | status |
|---|---|---:|---|
| $(0,0,1)$ | BBN | 1 | OPEN |
| $(0,1,0)$ | BNB | 1 | OPEN |
| $(1,0,0)$ | NBB | 1 | OPEN |

Two markings carry a broad state from $\mathrm{Jac}(F)^{\langle J\rangle}$. The third marking is the narrow state $J^1$.  
A broad state may be a pure tensor $a\otimes b\otimes c\in\mathrm{Jac}(W)^{\otimes 3}$ or a mixed-block vector. Those mixed-block slots are the core of the Frohman problem. They are not a product of three Guéré integrals of $W$.

### The twelve one-broad rooms (BNN family)

| $k,\ell,m$ | kind | sum | status |
|---|---|---:|---|
| $(0,2,5)$ | BNN | 7 | OPEN |
| $(0,3,4)$ | BNN | 7 | OPEN |
| $(0,4,3)$ | BNN | 7 | OPEN |
| $(0,5,2)$ | BNN | 7 | OPEN |
| $(2,0,5)$ | NBN | 7 | OPEN |
| $(3,0,4)$ | NBN | 7 | OPEN |
| $(4,0,3)$ | NBN | 7 | OPEN |
| $(5,0,2)$ | NBN | 7 | OPEN |
| $(2,5,0)$ | NNB | 7 | OPEN |
| $(3,4,0)$ | NNB | 7 | OPEN |
| $(4,3,0)$ | NNB | 7 | OPEN |
| $(5,2,0)$ | NNB | 7 | OPEN |

One broad insertion from the $2605$-space, two narrow Lefschetz states. Mixed means the broad insertion is not a pure tensor of a single block, or the two narrow states sit on different geometric axes than a product formula would require. Still OPEN.

### The twenty-one NNN rooms

Sum $7$ (fifteen rooms):  
$(1,1,5),\ (1,2,4),\ (1,3,3),\ (1,4,2),\ (1,5,1)$,  
$(2,1,4),\ (2,2,3),\ (2,3,2),\ (2,4,1)$,  
$(3,1,3),\ (3,2,2),\ (3,3,1)$,  
$(4,1,2),\ (4,2,1)$,  
$(5,1,1)$.

Sum $13$ (six rooms):  
$(3,5,5),\ (4,4,5),\ (4,5,4),\ (5,3,5),\ (5,4,4),\ (5,5,3)$.

If narrow states are identified with the Lefschetz line $J^k\leftrightarrow\omega^{k-1}$ via Chiodo–Ruan, the sum-$13$ decorations are degree-forbidden on that line and the sum-$7$ decorations are the only NNN candidates that can pair. That is a constraint. The pairing axiom supplies one number on the line, the volume $\int_X\omega^4=6$. It does not fill the other twenty NNN cells by decree, and it does not touch BBN/BNN. Basalaev (arXiv:1610.07428): axioms for a non-maximal group can leave a scale unfixed.

---

## What cuts a room without evaluating it

1. **Selection rule.** Already used. Builds the $36$ and kills the $180$.
2. **Homogeneity inside a room.** A broad insertion has a Jacobian degree in $\{0,6,12,18,24\}$. The FJRW degree of a narrow state is its age. Only some degree triples can have virtual dimension zero. That thins $2605^2$ and $2605$, and does not compute the survivors.
3. **Primitive versus Lefschetz.** Broad $J$-invariants include the primitive diamond $(1,426,1751,426,1)$. Pairing a primitive class against two Lefschetz powers can vanish by Lefschetz orthogonality. Vanishing of *some* slots is not vanishing of every mixed triple.
4. **WDVV.** Associativity writes linear relations among three-points once a few seeds exist. Seeds must come from the virtual class on $F$-spin moduli. WDVV does not invent them. Residues of $\mathrm{Jac}(W)$ and three Guéré integrals of $W$ are the wrong seeds.

---

## What would actually solve a room

**Way 1.** Evaluate the virtual class on that decoration. For genus zero and three marks the coarse moduli is a point, so the number is the degree of Witten's top Chern class (or the Polishchuk–Vaintrob class) of the six-variable spin bundle with those decorations. Guéré writes that class for *one* chain. $F$ is three disjoint chains. The formula does not factor.

**Way 2.** Prove a reconstruction theorem for $\langle J\rangle$ (order $6$), not $G_{\max}$ (order $27000$). Produce a finite seed list $S$ of Way-1 integrals. WDVV plus the pairing plus the selection rule then write the rest of genus zero.

Neither way is supplied in this file.

---

## What is not a solution

- Writing $0$, $1$, $6$, or $1/6$ into a BBN or BNN cell.
- Multiplying three Guéré integrals of $W$.
- Multiplying three $\mathrm{Jac}(W)$ residues and calling the product an $F$-vir number. That product is an algebra identity on pure tensors, already recorded.
- Importing a Gromov–Witten three-point of $X=V(F)$ from Klemm–Pandharipande. Different moduli stack.

Locked ranks stay $25$, $26$, $30$.  
Score stays: $180$ cells closed at $0$; these $36$ rooms are the Frohman problem.
