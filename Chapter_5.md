# Chapter 5
## Proof Techniques

Here we will cover the three most importatn means of proving:
- Direct Proof (just do by intuition)
- Proof by Contradiction (show that the negation of the statement you wish to prove implies the impossible)
- Proof in cases (which may be used when conditions dictate that different situations occur). 

Some other ones are:
- proof by exhaustion (in calculus, its used the proof that something is true by showing that it is true for each and every case that could possibly be considered)

Example of Formal Proof:
Theorem 5.1 
If a, b, and c are integers such that a divides b and a divides c, then a divides b+c
1) _Understanding The Problem:_  The hypothesis is that a, b, and c are integers such that a divides b and a divides c AND a divides c. This means a = bn such that n is an integer too (usually written as a|b or a|c.
2) _Devising a Plan:_ Since we know that c = an and b = am, we need to find an integer such that a|(b+c) ==> a|(am + an) ==> a|a(m + n). Since b + c  = am + an, there is a common factor of a and (m + n) is an integer, a|(b+c).

Proof: Let a, b, and c be integers such that a divides b and a divides c. We need to prove that a divides b + c. Since a divides b, there exists an integer m such that b = am. Since a divides c, there exists an integer n such that c = an.
Now, consider b + c: b + c = am + an   (substituting the expressions for b and c)
= a(m + n)  (factoring out a). Since m and n are integers, their sum (m + n) is also an integer. Let's call this sum k, so m + n = k. Then, b + c = ak, where k is an integer. By definition of divisibility, this means a divides b + c.
Therefore, we have proven that if a divides b and a divides c, then a divides b + c. ∎

Theorem 5.2

Prove: $\sqrt{2}$ is not a rational number
 
