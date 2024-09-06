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

Exercise 3.5
If n is odd, then n^2 - n - 6 is even
a. Contrapositive: if n^2 - n -6 is not even them n is even
b. Converse: if n^2 - n - 6 is even them n is odd

Exercise 3.6
a.
| P | Q | ~P -> ~Q |
| --- | --- | --- |
| T | T | T |
| T | F | T |
| F | T | F |
| F | F | T |

b. The inverse is the converse of the contrapostive since it has equivalence to the converse, hence its contrapositive.
c. Since the inverse and the converse of P -> Q has the same truth tables, they are in equivalence. So they function in the same way.


---
Problems
--- 
3.1) 
a) (Q -> P) <=> ~(P -> Q)
b The contrapositive is the equivalence of P -> Q so (P -> Q) <=> (~Q -> ~P)

3.3)
a. If you are the President of the United States, then you live in a white house
  - Contrapositive: if you don't live in a white house, then you are not the president of the United States
  - Converse: if you live in a white house, then you are the president of the United States
b. If you are going to bake a souffle, then you need eggs
  - Contrapositive: if you don't need eggs, then you aren't making the souffle
  - Converse: If you need eggs, then you're making a souffle
c. If x is a real number, then x is an integer
  - Contrapositive: If x is not integer, then x is not a real number
  - Conversee: If x is an integer, then x is not a real number
d. If x is a real number,then x^2 < 0
  - Contrapositive: If x^2 >= 0, then x is not a real number
  - Converse: If x^2 < 0, then x is a real numer

3.6)
a. If it does not rain, it does not pour
b. If am not living abroad, then I do not need brownies.
c. To not run quickly, it is not sufficent to have long legs.
d. To not make good chocolate cookies, it is not necessary to have baking soda.

3.9)
Let x and y be real numbers. Show that if x =/= y  then 2x + 4 =/= 2y + 4

Proof:
Let x and y be real numbers and assume 2x + 4 = 2y + 4. Using algebra, we find that 2x + 4 = 2y + 4 ==> 2x = 2y ==> x = y. Thus when 2x + 4 = 2y + 4, x = y.  By law of contrapositive, when x =/= y then 2x + 4 =/= 2y + 4. 

3.12
Consider P -> Q and P -> (Q V ~P)

| P | Q | P -> Q | P -> (Q V ~P) |
| --- | --- | --- | --- |
| T | T | T | T |
| T | F | F | F |
| F | T | T | T |
| F | F | T | T |

Since they have the same truth values then they are in equivalence. 

