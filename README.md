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

| Logical Symbol  |  Logical Operator | Shorthand | Formula | Logical Expression |
| :-----: |:-------:|:-----:| :-------: | :-------: |
| ¬ |Negation | not | val(¬p) = 1 - val(p) | ¬p |
| ∧ | Conjunction | and | val(p ∧ q) = min(val(p), val(q)) | p ∧ q |
| v | Disjunction | or | val(p v q) = max(val(p), val(q)) | p v q |
| ⊕ | Exclusive disjunction | xor | if val(p)  not equal val(q) = 1 , otherwise  0|  p ⊕ q  ≡ (¬p ∧ q) v (p ∧ ¬q) |
| → | Conditional | if, then | if val(p)  ≤ val(q) = 1 , otherwise  0  | p → q ≡  ¬p v q |
| ↔ | Biconditional | iff | if val(p) equals val(q) = 1 , otherwise  0 |  p ↔ q ≡ (p → q) ∧ (q → p) |

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

|   **Rule of Inference**  |            **Tautology**           |          **Name**          |
|:--------------------|:------------------------------:|:----------------------:|
|       p<br>p→q<br>∴ q      |        (p ∧ (p → q)) → q       |      Modus Ponens      |
|     ¬q<br>p→q<br>∴ ¬p     |       (¬q ∧ (p → q)) → ¬p      |      Modus Tollens     |
|     p→q<br>q→r<br>∴ p→r    |  ((p → q) ∧ (q → r)) → (p → r) | Hypothetical Syllogism |
|      p∨q<br>¬p<br>∴ q      |       ((p ∨ q) ∧ ¬p) → q       |  Disjunctive Syllogism |
|       p<br>∴p ∨ q       |           p → (p ∨ q)          |        Addition        |
|       p ∧ q<br>∴ p       |           (p ∧ q) → p          |      Simplification      |
|      p<br>q<br>∴ p ∧ q     |      ((p) ∧ (q)) → (p ∧ q)     |       Conjunction      |
| p ∨ q<br>¬p ∨ r<br>∴ q ∨ r | ((p ∨ q) ∧ (¬p ∨ r)) → (q ∨ r) |       Resolution       | 

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
  6. Proof by Equivalence (p ↔ q ↔ (p → q) ∧ (q → p)

## Week 5:
- Continuation of methods of proof
- Proof by counterexample
  - ** Example ** "Every positive integer is the sum of the squares of two integers."
    - The counterexample given were 3, 6, 7, and 10 since they are not a sum of squares of two integers.
7. Mathematical Induction
  - Show P(1) or P(0) to be true.
  - Direct proof
    - Assume P(k) ≡ T
    - Show P(k+1) ≡ T

## Week 6:
- Program Correctness
- Recursive Algorithms
- Summation

## Week 8:
I learned that:
- An empty set is not equal to a set containing an empty set.
- A power set contains all subsets of a set. (no. of subsets= 2^n where n is the number of elements of a set)
- Identities also exist in sets.

## Week 9:
- I learned that:
  - There are 3 types of functions.
    - One-to-one function (Injective)
      - For every x,y such that (x!=y --> f(x)!=f(y))
    - Onto Function (Surjective)
      - For every y, there's an x such that (f(x)=y)
    - Bijective Function
      - If and only if it is BOTH injective & surjective.
- Also this week, I learned different types of algorithm:
  - Finding the Minimum/Maximum
  - Linear Search Algorithm
  - Binary Search Algorithm

## Week 10:
- More types of algorithm:
  - Bubble Sort Algorithm
  - Insertion Sort Algorithm
  - Greedy Change Algorithm
- I learned about Growth of Functions.
  - Big-O Notation.
  - Big-Omega Notation.
  - Big-Theta Notation.

## Week 12:
- I learned about graph theory
  - graphs
  - vertex and degree of a vertex
  - Handshaking theorem
  - Simple graphs Kn
  - Euler Circuit and Path
  - Hamilton Circuit and Path
  - Matrices of graphs
  - Isomorphism of graphs
  - Planar Graphs
  - Euler's formula

## Week 13:
- <b> COLORED GRAPHS </b>
 - A coloring of a simple graph is the assignment of a color to each vertex of the graph so that no two adjacent vertices are assigned the same color.
 - The chromatic number of a graph is the least number of colors needed for a coloring of this graph.
 - The best algorithms known for finding the chromatic number of a graph have exponential worst-case time complexity
 
<b> FOUR COLOR THEOREM </b>
- The chromatic number of planar graph is no greater than four. (ONLY APPLIES TO PLANAR GRAPHS)
- non-planar graphs can have a larger number

<b> TREES </b>
- A <b> TREE </b> is a connected undirected graph with no simple circuits.
- a data structure that emulates a hierarchichal tree structure with a set of linked nodes.
- WHY STUDY TREES?
  - used to construct efficient algorithms for locating items in a list
  - used in algorithms, such as Huffman coding, that construct efficient codes saving costs in data transmission and storage
  - used to study games such as checkers and chess and can help determine winning strategies for playing these games
  - used to model procedures carried out using a sequence of decisions
  
- THEOREM: An undirected graph is a treee if and only if there is a unique simple path between any two of its vertices.
- <b> ROOTED TREE </b>
 - a tree in which one vertex has been designated as the root and every edge is directed away from the root

- <b> LEAVES </b>
 - nodes who don't have children
- <b> INTERNAL NODES </b>
 - those who have children
 
- <b> M-ARY TREE </b>
 - A rooted tree is called an m-ary tree if every internal vertex has no more than m children.
 - The tree is called a full m-ary tree if every internal vertex has exactly m children.
 
<b> ORDERED ROOTED TREE </b>
 - a rooted tree where the children of each internal vertex are ordered
 
- PROPERTIES OF TREES </b>
 - A tree with n vertices has n-1 edges
 - A full m-ary tree with i internal vertices contains n = mi + 1 vertices
 - A full m-ary tree with 
  - (i) n vertices has i = (n-1)/m internal vertices and l = [(m-1) n + 1]/m leaves,
  - (ii) i internal vertices has n = mi + 1 vertices and l = (m-1)i + 1 leaves,
  - (iii) l leaves has n = (ml - 1)/(m-1) vertices and i = (l-1)/(m-1) internal vertices
  
- <b> MODELING COMPUTATION </b> 
 - Structures in models of computaion:
    1. Grammars
    2. Finite-State Machines
    3. Turing Machines
    
- <b> GRAMMARS </b> 
 - FORMAL LANGUAGES
 - Why not English or Tagalog or any other language?
    - There are various meanings in a language. It is not definite or could have multiple meanings. (VAGUE LANGUAGE)
 - Grammars are extremely important in the construction and theory of compilers.
 - A SOURCE CODE cannot do everything by itself.
 
 - SYNTAX - The syntax of a language is extremely complicated 
 - APLHABET - a finite set of symbols
 - VOCABULARY (V) - is a finite, nonempty set of elements called <i> symbols </i>
 - WORD (or sentece) over V
 
- <b> AUTOMATA THEORY </b>
 - studies the laws of computation
 - lexical analyzers
 
- <b> FINITE-STATE MACHINE </b>
 - consists of a finite set S of states, a finite input alphabet I, a finite output alphabet O, a transitiom function f that assigns to each state and input pair a new state, an output function g that assigns to each state and input pair an output, and an initial state s0.
 - example
   - ![alt text](https://github.com/DeLaSalleUniversity-Manila-DISMATH-t216/dismathportfolio-Isabel-del-Castillo/blob/master/vending%20machine.png)
 
- <b> FINITE-MACHINES (NO OUTPUT) </b>
 - A finite-state automaton M = (S, I, f, s0, F ) consists of a finite set S of states, a finite input alphabet I, a transition function f that assigns a next state to every pair of state and input (so that f : S × I → S), an initial or start state s0, and a subset F of S consisting of final (or accepting states).

- <b> TURING MACHINES </b> [ T =(S,I,f,s0)]
 - consists of a finite set S of states, an alphabet I containing the blank symbol B, a partial function f from S × I to S × I × {R, L}, and a starting state s0.
 

 


 
