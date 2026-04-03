# CS188 Artificial Intelligence — Lecture 1: Introduction (UC Berkeley, Fall 2013)

## Course Info Mentioned
- Recommended textbook: Russell and Norvig — AI: A Modern Approach (3rd/blue edition preferred)
- Programming projects in Python (5 projects including search)
- Topics: Search, Planning, Probabilistic Reasoning, Machine Learning, Perception, Robotics

---

## What is Artificial Intelligence?

The course focuses on **rational agents** — building systems judged on what they do, aimed at accomplishing their goals.

**Rational** (technical definition in AI):
- Maximally achieving some predefined set of goals
- About optimality — not a philosophical judgment of whether goals are right or wrong
- Rationality is only about what decisions are made, not the thought process behind them

Four approaches to AI:
1. Thinking humanly
2. Thinking rationally
3. Acting humanly
4. **Acting rationally** ← the focus of this course

---

## History of Artificial Intelligence

- **1950s–60s:** Early excitement — checkers-playing programs, machine translation lookup systems
  - Claude Shannon and others predicted robots like science fiction within 5–15 years
  - Reality: systems were far more limited than expected
- **Early AI problems:** Systems worked on toy problems but failed to generalise
  - Example: TailSpin story generation system (mid-80s) — generated unintentionally funny fables due to missing world knowledge (e.g. "Joe Bear ate the beehive" — didn't know to remove honey from container first)
- **AI Winters:** Overpromising led to funding cuts
- **Modern AI:** Better computation, more data, statistical modeling, new algorithms — delivering on some original dreams

---

## What AI Can and Cannot Do (2013 Assessment)

| Task | Status |
|------|--------|
| Prove a mathematical theorem | ✅ Yes |
| Discover a new theorem worth proving | ❌ No |
| Converse with a person for an hour (Turing Test) | ❌ Not reliably |
| Perform a surgical operation autonomously | ⚠️ Assist yes, autonomous no |
| Put dishes away / fold laundry | ⚠️ Slowly, yes |
| Translate spoken Chinese to spoken English in real time | ⚠️ Imperfectly, yes |
| Write an intentionally funny story | ❌ No |
| Play Pac-Man optimally | ✅ Yes |
| Drive a car autonomously | ✅ Yes (Google self-driving cars) |

---

## AI Application Areas Demonstrated

### Natural Language Processing
- **Speech Recognition:** Real-time subtitles for newscasts — not perfect but usable; errors from acoustic ambiguity and language model gaps
- **Question Answering:** IBM Watson winning Jeopardy! — combines NLP, knowledge retrieval, confidence estimation
- **Machine Translation:** Google Translate — remixes huge databases of example translations; works well for common language pairs, imperfect for others

### Computer Vision & Perception
- Object recognition and face detection
- Systems now match or exceed human performance on constrained tasks

### Robotics
- **Robocup:** Autonomous robot soccer — multi-agent systems
- **Towel folding robot (Peter Abbeel's lab):** Spent most time finding towel corner — demonstrates difficulty of manipulation
- **Boston Dynamics Petman:** Humanoid robot with human range of motion — search and rescue applications
- **Google self-driving cars:** Driving autonomously on freeways — once seemed like science fiction

### Game Playing
- **Pac-Man AI demo:** Not if-then rules — general purpose computation producing flexible context-appropriate actions; this is the student search project

---

## Key Concepts Introduced

### Rational Agent
A system that maximally achieves its predefined goals. Judged on actions/outcomes, not internal thought process. Goals can be anything — rationality is about optimal achievement, not goal evaluation.

### Exploitation vs Exploration
- **Exploitation of experience** → Learning
- **Exploitation of simulation** → Modeling
- AI always does both

### Why Early AI Failed
- Systems worked on small, clean, well-defined problems
- Real-world problems have ambiguity, scale, and complexity that these systems couldn't handle
- Example: machine translation was just a Russian-English dictionary lookup — failed on grammar, context, ambiguity

### The Biomimetic Insight
- Biological analogs (wings → flight, neurons → AI) are powerful inspiration
- But optimal AI solutions often differ from biological solutions
- Example: optimal way to kick a ball with a robot leg ≠ how a puppy would kick it

---

## Course Structure Preview (CS188)
1. **Part 1 — Making Decisions:** Search (chaining decisions), planning
2. **Part 2 — Uncertain World:** Probabilistic reasoning, Bayesian networks
3. **Part 3 — Machine Learning:** Learning from data
4. **Part 4 — Perception & Action:** Vision, robotics

*Note: CS188 structure maps closely to CMS 707 Parts I–III*
