# Chapter 2
## Logically Speaking 
### Truth tables

Basics of Truths:
1. Negation: ~P = False when P is True
2. AND: P has to be True and Q has to be True
3. OR: At least one of P and Q has to be True
4. Implied: P will make Q True or False. This piece can be confusing but has to allow for Q to be True while P is False. In such a scenario, P not being a lie is priority or at least the fulfillment of P.

| P | Q | P -> Q|
| --- | --- | ---|
| T | T | T |
| T | F | F|
| F | T | T|
| F | F | T|

5. IFF (If and ONLY If): Both P and Q must both be True or both be False for P => Q to be True

Exercise 2.5:
(P -> (~Q V R)) ∧ (R V Q)
| P | Q | R|(P -> (~Q V R)) ∧ (R V Q) |
| --- | --- | ---| --- |
| T | T | T | T |
| T | F | T | F |
| T | T | F | F |
| F | T | T | F |
| F | F | T | T |
| T | F | F | F |
| F | F | F | F |

Tautology: a statement that is true by necessity or by virtue of its logical form. A truth table where all the final states are True

Contradiction: a statement that is not true by necessity nor true by the logical form. A truth table where all the final states are False

Theorem: a statement that is always true but requires truths with a conclusive argument
The key principle to forming proofs is not only stating that a statemnt <ins>P</ins> and <ins>Q</ins> are true but also that <ins>P <=> Q</ins> is also true.j

Exercise 2.8:

| P | Q | P -> Q| ~P V Q | ~(P -> Q) | P ∧ ~Q  |
| --- | --- | --- | --- | --- |
| T | T | T | T | F | F |
| T | F | F | F | T | T |
| F | T | T | T | F | F |
| F | F | T | T | F | F |

DeMorgans Laws:
 ~(P V Q) <=> (~P ∧ ~Q)
 ~(P ∧ Q) <=> (~P V ~Q)

 Implication and its negation:
 (P -> Q) <=> (~P V Q)
 ~(P -> Q) <=> (P ∧ ~Q)

 Double Negation:
 ~(~P) <=> P

Exercise 2.10:
a. If I go to the party, and he is NOT there     ~(P -> Q) <=> (P ∧ ~Q)
b. If x is even AND x is NOT divisible by 2      ~(P -> Q) <=> (P ∧ ~Q)
c. If a function is differentiable AND it is not continous     ~(P -> Q) <=> (P ∧ ~Q)
d. If x is a natural number and x is not even and not odd (P -> (Q V W)) <=> (P ∧ (~Q ∧ ~W))


Exercise 2.11:
(P -> Q) <-> (~P ∧ Q)
~(P V Q) <-> (~P ∧ ~Q)
~(P ∧ Q) <-> (~P V ~Q)
~(P ∧ ~Q) <-> (~P ∧ ~Q)

Problem 2.3:
| P | Q | ~(P ∧ Q) | ~P V ~Q |
| --- | --- | --- | --- |
| T | T | F | F |
| T | F | T | T |
| F | T | T | T |
| F | F | T | T |

Since both statements have the same tautology they are in equivalence
