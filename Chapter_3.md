# Chapter 3 
## Introducing the Contrapositive and Converse

Theorem 3.1
Let P, Q, and R denote statement forms. Then the following are tautologies:

1. *Distributive Property* :
  - (P ∧ (Q V R) <=> ((P ∧ Q) V (P ∧ R))
  - (P V (Q ∧ R)) <=> ((P V Q) ∧ (P V R))
2. *Associative Property* :
  - (P ∧ (Q ∧ R)) <=> ((P ∧ Q) ∧ R)
  - (P V (Q V R)) <=> ((P V Q) V R)
3. *Commutative Property* :
  - (P ∧ Q) <=> (Q ∧ P)
  - (P V Q) <=> (Q V P)

Exercise 3.2
Negate the following:
  1. (P ∧ Q) V (P ∧ R) ==> ~(P V Q) ∧ ~(P V R) ==> (~P V ~Q) ∧ (~P V ~R)
  2. P -> (Q ∧ R) ==> ~P ∧ ~(Q ∧ R) ==> ~P ∧ (~Q V ~R)

Tautologies allow us to replace one statement by another. This will allow us to solve other statemnents if they have the same tautologies then proving or disproving the statements if they have equivalence.
Take for example: *x is an odd and a prime* then since we know that primes are not divisible by any number and odds are any numbers NOT divisible by 2, then by equivalence x is an odd and a prime.

Now consider from our implication, we want that the second statement is true due to the first statement and we cannot have that the first statement be TRUE and the second one be FALSE. In such a case P -> Q <=> ~P V Q. What if there a statement that swaps the first statement (hypothesis) and the second statement (conclusion) amd negates them AND yet is still true? This is called the *contrapositive*.

Why should we care about the *contrapositive*?
Take the essence of the contrapositive... This negates the conclusion and implies that the hypothesis is wrong and with the implication feature, this shows that if the conclusion is not true, then the hypothesis must also be false. So the lack of truth in the negation of the conclusion then shows that the hypothesis must be true as well.

Truth Table of Contrapositive

P -> Q: If it rains, I wear a coat

| P | Q | ~Q -> ~P (If I don't wear a coat, it is not raining) |
| --- | --- | --- |
| T | T | T (If I wear a coat, it is raining.)  |
| T | F | F (If I don't wear a coat, it is raining) |
| F | T | T (If I wear a coat, it is not raining) |
| F | F | T (If I don't wear a coat, it is not raining) |


(Practice) Theorem 3.3
*Let x be an integer. If x^2 is odd, then is x is odd*
This statement has (P -> Q) where if x^2 is odd, then is x is odd. Then if x is not odd, then x is even and an even multiplied by an even is even (2n * 2n = 4n^2, but this is clearly divisible by 2), so x^2 is even. THen by law of contrapositives, this theorem holds QED. 

There are also statements similiar to contrapositives that changes with the implications. These are called *inverse* and *converse*

*Converse* : Q -> P, a flip where the non-negated conclusion implies the non-negated hypothesis

*Inverse* : ~P -> ~Q, the implication is negated


