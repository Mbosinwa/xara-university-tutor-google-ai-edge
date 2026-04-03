---
courseName: Programming Languages
courseCode: CMS705
subjectDomain: Computer Science
materialsCount: 3
status: Active
created: 2026-03-31
lastUpdated: 2026-04-01
---

# Course Structure: Programming Languages

**Institution:** Rivers State University | **Lecturer:** Dr. H. Okwu | **Session:** 2024/2025

---

## Materials Index

| # | Filename | Title | Type | Status |
|---|----------|-------|------|--------|
| 1 | programming_lang.md | Programming Languages — Lecture Notes (Dr. H. Okwu) | file | ✓ Processed |
| 2 | programming_lang2.md | Data Flow in Programming Languages — Lecture Notes (Dr. H. Okwu) | file | ✓ Processed |
| 3 | course-outline.md | CMS705 Programming Languages — Course Outline | text | ✓ Processed |

---

## Topics

### Primary Topics (from Course Outline)

1. **Language Definition Structure**
   - What is a language?
   - Language structure as a "system of systems"
   - Core linguistic components: Phonology, Morphology, Syntax, Semantics, Pragmatics
   - Language definition semantics in computer science
   - Static Semantics vs Dynamic Semantics
   - Types of programming languages (levels of abstraction)

2. **Data Types and Structure**
   - Primitive data types: Integer, Float, Character, Boolean, Void
   - Non-primitive data types: String, Array, Struct, Class, Pointer, Enum
   - Stack memory vs Heap memory
   - Linear data structures: Array, Linked List, Stack, Queue
   - Non-linear data structures: Tree, Graph, Heap, Hash Table, Trie
   - Basic operations on data structures: Insertion, Deletion, Traversal, Searching, Updating, Sorting, Merging
   - Control structures: Sequential, Selection, Iteration, Jump
   - Data flow: model, types, visibility

3. **Runtime Considerations**
   - Implementation methods: Assembly, Compilation, Interpretation, JIT
   - Data flow in memory (Stack vs Heap at runtime)
   - Dynamic Semantics (behaviour at runtime)
   - Core structural elements: Variables, Control Structures, Functions, Comments

4. **Interpretative Language**
   - Interpretation: line-by-line execution
   - Compiled vs interpreted languages
   - Just-in-Time (JIT) compilation (e.g. Java/JVM)
   - Bytecode and runtime translation

5. **Lexical Analysis and Parsing**
   - Phonology: smallest units of a language (tokens, phonemes)
   - Morphology: how tokens/words are formed (keywords, identifiers, operators)
   - Syntax: grammar rules for well-formed programs
   - Lexical elements: keywords, identifiers, operators, numeric constants
   - Readability, writability, reliability of syntax

---

## Key Concepts

| Concept | Brief Description | Source Material |
|---------|-------------------|-----------------|
| Language | Formal system of symbols and rules for communicating instructions | programming_lang.md |
| Phonology | Study of sound/token patterns; smallest units of a language | programming_lang.md |
| Morphology | How tokens/words are formed from root elements | programming_lang.md |
| Syntax | Rules governing arrangement of words/tokens into valid sentences/programs | programming_lang.md |
| Semantics | The meaning of programs — what they do | programming_lang.md |
| Pragmatics | Context and practical usage of a language | programming_lang.md |
| Static Semantics | Compile-time checks (e.g. type compatibility, variable declarations) | programming_lang.md |
| Dynamic Semantics | Runtime behaviour — what actually happens when code executes | programming_lang.md |
| Machine Language | Binary (0s and 1s) — directly executed by CPU; machine dependent | programming_lang.md |
| Assembly Language | Mnemonic codes (MOV, ADD); requires assembler; hardware-close | programming_lang.md |
| Middle-level Language | Combines low and high-level features; e.g. C; used in OS/compilers | programming_lang.md |
| High-level Language | Human-readable, machine-independent; e.g. Python, Java, C++ | programming_lang.md |
| Primitive Data Types | Built-in, fixed-size types stored directly in memory (int, float, char, bool, void) | programming_lang.md |
| Non-primitive Data Types | Complex, dynamic-size types built from primitives (String, Array, Class, Struct) | programming_lang.md |
| Stack Memory | LIFO region of RAM; stores local variables and function call data | programming_lang.md |
| Heap Memory | Dynamic memory region; used for runtime allocation (new/delete) | programming_lang.md |
| Linear Data Structure | Elements arranged sequentially; single-level (Array, Linked List, Stack, Queue) | programming_lang.md |
| Non-linear Data Structure | Elements arranged hierarchically or graph-like; multi-level (Tree, Graph, Heap) | programming_lang.md |
| Control Structures | Mechanisms that determine the order of statement execution | programming_lang.md |
| Sequential Control | Default top-to-bottom execution; no branching | programming_lang.md |
| Selection Control | Decision-making (if, if-else, else-if, switch) | programming_lang.md |
| Iteration Control | Looping (for, while, do-while, for-each) | programming_lang.md |
| Jump Control | Unconditional transfer of control (break, continue, return, goto) | programming_lang.md |
| Data Flow | Movement, transformation, and usage of data within a program during execution | programming_lang2.md |
| Sequential Data Flow | Data moves line by line in order | programming_lang2.md |
| Conditional Data Flow | Data flows differently depending on a condition | programming_lang2.md |
| Iterative Data Flow | Data flows repeatedly through a loop | programming_lang2.md |
| Procedural Data Flow | Data moves between functions via parameters and return values | programming_lang2.md |
| Explicit Data Flow | Data movement clearly written and visible in code | programming_lang2.md |
| Implicit Data Flow | Data movement through shared/global memory; harder to trace | programming_lang2.md |
| Compilation | Entire program translated at once to machine code; produces executable | programming_lang.md |
| Interpretation | Code translated and executed line by line at runtime | programming_lang.md |
| JIT Compilation | Bytecode compiled to machine code on demand at runtime (e.g. Java/JVM) | programming_lang.md |

---

## Definitions

### Language
A formal system of symbols and rules used to transmit information and instructions between a sender (human or program) and a receiver (computer or hardware). Every instruction must have a precise, single meaning in computer language.
*Source: programming_lang.md*

### Phonology
The study of sound patterns — the smallest unit of sound called a **phoneme** (analogous to tokens, keywords, operators, identifiers, and numeric constants in programming).
*Source: programming_lang.md*

### Morphology
The study of how words/tokens are derived and constructed; deals with the smallest units of meaning including root words, prefixes, and suffixes. In programming: how keywords, operators, and identifiers form meaningful units.
*Source: programming_lang.md*

### Syntax
A set of rules governing how words/tokens and phrases are arranged to create well-formed, legal sentences/programs. Determines the order of elements and how they relate to one another.
*Source: programming_lang.md*

### Semantics
The meaning of programs. Divided into: **Lexical Semantics** (meaning of individual words/tokens), **Compositional Semantics** (meaning of sentences/expressions).
*Source: programming_lang.md*

### Pragmatics
The study of language in context; how context, speaker intention, and cultural/usage norms influence interpretation beyond literal meaning. In programming: readability, writability, reliability, and efficiency.
*Source: programming_lang.md*

### Static Semantics
Checking rules applied at **compile time** to prevent execution errors — e.g. ensuring a variable is declared before use, or that types are compatible.
*Source: programming_lang.md*

### Dynamic Semantics
The action or behaviour of code at **runtime** — how expressions are evaluated, how values are computed, and how they change during execution.
*Source: programming_lang.md*

### Data Type
A classification that tells the compiler what kind of data a variable can hold — how much memory to allocate and what operations are allowed on that data.
*Source: programming_lang.md*

### Primitive Data Types
The most basic building blocks of a programming language — provided by the language and representing single simple values directly understood by the CPU. Stored directly in memory in binary form.
*Source: programming_lang.md*

### Non-Primitive Data Types
Also called reference or derived types; more complex structures built using other data types. Defined by the programmer or standard library. Can store multiple values; have dynamic size.
*Source: programming_lang.md*

### Data Structure
A method of organising, storing, and managing data in a computer so that it can be accessed and manipulated efficiently.
*Source: programming_lang.md*

### Stack (Data Structure)
A linear data structure following the **LIFO (Last-in-First-out)** principle. Operations: push (insert) and pop (remove).
*Source: programming_lang.md*

### Queue (Data Structure)
A linear data structure following the **FIFO (First-in-First-out)** principle. Elements added to rear (enqueue) and removed from front (dequeue).
*Source: programming_lang.md*

### Linked List
A sequence of nodes where each node contains data and a pointer to the next node. Allows dynamic sizing and efficient insertion/deletion.
*Source: programming_lang.md*

### Data Flow
The movement, transformation, and usage of data within a program during execution. Describes how data moves from input → storage → processing → output.
*Source: programming_lang2.md*

### Explicit Data Flow
Data movement clearly written and visible in code — passed as parameters, returned from functions, and assigned directly. Easy to trace and debug.
*Source: programming_lang2.md*

### Implicit Data Flow
Data movement that occurs indirectly through shared memory or global variables. Not clearly visible — harder to trace.
*Source: programming_lang2.md*

### Compilation
An implementation method where the **entire program** is translated at once into an executable file (e.g. `.exe`) by a compiler.
*Source: programming_lang.md*

### Interpretation
An implementation method where code is translated and executed **line by line** at runtime using an interpreter (e.g. Python, JavaScript).
*Source: programming_lang.md*

### JIT (Just-in-Time) Compilation
A hybrid approach that compiles bytecode to machine code **on demand at runtime**. Used by the Java Virtual Machine (JVM).
*Source: programming_lang.md*

---

## Examples

### Language Structure — Phonology in Programming
`int age;` — `cout << "Enter age: ";` — `cin >> age;` — tokens are the phonemes of a programming language.
*Source: programming_lang.md*

### Morphology in Programming
`whitespace = a + b` | `Walked = Walk + ed` — identifiers built from root components like natural language words.
*Source: programming_lang.md*

### Static Semantics — Compile-time Type Error
```cpp
x = "hello"; // Compile error: cannot assign string to integer type
```
*Source: programming_lang.md*

### Primitive Data Types — Integer
```cpp
int count = 10; // stores -2,147,483,648 to 2,147,483,647
```
*Source: programming_lang.md*

### Procedural Data Flow — Grade Calculator
Three functions (`calculateTotal`, `calculateAverage`, `determineGrade`) each receive data as parameters and return results — explicit chain of data movement.
*Source: programming_lang2.md*

### Implicit Data Flow — Global Variable
```cpp
int total = 0; // global variable modified by multiple functions without passing as parameter
```
*Source: programming_lang2.md*

### Stack vs Heap at Runtime
```cpp
int localVar = value * 2;   // Stack
int* heapVar = new int(5);  // Heap — must be freed with delete
```
*Source: programming_lang2.md*

### Control Structure — Switch Statement
```cpp
switch (day) { case 1: cout << "Monday"; break; ... }
```
*Source: programming_lang.md*

### Iterative Data Flow — For Loop
```cpp
int sum = 0;
for (int i = 1; i <= 5; i++) { sum += i; }
```
Data `i` flows multiple times through the loop.
*Source: programming_lang2.md*

---

## Relationships

| From | Relationship | To |
|------|-------------|-----|
| Phonology | is a component of | Language Structure |
| Morphology | is a component of | Language Structure |
| Syntax | is a component of | Language Structure |
| Semantics | is a component of | Language Structure |
| Pragmatics | is a component of | Language Structure |
| Static Semantics | is checked at | Compile time |
| Dynamic Semantics | is evaluated at | Runtime |
| Machine Language | is lower than | Assembly Language |
| Assembly Language | is lower than | Middle-level Language |
| Middle-level Language | is lower than | High-level Language |
| Compilation | translates to | Machine Code (whole program) |
| Interpretation | translates and executes | Line by line at runtime |
| JIT | is a hybrid of | Compilation + Interpretation |
| Primitive Data Types | are building blocks for | Non-Primitive Data Types |
| Stack Memory | stores | Local variables and function call data |
| Heap Memory | stores | Dynamically allocated data (new/delete) |
| Linear Data Structures | arrange data | Sequentially (one level) |
| Non-linear Data Structures | arrange data | Hierarchically or graph-like (multiple levels) |
| Control Structures | determine | Order of data flow through program |
| Sequential Data Flow | is a type of | Data Flow (by execution) |
| Conditional Data Flow | is a type of | Data Flow (by execution) |
| Iterative Data Flow | is a type of | Data Flow (by execution) |
| Procedural Data Flow | is a type of | Data Flow (by execution) |
| Explicit Data Flow | is a type of | Data Flow (by visibility) |
| Implicit Data Flow | is a type of | Data Flow (by visibility) |
| Phonology / Morphology / Syntax | are core concerns of | Lexical Analysis and Parsing |
| Data Flow | is fundamental to | Compiler Design, OS, AI, Security, Algorithms |
