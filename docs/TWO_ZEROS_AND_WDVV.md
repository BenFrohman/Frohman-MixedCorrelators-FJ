# Two different zeros. Locked integers. Mixed WDVV — equations, not fills

Author: Benjamin Stanley Frohman  
Copyright (c) 2026 Benjamin Stanley Frohman  
License: Apache-2.0

Companion tables: `tables/all_216_decoration_triples.csv` (216 = 36 + 180),
`tables/allowed_36.csv`, `docs/ALL_216.md`.

## 1. Off-rule vanishing is not allowed-triple vanishing

The stack of `(F, ⟨J⟩)`-spin curves with decorations `(γ₁, γ₂, γ₃)` is empty unless

    γ₁ γ₂ γ₃ = J^{2g-2+n}.

Genus zero, three marks: `γ₁ γ₂ γ₃ = J`. If decorations are `J^k, J^ℓ, J^m`, that is

    k + ℓ + m ≡ 1 (mod 6).

Empty stack implies the integral is zero. That is off-rule vanishing. It is real. It is cheap. It does not look at the virtual class. It only asks whether the moduli space exists.

There are `6³ = 216` ordered decoration triples. Exactly `36` pass. The other `180` are this cheap zero. They are written in `tables/all_216_decoration_triples.csv` (column `selection=EXCLUDED`). The first of them is `(0,0,0)` BBB: three identity decorations, sum `0 ≢ 1`.

An **allowed** triple is one that passes the test. The stack is then a copy of `B⟨J⟩` (genus-zero three-pointed F-spin curves with those monodromies). The correlator is

    ⟨α, β, γ⟩_{0,3}^{F,⟨J⟩}
    = ∫_{[M-bar_{0,3}^{F,⟨J⟩}(J^k, J^ℓ, J^m)]^{vir}}.

That integral can still be zero. Reasons that are not the selection rule:

1. **Homogeneity.** Primary genus-zero three-points vanish unless `∑_i deg α_i = ĉ(F) = 4`. A triple can satisfy `k+ℓ+m ≡ 1 (mod 6)` and still have the wrong weighted degree. Then the virtual class lives in the wrong degree and the number is zero. That is a second filter, not the first.
2. **Line-bundle integrality.** Each spin bundle `L_j` must have integer degree after desingularization. Fail that and the component is empty for a different reason.
3. **The integral itself.** Stack nonempty, degrees match, and the virtual class can still integrate to zero. Concavity, index-zero, or an actual computation is what decides that. None of those has been run on mixed BBN/BNN insertions of this F.

So: "0 off the selection rule" is a statement about **which rooms exist**. "Every allowed mixed triple is 0" is a statement about **the virtual class in the rooms that exist**. The second is not the first. Writing 0 in every BBN/BNN cell is inventing the second from the first.

The slot counts `20,358,075` and `31,260` are how many basis triples sit in rooms that exist after the group-product test only. Homogeneity cuts that list further. What remains is still OPEN as numbers.

## 2. So what are the locked integers?

They are ranks, Betti numbers, and one volume. They are not structure constants of the A-model on F-spin moduli.

| Integer | Name | What it is, in one sentence |
|---|---|---|
| 25 | μ(W) | Dimension of C[u,v]/(∂W). Also b_1 of the Milnor fibre of the plane-curve germ (a bouquet of 25 circles). |
| 26 | μ(W^T) | Same for the transpose germ. The extra monomial is v^{11} ∈ (∂W^T). |
| 30 | |det A| = |Aut(W)| | Order of the maximal diagonal symmetry group. Preserved by BHK transpose. Not μ. |
| 15625 = 25^3 | dim Jac(F) | Thom–Sebastiani: three copies of the Jacobian algebra. |
| 27000 = 30^3 | |Aut(F)| | Product of the three symmetry groups. |
| (1, 426, 1751, 426, 1) | Hilbert of Jac(F)^J | Graded pieces of the J-invariants, degrees 0,6,12,18,24. Classical primitive Hodge numbers of any smooth sextic in P^5 (Griffiths 1968–69). |
| 2605 | dim Jac(F)^J | 1+426+1751+426+1. The ordinary room. |
| 1752 = 1751+1 | h^{2,2}(X) | Primitive piece plus ω^2. |
| 2606 = 2605+1 | b_4(X) | Same extra 1. |
| 5 | narrow line | Fixed loci of J,J^2,J^3,J^4,J^5 are the origin. One Lefschetz state each: 1, ω, ω^2, ω^3, ω^4. |
| 2610 = 2605+5 | dim H_{F,⟨J⟩} | Both rooms. Equals dim H^\u2022(X). |
| 6 = ∫_X ω^4 | degree | Volume of a sextic in P^5. One pairing on the narrow line. |
| {1, -6} | 42 residue triples | Structure constants of Jac(W) against the socle u^3 v^5. |

Matching the diamond on this three-chain Jacobian says: the B-model vector space of this special sextic has the same dimension, grade by grade, as the B-model of a general one. Hodge numbers are constant in the smooth locus, so that match was expected. It does not compute ⟨α, β, γ⟩_{0,3}^{F,⟨J⟩}.

## 3. Mixed WDVV reconstruction — the machine, not the table

WDVV is associativity of the quantum product on H_{F,⟨J⟩}:

    ⟨α ⋆ β, γ ⋆ δ⟩ = ⟨α ⋆ γ, β ⋆ δ⟩,
    ⟨φ_i ⋆ φ_j, φ_k⟩ = ⟨φ_i, φ_j, φ_k⟩_{0,3}^{F,⟨J⟩}(t).

With the pairing η_{ij} = ⟨φ_i, φ_j⟩ (two-point, genus zero) you raise indices and get a system on the unknown three-points. String and dilaton cut descendants. That is the reconstruction machine. It needs seeds. It does not invent them.

### What is already a seed

- Pairing on the narrow Lefschetz line, including ⟨ω^2, ω^2⟩ ~ ∫_X ω^4 = 6.
- Identity-sector three-points of Jac(F). Thom–Sebastiani is an algebra isomorphism Jac(F) ≅ Jac(W)^{\u2297 3}, so even mixed-block **residue** three-points factor:

      ⟨ a1⊗a2⊗a3, b1⊗b2⊗b3, c1⊗c2⊗c3 ⟩_{Jac(F)}
      = ∏_{k=1}^3 ⟨a_k, b_k, c_k⟩_W.

Each block factor is a coefficient of u^3 v^5 in {1, -6}. That is the 42-row CSV. It is the B-model identity sector, not the virtual class on mixed decorations.

### What is not a seed

- BBN: two broad states, one narrow state e_{J^k}.
- BNN: one broad, two narrow.
- Any three-point whose decorations pass the selection rule and whose insertions mix the 2605-room with the Lefschetz line.

Krawitz reconstruction identifies the FJRW ring with a Milnor / orbifold Milnor ring for G_max. This group is ⟨J⟩, not G_max. For ⟨J⟩ the theory is in general not generically semisimple; Teleman reconstruction does not apply, and the FJRW axioms alone reconstruct genus zero only up to scaling. Guéré computes λ_g ∪ c^{PV}_{vir} on **one chain**, any G. F is three disjoint chains. There is no product formula that turns three Guéré integrals into a mixed F three-point.

### The linear system that would produce the mixed table

Write B for a homogeneous basis of the 2605-dimensional identity sector and N_k = e_{J^k} for the five narrow states, k = 1,...,5.

Allowed decoration types with k+ℓ+m ≡ 1 (mod 6):

| Kind | Decorations | Unknowns | Seed? |
|---|---|---|---|
| three identity | 0+0+0 ≢ 1 | none on F-spin moduli | EXCLUDED by selection. Lives in Jac(F), not on M-bar_{0,3}^{F,⟨J⟩}. |
| BBN | two broad (deco 0), one narrow J^1 | ⟨B_i, B_j, N_1⟩ | OPEN |
| BNN | one broad, two narrow with ℓ+m ≡ 1 | ⟨B_i, N_ℓ, N_m⟩ | OPEN |
| NNN | k+ℓ+m ≡ 1, all narrow | ⟨N_k, N_ℓ, N_m⟩ | one of these is the volume pairing; the rest are finite and not all known |

The WDVV identity with one insertion from N and two from B moves unknowns between the BBN and BNN blocks:

    ∑_s ⟨α, β, φ_s⟩ η^{st} ⟨φ_t, γ, δ⟩
    = ∑_s ⟨α, γ, φ_s⟩ η^{st} ⟨φ_t, β, δ⟩.

Take α, β ∈ B, γ = N_k, δ = N_ℓ. The left side eats BBN seeds times BNN unknowns (and conversely). Without at least one family of those seeds evaluated from [M-bar]^{vir} — concavity, index-zero, or a reconstruction theorem proved for ⟨J⟩ — the system is homogeneous in the mixed unknowns and does not determine them.

Basalaev: from the FJRW axioms alone, genus zero for a non-maximal group reconstructs only up to scaling. Scaling is not a table.

### What this grind produces

- The filter: selection rule empties 180 cells; homogeneity empties more among the 36; the rest stay OPEN.
- The seeds that exist: 42 residue triples of W, the factored Jac(F) identity-sector algebra, and ∫_X ω^4 = 6.
- The WDVV shape that would move mixed BBN ↔ BNN once a seed family is supplied.
- A proof that WDVV plus {0, 1, 6, 1/6} does not fill the table.

The mixed table is still the object named in the Frohman problem. Reconstruction writes the equation. It does not evaluate the integral.
