# Chapter 4
## Set Notation and Quantifiers.

*Sets:* a collection of district, well-defined objects forming a group
*Group:* a combination of a set and binary opertations
*Binary Operation:*  an operator that operates on two operands and manipulates them to return a result.

We write x ∈ X s.t. x is an element of "X" 

*Universe:* The set of all possible objects that are considered for a given context. 

Example: _S = {x ∈ X: x satisfies P}_
Some common sets:

Natural Numbers _N_ = {0,1,2,3,...}
Integers _Z_ = {..., -2, -1, 0, 1, 2, ...}
Rational Numbers _Q_ = {_p/q_ : p, q ∈ Z and q =/= 0}
Real Numbers _R_
Complex Numbers _C_ = {a + bi: i^2 = -1, a, b ∈ R}
Plane R^2 = {_(x, y)_} : x,y ∈ _R_}
For n ∈ Z+, Euclidean _n_-Space R^n = {(x1, x2, ... ,x): x(j) ∈ _R_ for j: 1,2, ... , n}


" [] " is inclusive bounds {_a <= x <= b_} : a,b,x ∈ _U_}
" () " is exclusive bounds {_a < x < b_} : a,b,x ∈ _U_}

Example 4.1
a. {x ∈ _Z_ : x^2 = 1} ==> x is a integer such that x^2 = 1, {1,-1}
b. {x ∈ _N_ : x^2 = 1} ==> x is a natural number such that x^2 = 1 {1}
c. {(x,y) ∈ R^2 : y = 0} ==> x and y are elements of R^2 such that y = 0 
d. {(x,y,z) ∈ R^3 : z = 0} ==> x, y, z are elements of R^3 such thast z = 0
e. {x ∈ Z : x is even} ==> x is an integer such that x is even
f.{(m,n) : m,n ∈ Z} ==> m and n are elements of a set such that m and n are integers

In mathematics, in order to determine the truth or falsitity of a statement, we need to know whether we are talking about a particular x or all x.

_∈:_ An element of
_∃:_ There exists, an element of 
_∀:_ For all, for every element

"For all x, x satisfies the inequality, x^2 - 1 < 0" <=>  ∀x, x^2 - 1 < 0
"For all x, x is part of a sentence p(x)" <==> ∀x, p(x)
"There is an integer x such that x = 0" <==> ∃x, (x=0)

To make all these things happen, we must use a conjuction rather than an implication.

Example 4.2
a. There exists an integer x such that it satisfies the equation x^2 + 2x = 15
b. This statement can exist in a universe where x can at least have negative values such since the solutions are at least x = 3, x = -5
c. This statement can not exist in a unvierse where only naturla numbers exist since at least one solution is negative

Example 4.3
a. ∀x, x ∈ Z
b. ∃x, ((x ∈ Z) ∧ (x > 0)
c. ∃x, ((x ∈ Q) ∧ (x^2 + 1 = 0))
d. ∀x, ∃y, (x < y)
e. ∃y, (x < y), ∀x
f. ∀x, (x ∈ Q -> (x^2 - Π =/= 0))
g. ∀x, ((x =/= 0) -> x^2 > 0))
h. ∀x, ((x > 0) -> (4 < x < 6)

For negation  with "for all" (∀x, p(x)), use "there exists" (∃x, ~p(x)). This shows that not all elements are viable for the statement since there is an elment that negates the universe. similarly, with "there exists" (∃x, p(x)) you can do (∀x, ~p(x)).

Example 4.4
There exists a person who lives in a glass house who also throws stones.

Example 4.5
Negate the following: "For every rational number x, there exists an integer n that is greater than x"
> There exists a rational number x, for all integers n such that n is less than or equal to x



