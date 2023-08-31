## 31-Aug-23
1) Show that ∀x(P(x) ∧ Q(x)) === ∀xP(x) ∧ ∀xQ(x).
	- Solution:
	- #missing

2) What if the negation of the following:
	1) ∀x(x$^2$ > x)
		- Solution:
			- ∃x(¬(x$^2$ > x))
	1) ∃x(x$^2$ = 2)
		- Solution:
			- ∀x(¬(x$^2$ = 2))

3) Show that ¬(∀x( P(x) -> Q(x) )) & ∃x(P(x) ∧ ¬Q(x)) are logically equivalent.
	- Solution:
		![[Pasted image 20230831105151.png]]

4) Let P(x, y) be the statement "x + y = y + x" what are the truth values of the following, with the domain as all real numbers?
	1) ∀x∀yP(x, y)
		- Solution:
			- for every real number x & for every real number y, x + y = y + x
			- True
				- since P(x, y) is true for all real numbers x, y
	2) ∀y∀xP(x, y)
		- Solution:
			- True

5) Let Q(x, y) denote x + y = 0, what are the truth values of ∃y∀xQ(x, y) & ∀x∃yQ(x, y), with the domain as all real numbers?
	- Solution:
		- ∃y∀xQ(x, y)
			- there is a real number y for which every real number x satisfies x + y = 0
			- False
				- since there is no real number y for which ∀xQ(x, y)
		- ∀x∃yQ(x, y)
			- for all real numbers x there is a real number y which satisfies x + y = 0
			- True
				- because for all x there exists a unique real number y satisfying Q(x, y)

6) Translate statements from natural language to logical expression and vice versa:
	1) "sum of two positive integers is always positive" where the domain consists of integers
		- Solution:
			- ∀x∀y(x > 0 ∧ y > 0 -> x + y > 0)
	2) "every non zero real number has a multiplicative inverse" where the domain is ℝ
		- Solution:
			- ∀x∃y(x != 0 -> x * y = 1)
	3) "∀x( c(x) ∨ ∃y( c(y) ∧ F(x, y) ) )"
		- c(x) = "x has a computer" 
		- F(x, y) = "x and y are friends"
		- domain for x and y consists of all students in your class
		- Solution:
			- All students in my class have a computer or have a friend who has a computer.

## 31-Aug-23 HW
1) Prove the following:
	1) p -> q === ¬p ∨ q
	2) ¬(p -> q) === p ∧ ¬q
	3) p ∨ q === ¬p -> q
	4) p ∧ q === ¬(p -> ¬q)
	5) (p -> q) ∧ (p -> r) === p -> (q ∧ r)
	6) (p -> r) ∧ (q -> r) === (p ∨ q) -> r
	7) (p -> q) ∨ (p -> r) === p -> (q ∨ r)
	8) (p -> r) ∨ (q -> r) === (p ∧ q) -> r
	9) p <-> q === (p -> q) ∧ (q -> p)
	10) p <-> q === ¬p <-> ¬q
	11) p <-> q === (p ∧ q) ∨ (¬p ∧ ¬q)
	12) ¬(p <-> q) === p -> ¬q