## 23-Aug-23

- Logic -> Science of Reasoning
	- systematic and structural study of reasoning inference and principal of validation
- Principles of Validation
	1) LOI -> Law of Identity
	2) LOEM -> Law of Excluded Middle
	3) LONC -> Law of Non-Contradiction
- Proposition
	- declarative statement with truth value
	- statement with is either true or false and not both
	- eg.
		- Kolkata is the capital of India -> F
		- 2 + 3 = 5 -> T
		- ~~x + 1 = 3~~ -> no truth value
	- p, q, r, s -> represent propositions
- Truth Value
	- T (True) if proposition is true
	- F (False) if proposition is false
- Propositional Logic / Propositional Calculus
	- area of logic for validity of a proposition

 1) Negation of a Proposition
	 - Let 'p' be a proposition, then the negation of p is denoted by '¬p'.
		 - read as 'not p'
	 - Truth value of ¬p is the opposite of p.
	 - eg.
		 - p = "The bag is red."
			 - ¬p = "The bag is not red."
2) Conjunction
	- Let 'p' and 'q' be propositions, then conjunction of p and q is denoted by 'p∧q'.
		- read as 'p and q'
	- True only if both p and q are true, otherwise it is false.
	- ![[Pasted image 20230830084807.png]]
3) Disjunction
	- Let 'p' and 'q' be propositions, then disjunction of p and q is denoted by 'p∨q'.
		- read as 'p or q'
	- True if either p or q is true, or both are true. False only if both are false.
	- ![[Pasted image 20230830084729.png]]
4) XOR (exclusive OR)
	- Let 'p' and 'q' be propositions, then XOR of p and q is denoted by 'p⊕q'.
		- read as 'p exclusive or q'
	- ![[Pasted image 20230830085126.png]]
## 24-Aug-2023
5) Conditional Statements
	1) p implies q
		1) p -> q / p => q
		2) if p, then q
			- p -> hypothesis / premise
			- q -> conclusion / consequence
		3) ![[Pasted image 20230830085341.png]]
		4) also known as:
			- if p then q
			- p only if q
			- p is sufficient for q
			- q unless ¬p
	2) q -> p (converse of p -> q)
		1) ![[Pasted image 20230830085559.png]]
	3) ¬q -> ¬p (contrapositive of p -> q)
		1) ![[Pasted image 20230830085719.png]]
		2) #missing
	4) ¬p -> ¬q (inverse of p -> q)
		1) ![[Pasted image 20230830085938.png]]
6) Biconditional Statement
	1) p <-> q / p <=> q
	2) p if an only if q
	3) ![[Pasted image 20230830101122.png]]
	4) also known as:
		- p is necessary and sufficient for q
		- p iff q
		- if p, then q and the converse
		- p implies q and is implied by q

- Important Logical Operators
	1) negation ¬
	2) conjunction ∧
	3) disjunction ∨
	4) implication -> / =>
	5) biconditional <-> / <=>

- Propositional Equivalence
	1) Tautology
		- a compound proposition that is always true, no matter what the truth value of the components (propositional variables)
		- p ∨ ¬p
	2) Fallacy / Contradiction
		- a compound proposition that is always false, no matter what the truth value of the components
		- p ∧ ¬p
	3) Contingency
		- a compound proposition that is neither a tautology or a contradiction
		- p ∧ q

- Logical Equivalence
	- if p <-> q, p and q are logically equivalent
	- p === q

1) <u>De Morgan's Law</u>
	1) #missing
## 30-Aug-23
- Consider the true statement: Every computer connected to the university network is functioning properly.
	- Prove that: "X$_1$ is working properly." where X$_1$ is a computer connected to the university network.
	- Given the fact: "X$_2$ is a computer connected to the university network, that has been attacked by an invader."
		- Prove that: "There is a computer connected to the university network which isn't working properly."
- Laws of Logic discussed in propositional logic is inadequate to prove these statements.

- Predicates
	- consider the statement: "x is greater than 3"
		- "x" is the subject -> depends on the value of x
		- "is greater than 3" is the predicate
		- we can denote the statement by P(x)
			- p() -> propositional function -> "is greater than 3"
			- x -> subject
			- P(x) is the value of the proposition of the function at x
		- once we assign a value for x, we get a propositional statement
			- p(2) -> false
			- p(4) -> true

- <u>Domain of Disclosure</u>
	- Many mathematical statements assert about the truth values of statements invoking variables taken from a domain known as "domain of disclosure"
	- P(x) : "x > 3" is false for all x ∈ ℝ$^-$

- <u>Universal Quantification of P(x)</u>
	- "P(x) for all values of x is the domain of disclosure"
	- ∀x P(x) -> universal quantification
		- read as "for all x p of x"
		- ∀ -> universal quantifier
	- an input "a" such that P(x) is false is said to be a "counter example" for the universal quantification "∀xP(x)"
		- P(x) : x > 3
			- then x = 1 is a counter example for "∀xP(x)"

- <u>Existential Quantification of P(x)</u>
	- there exists an element "x" from the domain such that P(x)
	- ∃xP(x) -> existential quantification
		- read as "there exists an x such that P(x)"
		- ∃ -> existential quantifier
	- a domain is necessary for existential quantification
	- also known as:
		- there is some x such that P(x)
		- there is at least one x with P(x)
		- P(x) for some x

- <u>Truth Value of Quantification of P(x)</u>
	- ∀xP(x)
		- True -> when P(x) is true for every x in the domain of disclosure
		- False -> when there is an x in the domain of disclosure for which P(x) is false
	- ∃xP(x)
		- True -> when there is at least one x for which P(x) is true
		- False -> when P(x) is false for every x

## 31-Aug-23
- <u>Uniqueness Quantifiers</u>
	- ∃!xP(x) -> there is exactly one x, P(x)
		- ∃ -> unique quantifier
	- there is one and only one x for which P(x) is true
	- eg.
		- ∃!xP(x), where P(x): x + 3 = 5

- <u>Logical Equivalences Involving Quantifiers</u>
	- statements involving quantifiers are logically equivalent if and only if their truth values are the same, regardless of predicates and domains involved
	- S === T -> logical equivalence between statements S & T

- <u>Negation of a Quantification</u>
	- negation of ∀xP(x) is given by ∃x¬P(x)
	- eg.
		- statement: "All bird can fly."
			- negation: "There exists a bird that can't fly."
		- statement: ∃xQ(x)
			- negation: ¬(∃xQ(x)) === ∀x(¬Q(x))
	![[Pasted image 20230831104224.png]]

- <u>Nested Quantifiers</u>
	- statements involving more than one quantifier in such a way that one quantifier is within the scope of another
	- eg.
		- ∀x∃y(x + y = 0)
			- === ∀xQ(x)
				- Q(x): ∃y(x + y = 0)
			- ∀x∃yP(x, y), where P(x, y): x + y = 0
	- the order of nested universal / existential quantifiers can be changed without changing the meaning of the statement if all quantifiers are of the same type

