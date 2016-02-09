# dismathportfolio-Isabel-del-Castillo
dismathportfolio-Isabel-del-Castillo created by Classroom for GitHub

## Week 1:
- On the first week, I learned what was Discrete Mathematics all about.
- Our first lesson was all about logic and proofs.
  - In this lesson, I learned that proposition is a statement that is either true (1) or false (0).
  - There are different types of truth as dependent to its beholder
     - Legal truth - decided by a judge
     - Authoritative truth - specified by a trusted person
     - Scientific truth - confirmed by experiment
     - Probable truth - statistical analysis
     - Philosophical truth - careful exposition and persuasion
     - Mathematical truth - what we use in DISMATH
- I also learned logical connectives

| Operator | Symbol | Usage |
| :---: | :---: | :---: |
| Negation | ¬ | not |
| Conjunction | ∧ | and |
| Disjunction | v | or |
| Exclusive or | ⊕ | xor |
| Conditional | → | if, then |
|Biconditional | ↔ | iff |

- Also, I learned how to use a truth table.
  - Truth table is a lists of possible combination of inputs with corresponding output.
  - To determine the number of rows in a truth table, use 2<sup> n </sup>; let n be the number of propositional variables.
  
| Input (q) | Output (¬q) |
| :-----: | :---: |
| T | F |
| F | T |

- Conjuntion - p ∧ q is T iff both p and q are T

| p | q | p ∧ q |
| :---: | :---: | :---: |
| F | F | F |
| F | T | F |
| T | F | F |
| T | T | T |

- Disjuntion - p v q is T iff p is T or q is T.

| p | q | p v q |
| :---: | :---: | :---: |
| F | F | F |
| F | T | T |
| T | F | T |
| T | T | T |

- Exclusive or - p ⊕  q is T iff exactly one of p and q is T

| p | q | p ⊕ q |
| :---: | :---: | :---: |
| F | F | F |
| F | T | T |
| T | F | T |
| T | T | F |

- Conditional - p → q is T if both p and q are T, when p is F.

| p | q | p → q |
| :---: | :---: | :---: |
| F | F | T |
| F | T | T |
| T | F | F |
| T | T | T |

- Biconditional - p ↔ q is T iff p and q have the same truth values.

| p | q | p ↔ q |
| :---: | :---: | :---: |
| F | F | T |
| F | T | F |
| T | F | F |
| T | T | T |


## Week 2:
- In second week of DISMATH, our next lesson was about logical equivalences.
 - Aside from truth table, I could also use logical equivalences in proving.
 - There are different logical equivalences
 
| Equivalences | Name |
| :---: | :---: |
| p ∧ T ≡ p | Identity Laws|
| p v F ≡ p |  |
| p v T ≡ T | Domination Laws |
| p ∧ F ≡ F | |
| p v p ≡ p | Idempotent Laws |
| p ∧ p ≡ p | |
| ¬(¬p) ≡ p | Double Negation Law |
| p v q ≡ q v p | Commutative Laws |
| p ∧ q ≡ q ∧ p  |  |
| (p v q) v r ≡ p v (q v r) | Associative Laws |
| (p ∧ q) ∧ r ≡  p ∧  (q  ∧  r) |  |
| p v (q ∧ r) ≡ (p v q) ∧ (p v r)  | Distributive Laws |
| p ∧ (q v r) ≡ (p ∧ q) v (p ∧  r) |  |
| ¬(p v q) ≡ ¬p ∧ ¬q | De Morgan's Laws |
| ¬(p ∧ q) ≡ ¬p v ¬q | |
| p ∧  (q v p) ≡ p | Absorption Laws |
|  p v  (q  ∧  p) ≡ p | |
| p v ¬p ≡ T | Negation Laws |
| p ∧ ¬p ≡ F | |

- I learned also the converse, inverse and contrapositive.

|  | Converse | Inverse | Contrapositive |
| :---: | :---: | :---: | :---: |
| p → q | q → p | ¬p → ¬q | ¬q → ¬p |

- Besides logical equivalences, we were also taught about quantifiers.
  - Quantifiers indicates the generality of the open sentence in which a variable occurs.
    - Existential quantifier (∃x) - "there exist"
    - Universal quantifier - (∀x) - "for all"

## Week 3:
- So far, there are 3 tools in proving 
  - truth table
  - logical equivalences
  - quantifiers
- In this week's lesson, we were taught about another tool, which is the rules of inference.

| Tautology | Name |
| :-----------: | :------------: |
| (p ∧ (p → q)) → q | Modus Ponens |
| (¬q ∧ (p → q)) → ¬p | Modus Tollens |
| ((p → q) ∧ (q → r)) → (p → r) | Hypothetical Syllogism |
| ((p ∨ q) ∧ ¬p) → q | Disjunctive Syllogism |
| p → (p ∨ q) | Addition |
| (p ∧ q) → p | Simplification |
| ((p) ∧ (q)) → (p ∧ q) | Conjunction |
| ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) | Resolution |

- In our assignment, using the rules of inference, we conluded that superman does not exist.

## Week 4:
- In our fourth week in DISMATH, we were taught the different methods of proof
  1. Direct proof (p → q)
    - Assume p is T.
    - Show that q is also T.
  2. Proof by contraposition (¬q → ¬p)
    - Assume ¬q is T.
    - Show that ¬p is also T.
  3. Vacuous Proof (¬p → (p → q))
    - Show that p is F
    - p → q must be T.
  4. Trivial Proof (q → (p → q))
    - Show that q is T
    - p → q is also T
  5. Proof by contradiction
    - Asuume that the premise is not T (¬premise ≡ T)
    - Based on that, show that the premise will end up in a contradiction.   