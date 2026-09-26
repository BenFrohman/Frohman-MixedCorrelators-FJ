# Chinese Remainder Theorem on this lab

Author: Benjamin Stanley Frohman. Copyright (c) 2026. Apache-2.0.

CRT is a ring isomorphism, not a virtual class. It applies to the discrete symmetry of this pair. It does not fill mixed correlators.

## The theorem used here

If n, m are coprime then

    Z/nmZ ≃ Z/nZ × Z/mZ.

Equivalently: a system x ≡ a (mod n), x ≡ b (mod m) has a unique solution mod nm.

Wikipedia: true over every PID; general rings use two-sided ideals.

## Where it hits this research

1. Group of the atom. |Aut(W)| = |det A| = 30 = 2·3·5.
   CRT gives

       Z/30Z ≃ Z/2Z × Z/3Z × Z/5Z.

   Characters of Aut(W) are triples of a sign, a cube root, and a fifth root.
   That is the diagonal symmetry group used as FJRW input, not μ.

2. The CY group. J has order 6 = 2·3.

       ⟨J⟩ ≃ Z/6Z ≃ Z/2Z × Z/3Z.

   Narrow sectors J^k, k=1..5, split as odd/even under the order-2 factor
   and as residue mod 3 under the order-3 factor.

3. The selection rule. Decorations multiply to J means

       k + ℓ + m ≡ 1 (mod 6).

   Because 6 = 2·3, CRT splits this into the pair

       k + ℓ + m ≡ 1 (mod 2),
       k + ℓ + m ≡ 1 (mod 3).

   A triple is allowed iff both congruences hold. That is why there are
   exactly 36 ordered decoration triples: 6^3 / 6 = 36, equivalently
   the kernel of the sum map Z/6 → Z/6 is size 36.
   CRT does not evaluate the integral on those 36 classes.

4. Degrees of the two germs. deg W = 6 = 2·3. deg W^T = 15 = 3·5.
   Weights (1,1) vs (3,2). The 2-3-5 factorization is the same three primes
   that split Aut.

5. Thom–Sebastiani of rings. Jac(F) ≃ Jac(W)^⊗³ is a tensor of algebras,
   not CRT. CRT is about coprime moduli. Tensor of Jacobians is a different
   product. Do not confuse them.

## Where it does not apply

- Not a number for ⟨α,β,γ⟩_{0,3}^{F,⟨J⟩}.
- Not Guéré's chain formula.
- Not Hodge Term A or Term B.
- Not a reason to write 0, 1, or 6 in BBN/BNN cells.

CRT organizes the group and the selection sieve. The mixed table stays OPEN.
