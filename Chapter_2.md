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

