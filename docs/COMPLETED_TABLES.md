# Completed tables

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0

Source of the closed block: the evaluation screenshot.  
The garbled OCR row `|det A|5, 26, 30` is corrected to **25, 26, 30**.

## Table 1. Closed quantities

| quantity | value | why |
|---|---|---|
| off-rule cells | 180 of 216 are 0 | $k+\ell+m\not\equiv 1\pmod{6}$ $\Rightarrow$ empty $F$-spin stack $\Rightarrow$ domain empty |
| volume | $\int_X\omega^4=6$ | degree of a sextic in $\mathbb{P}^5$; one pairing on the Lefschetz line |
| $\mu(W)$ | 25 | LTs $v^6,u^5,u^4v$; monomials $4\cdot 6+1=25$ |
| $\mu(W^T)$ | 26 | LTs $u^4,uv^5,v^{11}$; $11+15=26$ |
| $\lvert\det A\rvert=\lvert\mathrm{Aut}(W)\rvert$ | 30 | $A=\begin{pmatrix}5&1\\0&6\end{pmatrix}$; $v^{11}\in(\partial W^T)$ |
| $\mu(F)$ | 15625 | $25^3$ Thom–Sebastiani |
| $\lvert\mathrm{Aut}(F)\rvert$ | 27000 | $30^3$ product of groups |
| Hilbert / state space | $(1,426,1751,426,1)$, $2610=2605+5$ | $J$-invariants of $\mathrm{Jac}(F)$; five narrow states |
| full $h^{2,2}$ | $1752=1751+1$ | extra $1$ is $\omega^2$, algebraic |
| $b_4$ | $2606=2605+1$ | same extra $1$ |
| $\mathrm{Jac}(W)$ residues | 42 triples in $\{1,-6\}$, Counter $\{1{:}38,\,-6{:}4\}$ | coeff of socle $u^3v^5$; algebra, not $[\overline{\mathcal{M}}]^{\mathrm{vir}}$ |

CSV: `tables/closed_quantities.csv`

## Table 2. The 36 allowed rooms

| kind | rooms | basis slots (size, not a correlator) | value |
|---|---:|---:|---|
| BBN / BNB / NBB | 3 | $3\cdot 2605^2=20\,358\,075$ | OPEN |
| BNN / NBN / NNB | 12 | $12\cdot 2605=31\,260$ | OPEN |
| NNN | 21 | 21 | OPEN; one pairing on the Lefschetz line is the volume 6 |

CSV: `tables/rooms_status.csv` and `tables/allowed_36.csv`

## NNN degree split (constraint, not a mixed fill)

If narrow states are identified with the Lefschetz line via Chiodo–Ruan ($J^k\leftrightarrow\omega^{k-1}$), the selection rule $k+\ell+m\equiv 1\pmod{6}$ splits the 21 NNN rooms into

- raw sum $7$ (degree-allowed candidates),
- raw sum $13$ (degree-forbidden on the line).

That is a constraint on which NNN decorations can be nonzero. It does **not** evaluate mixed BBN/BNN. It does **not** write $6$ into those mixed cells. Basalaev (arXiv:1610.07428): non-maximal groups can leave an overall scale unfixed if one uses axioms alone.

## What stays unwritten

Every mixed BBN/BNN number from

$$
\int_{\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}}
\bigl[\overline{\mathcal{M}}_{0,3}^{F,\langle J\rangle}\bigr]^{\mathrm{vir}}.
$$

Locked ranks stay $25$, $26$, $30$.
