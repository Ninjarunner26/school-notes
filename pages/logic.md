## Intro
	- **Logical propositions** are statements that can either be **true** or **false.**
	- If the statement contains an **undefined variable**, it is not a proposition.
	- **Notation and Syntax:**
	- Use **lowercase letters**. **~** is used to denote a **negation**. **^** is used to denote **and**. **V** is the symbol for **or**. A **+ in a circle** represents **exclusive or**.
	- There is an **order of operations** to logical statements. **Not** is done first, then **and**, then **or**.
- ## Venn Diagrams
	- Draw a Venn Diagram with a circle for each proposition involved in a statement. Then shade in all the areas that are included/true for the statement
- ## Logical Equivalence
	- **Truth tables** list out all possible values for a given set of propositions and statements.
	- We can use them to determine whether a given pair of propositions or statements are equivalent.
- ## Gate Diagrams & Boolean Algebra
	- Gate diagrams are visual representations of the previously discussed concepts:
	  [[logic-gate-diagrams]]
	- Boolean Algebra is a different notation for logical propositions and statements.
- ## Laws of Logic
	- There's a set of rules to assist in simplifying logical expressions.
	- **Identity law**: 
	  P^1 <=> P
	  PV1 <=> 1
	  P^0 <=> 0
	  PV0 <=> P
	- **Idempotent law**:
	  P^P <=> P
	  PVP <=> P
	- **Complement law**:
	  ~(~P) <=> P
	  P^~P <=> 0
	- **De Morgan's**
	  ~(AB) =  ~A + ~B
	  ~(A + B) = ~A * ~B
	- **Distributive**
	  A(B+C) = AB + AC
	  A + BC = (A+B)(A+C)
	- **Absorption**
	  A(A+B) = A
	  A(~A+B) = AB
	  A + AB = A
	  A + ~AB = A+B
- ## Conditionals
	- P -> Q
	  If P, Then Q
	- **Example**
	  If I live in Victoria, then I live in BC
	- P -> Q <=> ~Q -> ~P
	- P <-> Q
	  If and only if P, Then Q
	- **Example**
	  If and only if it is Sunday, then tomorrow is Monday