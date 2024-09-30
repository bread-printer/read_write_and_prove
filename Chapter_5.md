mk# Chapter 5
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

Let p, q be integers and q is nonzero without a common factor. Let's also assume that $\sqrt{2}$ is a rational number whereby $\sqrt{2}$ = p/q. Then if we square both sides, 2 = p^2 / q^2, then 2(q^2) = p^2 whereby we can assume p^2 is then even. Since p^2 is even then p is even, this implies p = 2m => 2q^2 = 4m^2. Simplifying, q^2 = 2m^2. Since q^2 is even, then q is even but this is not possible since p and q cannot have common factors. Therefore by proof by contradiction, $\sqrt{2}$ is irrational.

Be confident in your proof

Cases are necessary for proofs since they provide context for working with things like absolute value or proving with base cases (e.g. 1 or 0).


Theorem 5.3
Prove: Let x and y be real numbers. Then |xy| = |x|*|y|.

Given that x,y are real numbers, we can prove that |xy| = |x| * |y| by the possible cases:
- Positive X, Positive Y
- At least one number positive and one number negative
- Negative X, Negative Y

For the first case: |xy| = xy = x * y = |x| * |y|. This proves the first case.
For the second case assume x < 0, y > 0 : |xy| = x(-(-y)) = x * y = |x| * |y|. This proves the second case
For the final case, assume x < 0, y < 0: |xy| = (-(-x))(-(-y)) = x * y = |x| * |y|. This proves the final case. With all possible cases proven, it is evident that |xy| = |x|*|y|.


Theorem 5.4
Prove: Show that for a real number x, we get -2 <= x < 1 IFF $\frac{2x+1}{x-1}$ <= 1

Proof: Let x be a real number such that -2 <= x < 1. First we will prove with -2 <= x < 1 --> $\frac{2x+1}{x-1}$ <= 1. 
When x = -2: (2(-2) + 1)/(-2 -1) = -3/ -3 = 1; when x = 1: (2(1) +1)/(1 -1) = 3/0 which is undefined so we try with x = 0 as an alternative real integer that is close to 1: (2(0) + 1)/(0 -1) = (1)/(-1) = -1 which is less than 1. Here we have proved the first part with the direct implication. Then with $\frac{2x+1}{x-1}$ <= 1 --> $\frac{(2x+1)(x-1)}{x-1}$ <= 1(x - 1) --> 2x + 1 <= x -1 --> x <= -2. The only way both of these can be true is if x = -2. Then if x - 1 ≥ 0, then x ≥ 1, which would make (2x+1)/(x-1) > 1. Thus if -2 <= x < 1, then $\frac{2x+1}{x-1}$ <= 1. Thus we have proven the equivalence. 

