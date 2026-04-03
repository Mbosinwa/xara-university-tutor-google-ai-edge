---
courseName: Compiler Construction
courseCode: CMS709
subjectDomain: Computer Science
institution: Rivers State University, Nkpolu-Oroworukwo, Port Harcourt
lecturers: Dr. E.O Bennett, Dr. E.E Omaegbu
materialsCount: 1
status: Active
created: 2026-04-02
lastUpdated: 2026-04-02
---

# Course Structure: Compiler Construction

## Materials Index

| # | Filename | Title | Type | Status |
|---|----------|-------|------|--------|
| 1 | lexical-analysis-lecture-notes.md | Lexical Analysis — Lecture Notes (Dr. Bennett & Dr. Omaegbu) | text/lecture notes | ✓ Processed |

---

## Topics

### Primary Topics

1. **Lexical Analysis**
   - Definition and role of the Lexical Analyser
   - Interaction of LA with the Parser
   - Why separate LA from Syntax Analysis
   - Secondary tasks of LA (comment elimination, error correlation)

2. **Tokens, Patterns and Lexemes**
   - Token definition and classification
   - Pattern specification (regular expressions)
   - Lexeme as a concrete token instance
   - Token attributes and symbol table pointers
   - Tokens in programming languages (keywords, operators, identifiers, etc.)

3. **Difficulties and Errors in Lexical Analysis**
   - Reserved words and context-dependent keywords (FORTRAN)
   - Significance of blanks across languages
   - Error detection limits of LA
   - Lookahead requirements

4. **Specification and Recognition of Tokens**
   - Regular Definitions (via regular expressions / LEX)
   - Transition Diagrams (TD)
   - Recognising keywords: two approaches
   - Priority of tokens (longest match, first-listed pattern)

5. **Formal Language Theory**
   - Type 0–3 language hierarchy (Chomsky hierarchy)
   - Regular, Context-Free, Context-Sensitive languages
   - Alphabet, strings, and language representations
   - Σ\* — countably infinite set of all strings

6. **Finite State Automata and Transition Diagrams**
   - FSA vs TD distinctions
   - Scanner stage (FSA-based)
   - Evaluator stage
   - Dead states and retraction
   - Merging multiple DFAs/TDs into a combined diagram

7. **Input Buffering**
   - Two-half buffer design
   - Forward pointer and beginning pointer
   - Handling EOF and special characters
   - Retraction mechanism

8. **Implementation of Lexical Analyser**
   - Automatic generators (LEX / FLEX)
   - Hand-written LA in HLL
   - Hand-written LA in low-level language
   - Trade-offs of each approach

---

## Key Concepts

| Concept | Brief Description | Source Material |
|---------|-------------------|-----------------|
| Lexical Analysis | First phase of a compiler; converts character stream to token stream | lexical-analysis-lecture-notes.md |
| Token | A categorised unit of source text (keyword, identifier, operator, etc.) | lexical-analysis-lecture-notes.md |
| Pattern | A regular expression rule describing the set of strings that form a token | lexical-analysis-lecture-notes.md |
| Lexeme | The actual character sequence that matches a pattern and forms a token | lexical-analysis-lecture-notes.md |
| Symbol Table | Data structure storing token information (lexeme, line number, type) | lexical-analysis-lecture-notes.md |
| Transition Diagram (TD) | A variant of FSA used to model the lexer; reads until a token is found | lexical-analysis-lecture-notes.md |
| Finite State Automaton (FSA) | Accepts or rejects a string; basis for scanner design | lexical-analysis-lecture-notes.md |
| Regular Expression | Formal notation for specifying token patterns | lexical-analysis-lecture-notes.md |
| Forward Pointer | Input buffer pointer that scans ahead to determine the next lexeme | lexical-analysis-lecture-notes.md |
| Retraction | Rolling back the forward pointer after overshooting an accepting state | lexical-analysis-lecture-notes.md |
| Dead State | A non-accepting state with no valid transitions; signals end of scan | lexical-analysis-lecture-notes.md |
| Scanner | FSA-based stage that identifies token type and position | lexical-analysis-lecture-notes.md |
| Evaluator | Stage that processes lexeme characters to produce a token value | lexical-analysis-lecture-notes.md |
| LEX / FLEX | Automatic lexical analyser generator tools based on regular expressions | lexical-analysis-lecture-notes.md |
| Chomsky Hierarchy | Type 0–3 classification of formal languages (RL, CFL, CSL, unrestricted) | lexical-analysis-lecture-notes.md |
| Longest Match Rule | Lexer prefers the longest valid lexeme when multiple patterns match | lexical-analysis-lecture-notes.md |
| First-Listed Pattern Rule | When length is equal, the pattern listed first in specification wins | lexical-analysis-lecture-notes.md |

---

## Definitions

### Lexical Analysis
The process of taking an input string of characters (such as source code) and producing a sequence of symbols called lexical tokens (or tokens). It is the first phase of a compiler.
*Source: lexical-analysis-lecture-notes.md*

### Token
A string of characters that logically belong together — e.g., float, identifier, operator, constant. Treated as terminal symbols of the grammar specifying the source language. Also called "word".
*Source: lexical-analysis-lecture-notes.md*

### Pattern
A rule (expressed as a regular expression) that describes the set of strings associated with a particular token. The pattern "matches" every lexeme in that set.
*Source: lexical-analysis-lecture-notes.md*

### Lexeme
The actual sequence of characters forming a specific instance of a token — e.g., `"abs_zero_kelvin"`, `273`, `"float"`.
*Source: lexical-analysis-lecture-notes.md*

### Transition Diagram (TD)
A variant of FSA used to model lexical analysers. Unlike FSA, TD reads characters until finding a token, then returns that token and repositions the input buffer. Accepting states typically have no out-transitions.
*Source: lexical-analysis-lecture-notes.md*

### Finite State Automaton (FSA)
A mathematical model that accepts or rejects an input string. Used as the basis for the scanner stage of a lexer.
*Source: lexical-analysis-lecture-notes.md*

### Dead State
A non-accepting state from which there are no valid transitions. When the scanner reaches a dead state, it is done; the last accepting state is used to determine the token type and length.
*Source: lexical-analysis-lecture-notes.md*

### Retraction
The act of returning the forward input pointer to the character immediately after the accepted lexeme, when the scanner has read beyond it (marked with `*` on TD transitions).
*Source: lexical-analysis-lecture-notes.md*

### Regular Language
A formal language that can be described by a regular expression and recognised by a finite automaton. Example: L1 = {aᵐbⁿ | m, n > 0}.
*Source: lexical-analysis-lecture-notes.md*

### Context-Free Language (CFL)
A formal language generated by a context-free grammar and recognised by a pushdown automaton. Example: L2 = {aⁿbⁿ | n > 0}.
*Source: lexical-analysis-lecture-notes.md*

### Context-Sensitive Language (CSL)
A formal language that is neither regular nor context-free. Example: L3 = {aⁿbⁿcⁿ | n ≥ 0}.
*Source: lexical-analysis-lecture-notes.md*

---

## Examples

### Token, Lexeme, Pattern — Table Example
| Token | Sample Lexeme | Pattern |
|-------|---------------|---------|
| const | const | const |
| id | pi, count, D | letter · (letter\|digit)* |
| num | 3.1426, 0, 6 | any numeric constant |
| relation | <, <=, >=, != | `< \| <= \| = \| > \| >= \| !=` |
*Source: lexical-analysis-lecture-notes.md*

### Token Attributes — FORTRAN Statement
For `E = M * C ** 2`, the tokens and attributes are:
- `<id, ptr→E>`, `<assignOp>`, `<id, ptr→M>`, `<multiOp>`, `<id, ptr→C>`, `<multiOp>`
*Source: lexical-analysis-lecture-notes.md*

### TD Example 1 — Identifiers, Keywords, Numbers
A combined transition diagram with states for IDENTIFIER (states 0→1→2), INTEGER (states 0→3→4), and keyword "one" (states 0→5→7→9→10), with retraction on accepting transitions.
*Source: lexical-analysis-lecture-notes.md*

### TD Example 2 — Integers, ADD (+), INCR (++)
Transition diagram handles: `digit` → INTEGER; `+` → ADD (with retraction); `++` → INCR; `digit+` → INTEGER with potential signed continuation.
*Source: lexical-analysis-lecture-notes.md*

### Transition Table — TD Example 2
| State | + | − | D | Token | Retraction |
|-------|---|---|---|-------|------------|
| 0 | 1 | 8 | 6 | — | — |
| 1 | 3 | 2 | 2 | — | — |
| 2 | — | — | — | ADD | 1 |
| 5 | — | — | — | INCR | 2 (or 0) |
| 7 | — | — | — | INTEGER | 1 |
*Source: lexical-analysis-lecture-notes.md*

### Keyword Recognition — Symbol Table Approach
Keywords (`do`, `end`, `for`, `while`) are pre-loaded into the symbol table. When the TD recognises a string, the symbol table is checked: if found → Keyword, else → Identifier.
*Source: lexical-analysis-lecture-notes.md*

### Token Priority — Longest Match
- `DO` vs `DOT` → `DOT` is chosen (longer match)
- `>` vs `>=` → `>=` is chosen (longer match)
*Source: lexical-analysis-lecture-notes.md*

---

## Relationships

| From | Relationship | To |
|------|-------------|-----|
| Lexical Analyser | is a subroutine of | Parser |
| Lexical Analyser | reads/writes | Symbol Table |
| Token | is described by | Pattern |
| Token | is instantiated by | Lexeme |
| Token | has attribute pointing to | Symbol Table entry |
| Transition Diagram | is a variant of | Finite State Automaton |
| Scanner | is based on | FSA |
| Scanner | feeds lexeme to | Evaluator |
| Evaluator | produces | Token (type + value) |
| Regular Expression | is used to specify | Pattern |
| LEX/FLEX | generates | Lexical Analyser |
| Regular Language | is recognised by | Finite Automaton |
| Context-Free Language | is recognised by | Pushdown Automaton |
| Context-Free Language | is a superset of | Regular Language |
| Context-Sensitive Language | is a superset of | Context-Free Language |
| Forward Pointer | enables | Retraction |
| Dead State | triggers | Token acceptance (last valid state) |
| Longest Match Rule | takes priority over | First-Listed Pattern Rule |
