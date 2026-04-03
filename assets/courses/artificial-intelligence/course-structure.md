---
courseName: Artificial Intelligence
courseCode: CMS707
subjectDomain: Computer Science
materialsCount: 6
status: Active
created: 2026-03-09
lastUpdated: 2026-04-02
---

# Course Structure: Artificial Intelligence

## Materials Index

| # | Material | Type | Status |
|---|----------|------|--------|
| 1 | cms707-ai-course-outline.md | Course Outline | ✓ Processed |
| 2 | cms707-class-jottings-problem-solving.md | Class Notes (Partial) | ✓ Processed |
| 3 | ai-modern-approach-book-summary-transcript.md | YouTube Transcript | ✓ Processed |
| 4 | peter-norvig-lex-fridman-podcast-transcript.md | YouTube Transcript | ✓ Processed |
| 5 | cs188-lecture-1-introduction-transcript.md | Lecture Transcript (UC Berkeley CS188) | ✓ Processed |
| 6 | cms707-full-class-notes-dr-friday-orji.md | Full Class Notes — Dr. Friday Orji | ✓ Processed |

---

## Topics

### Part I — Problem-Solving and Search

1. **Introduction to Artificial Intelligence**
   - Definition of Intelligence (formal definition — Dr. Orji)
   - Definition and goals of AI
   - Machines vs humans: computation vs creativity
   - Limits of Computational Power — learning order (Perception → Engineering)
   - Mundane Tasks vs Formal Tasks (explicit table)
   - History of AI (1950s to present)
   - Four approaches to AI (thinking/acting humanly/rationally)
   - AI Winters and resurgence
   - What AI can and cannot do

2. **AI Agents and Rational Agents**
   - Definition of an agent (operates automatically, perceives, persists, adapts, creates goals)
   - Rational agent (technically defined)
   - Percept Sequence — complete history of perceived inputs
   - Agent Function (abstract) vs Agent Program (concrete implementation)
   - Performance Measure — captures best/expected outcome
   - Types of agents: reactive, deliberative, hybrid
   - Rationality = maximally achieving predefined goals

3. **Problem-Solving and Search**
   - State Space Representation
   - 4-step problem-solving method (Define → Analyse → Isolate/Represent → Choose technique)
   - Problem formulation
   - Classic AI problems (Water Jug, Farmer-Lion-Goat-Yam)
   - Search strategies: Breadth-First Search (FIFO), Depth-First Search (LIFO/Stack)
   - Iterative Deepening Search (depth-limited DFS)
   - Best-First Search (combines BFS + DFS advantages)
   - Advantages of DFS (memory efficiency, early termination)
   - Informed search: A* search
   - Local search algorithms
   - Constraint Satisfaction Problems
   - Adversarial search and games: game trees, Minimax, Alpha-Beta Pruning

4. **Heuristic Search Techniques**
   - Heuristic functions
   - Informed vs uninformed search
   - Best-First Search as hybrid approach
   - Local search and optimisation

### Part II — Knowledge Representation and Reasoning

5. **Knowledge Representation**
   - Forms of KR: Natural Language, Simple Relational, Inheritance/Inferential
   - Mapping between Facts and Representations
   - Hallucination in AI — facts that may not be there
   - Inferential Knowledge — predicate logic axioms over real-world domains

6. **Using Predicate Logic**
   - Propositional logic
   - First-order (predicate) logic — formal grammar (Sentence, AtomicSentence, Term, Quantifiers)
   - Quantifiers (∀, ∃), constants, variables, predicates, functions
   - Skolemisation, unification
   - Inference rules
   - Resolution, forward and backward chaining
   - Marcus/Caesar example (8 axioms → inference)

6. **Probabilistic Reasoning**
   - Uncertainty in AI
   - Bayesian reasoning
   - Bayesian networks
   - Probabilistic inference

7. **Semantic Nets**
   - Knowledge representation techniques
   - Semantic networks
   - Frames and scripts

### Part III — Advanced Topics and Application Areas

8. **Learning**
   - Types of learning: supervised, unsupervised, reinforcement
   - Decision trees
   - Artificial neural networks
   - Deep learning
   - Bayesian learning
   - Exploitation of experience vs exploration

9. **Perception and Action**
   - Computer vision: object recognition, face detection
   - Robotics: motion planning, manipulation, control
   - Multi-agent systems
   - Biomimetic vs optimal solutions

10. **Natural Language Processing**
    - Speech recognition
    - Machine translation
    - Question answering (e.g. IBM Watson)
    - Language models
    - Parsing and semantic analysis

11. **Expert Systems**
    - Knowledge-based systems
    - Inference engines
    - Rule-based reasoning

12. **Fuzzy Logic Systems**
    - Fuzzy sets and membership functions
    - Fuzzy inference
    - Applications of fuzzy logic

13. **Genetic Algorithms**
    - Evolutionary computation
    - Selection, crossover, mutation
    - Optimisation using genetic algorithms

---

## Key Concepts

| Concept | Brief Description | Source |
|---------|-------------------|--------|
| Artificial Intelligence | Field of building systems that exhibit intelligent behaviour | course-outline, cs188-lecture-1 |
| Rational Agent | System that maximally achieves predefined goals; judged on actions not thought process | cs188-lecture-1, class-jottings |
| State Space Representation | Formal representation of a problem as states, operators, initial state, goal state | class-jottings |
| Search | Process of finding a sequence of actions/states leading from initial to goal state | course-outline, ai-book-summary |
| Heuristic | Problem-specific knowledge used to guide search more efficiently | course-outline |
| Predicate Logic | Formal language for knowledge representation using predicates, quantifiers | course-outline, ai-book-summary |
| Probabilistic Reasoning | Handling uncertainty using probability theory and Bayesian methods | course-outline |
| Semantic Net | Graph-based knowledge representation showing concepts and relationships | course-outline |
| Supervised Learning | Learning from labelled training data | ai-book-summary |
| Unsupervised Learning | Finding patterns in data without labels | ai-book-summary |
| Reinforcement Learning | Learning from rewards and punishments through interaction | ai-book-summary |
| Neural Networks | ML models inspired by biological neurons | ai-book-summary |
| Deep Learning | Multi-layer neural networks for large-scale learning | ai-book-summary |
| NLP | Field enabling computers to understand and generate human language | course-outline, cs188-lecture-1 |
| Expert Systems | AI systems encoding expert knowledge for decision making | course-outline |
| Fuzzy Logic | Logic that handles degrees of truth rather than binary true/false | course-outline |
| Genetic Algorithm | Evolutionary optimisation technique inspired by natural selection | course-outline |
| Water Jug Problem | Classic AI search problem: achieve target measurement using unmarked jugs | class-jottings |
| Farmer-Lion-Goat-Yam | Classic constraint-based river crossing problem | class-jottings |
| Minimax | Game tree search algorithm for adversarial two-player games | ai-book-summary |
| Alpha-Beta Pruning | Optimisation of Minimax that eliminates unnecessary branches | ai-book-summary |
| A* Search | Informed search using heuristic + path cost to find optimal solution | ai-book-summary |
| Exploitation vs Exploration | Tension between using known knowledge vs seeking new information | cs188-lecture-1 |
| Turing Test | Benchmark for machine intelligence via indistinguishable conversation | cs188-lecture-1 |
| Intelligence | Capacity to think and comprehend the world in an elaborate way, involving knowledge, experience and understanding | full-class-notes |
| Mundane Tasks | Human-natural tasks (perception, speech, common sense) that are computationally hard to represent | full-class-notes |
| Formal Tasks | Well-defined tasks (chess, maths, logic) that are easier to encode in a computer | full-class-notes |
| Percept Sequence | Complete history of everything an agent has ever perceived; determines agent behaviour | full-class-notes |
| Agent Function | Abstract mathematical mapping from percept sequence to action | full-class-notes |
| Agent Program | Concrete implementation of the agent function | full-class-notes |
| Performance Measure | Criterion that captures best/expected outcome for evaluating rational agent behaviour | full-class-notes |
| Best-First Search | Search strategy combining advantages of BFS (no dead ends) and DFS (memory efficiency) | full-class-notes |
| Iterative Deepening Search | DFS variant that increases depth limit incrementally; combines BFS completeness with DFS memory use | full-class-notes |
| Simple Relational KR | Table-based knowledge representation; weak inferential capability (e.g. database) | full-class-notes |
| Inferential KR | Knowledge representation that supports inheritance and logical inference across class hierarchies | full-class-notes |
| Hallucination (AI) | Facts introduced by a system that may not exist in reality; linked to lack of consciousness/self-awareness | full-class-notes |

---

## Definitions

### Artificial Intelligence
The field concerned with building systems that act rationally — maximally achieving their predefined goals — across a wide range of tasks that require intelligence.
*Source: cs188-lecture-1, ai-book-summary*

### Rational Agent
An agent that selects actions to maximally achieve its predefined goals. Rationality is about optimality of decisions, not the thought process, emotions, or nature of the goals themselves.
*Source: cs188-lecture-1*

### State Space Representation
A formal way to represent a problem using: (1) a set of possible states, (2) operators/actions that transition between states, (3) an initial state, and (4) a goal state or goal test.
*Source: class-jottings*

### Heuristic Search
Search that uses domain-specific knowledge (heuristic functions) to estimate the cost/distance to the goal, guiding search more efficiently than uninformed strategies.
*Source: course-outline*

### Predicate Logic (First-Order Logic)
A formal logical system that extends propositional logic with quantifiers (∀, ∃) and predicates, allowing representation of objects, properties, and relationships.
*Source: ai-book-summary*

### Fuzzy Logic
A logic system where truth values are continuous between 0 and 1 (degrees of truth), rather than binary, allowing handling of vague or imprecise information.
*Source: course-outline*

### Genetic Algorithm
An optimisation technique inspired by biological evolution — uses a population of candidate solutions that evolve through selection, crossover, and mutation operators.
*Source: course-outline*

### Intelligence
"The capacity to think and comprehend the world in an elaborate way, involving knowledge, experience and understanding." AI is concerned with building entities with at least human-level cognition — doing creative things humans do, but faster.
*Source: full-class-notes (Dr. Friday Orji)*

### Agent
Something that operates automatically, perceives its environment, persists over a prolonged time period, adapts to changes, and creates and pursues goals. Concretely: perceives environment through sensors and acts through actuators.
*Source: full-class-notes*

### Rational Agent
An agent that acts so as to achieve the best outcome or expected outcome when there is uncertainty. The notion of best/expected outcome is captured by a performance measure.
*Source: full-class-notes*

### Percept Sequence
The complete history of everything an agent has ever perceived. An agent's choice of action at any instant can depend on built-in knowledge and the entire percept sequence observed to date.
*Source: full-class-notes*

### Agent Function
An abstract mathematical description of how an agent maps any given percept sequence to an action. Distinguished from the agent program, which is its concrete implementation.
*Source: full-class-notes*

### Performance Measure
The criterion used to evaluate how well a rational agent is achieving its goals. Captures the notion of best or expected outcome, especially under uncertainty.
*Source: full-class-notes*

### Hallucination (AI)
Facts that may not be there — representations that do not correspond to truth in the real world. Humans avoid this through consciousness and self-awareness; AI systems lack this safeguard by default.
*Source: full-class-notes*

### Iterative Deepening Search
A DFS variant that runs depth-limited search with increasing depth limit (0, 1, 2, … ∞) until a solution is found. Combines BFS's completeness with DFS's memory efficiency.
*Source: full-class-notes*

---

## Examples

### Water Jug Problem (State Space)
- **Initial state:** Both jugs empty (0, 0)
- **Goal state:** 4-gallon jug contains exactly 2 gallons (2, ?)
- **Operators:** Fill jug, empty jug, pour from one to another
*Source: class-jottings*

### Farmer-Lion-Goat-Yam Problem
- **Notation:** FLGY| = all on left bank; |FLGY = all on right bank
- **Constraints:** Lion+Goat alone → Lion eats Goat; Goat+Yam alone → Goat eats Yam
- **Solution requires:** Careful sequencing of crossings to avoid unsafe states
*Source: class-jottings*

### TailSpin Story Generator (Early AI Failure)
"Joe Bear was hungry. He asked Irving Bird where some honey was. Joe walked to the oak tree. He ate the beehive."
The system lacked knowledge that eating something in a container requires first removing it — illustrates limits of early knowledge representation.
*Source: cs188-lecture-1*

### Water Jug Problem — Full State Space (Dr. Orji)
- **State:** (x, y) where x = gallons in 4-gal jug, y = gallons in 3-gal jug
- **Start:** (0,0) → **Goal:** (2,3) via path: (0,0)→(4,0)→(3,0)[pour]→(3,3)→(4,2)→(2,0)→(2,3)✓
*Source: full-class-notes*

### Predicate Logic — Marcus and Caesar
8 axioms used to infer whether Marcus was loyal to Caesar:
`Man(Marcus)`, `Pompeian(Marcus)`, `∀x Pompeian(x)→Roman(x)`, `Ruler(Caesar)`,
`∀x Roman(x)→[loyal(x,Caesar) ∨ hate(x,Caesar)]`, `∀x∃y loyal_to(x,y)`,
`∀x∀y person(x)∧ruler(y)∧try_assassinate(x,y)→loyal_to(x,y)`, `try_assassinate(Marcus,Caesar)`
*Source: full-class-notes*

### Knowledge Representation — Natural Language Chain
Facts → Internal Representation → Reasoning → English Generation
Example: `Man(Socrates)` + `∀x man(x)→mortal(x)` → infer `mortal(Socrates)` → "Socrates is mortal"
*Source: full-class-notes*

### Simple Relational KR — Football Players Table
Database table of player stats (Ronaldinho, Messi, etc.) with height, weight, position.
Supports queries like "Who is the heaviest player?" but has weak inferential capability.
*Source: full-class-notes*

### IBM Watson — Jeopardy! (NLP Success)
Watson combined: question parsing, knowledge retrieval from Wikipedia, confidence estimation, and Jeopardy-specific strategies to beat human champions.
*Source: cs188-lecture-1*

---

## Relationships

| From | Relationship | To |
|------|-------------|----|
| Rational Agent | is defined by | Maximally achieving predefined goals |
| State Space Search | is the foundation of | Problem-Solving and Search |
| Heuristic Search | is an improvement of | Uninformed Search |
| A* Search | uses | Heuristic + path cost |
| Minimax | is used in | Adversarial Search / Game Playing |
| Alpha-Beta Pruning | optimises | Minimax Search |
| Predicate Logic | enables | Knowledge Representation |
| Predicate Logic | is used in | Inference (resolution, chaining) |
| Bayesian Reasoning | is a type of | Probabilistic Reasoning |
| Semantic Nets | is a type of | Knowledge Representation |
| Expert Systems | depend on | Knowledge Representation + Inference |
| Neural Networks | are the basis of | Deep Learning |
| Deep Learning | is a type of | Machine Learning |
| Reinforcement Learning | is a type of | Machine Learning |
| Genetic Algorithm | is a type of | Evolutionary / Optimisation technique |
| Fuzzy Logic | contrasts-with | Classical Boolean Logic |
| NLP | is an application of | Knowledge Representation + Learning |
| Perception | enables | Action in Robotics |
| Exploitation of experience | is-a type of | Learning |
| Exploitation of simulation | is-a type of | Modeling |
| Water Jug Problem | is solved by | State Space Search |
| Farmer Problem | is solved by | Constraint-based State Space Search |
| Mundane Tasks | are harder to represent than | Formal Tasks |
| Agent Function | is implemented by | Agent Program |
| Percept Sequence | determines | Agent behaviour |
| Performance Measure | evaluates | Rational Agent |
| Iterative Deepening Search | combines advantages of | BFS + DFS |
| Best-First Search | combines advantages of | BFS + DFS |
| DFS | uses less memory than | BFS |
| Simple Relational KR | has weaker inference than | Inferential KR |
| Hallucination | is caused by | Absence of consciousness / self-awareness in AI |
| Predicate Logic | is used to express | Inferential Knowledge |
| Natural Language | maps to | Internal Representation (via KR) |

---

## Exercises

### Session 1: Introduction
1. Can introspection — reporting on inner thoughts — be accurate? Could you be wrong about what you're thinking?
2. "Computers can only do what programmers tell them" — is this true, and does it mean they can't be intelligent?
3. "Animals can only do what their genes tell them" — is this true, and does it imply animals can't be intelligent?
4. Examine which tasks can currently be solved by computers: table tennis, driving in Port Harcourt, writing a funny story, legal advice, real-time English-French translation, complex surgery. What makes the infeasible ones hard?
5. Describe a shark and octopus to a child who has never seen one. What mechanisms does the child use to comprehend them?

### Session 2: Problem Solving and Search
1. Give precise problem formulations for: (a) 4-colour map colouring, (b) monkey and bananas (3ft monkey, 8ft ceiling, movable chair), (c) debugging an "Illegal input record" message, (d) 3-jug problem (12gal, 8gal, 1gal — measure exactly 1 gallon).
2. Missionaries and Cannibals: 3 missionaries + 3 cannibals, boat holds 1–2. Get all across without missionaries being outnumbered on either side. (a) Formulate and draw complete state space. (b) Implement and solve optimally — is checking for repeated states useful?
*Source: full-class-notes (Dr. Friday Orji)*
