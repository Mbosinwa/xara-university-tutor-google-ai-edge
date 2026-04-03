# Xara — University Tutor

A skill for the [Google AI Edge Gallery](https://github.com/google-ai-edge/gallery) that acts as a personal AI study companion for UST PGD Computer Science students enrolled in the CMS-series courses.

## What It Does

Xara combines three roles in one:

- **Tutor** — teaches using the Socratic method (questions first, not lectures)
- **Course Organiser** — knows every course, topic, and material file
- **Examiner** — generates quizzes grounded in your actual course material

All progress is saved locally on your device via `localStorage`.

## Courses Covered

| Code | Course |
|------|--------|
| CMS707 | Artificial Intelligence |
| CMS701 | Operating Systems |
| CMS703 | Data Communications & Networks |
| CMS705 | Programming Languages |
| CMS709 | Compiler Construction |
| CMS711 | System Analysis & Design |

## Commands

| Command | Action |
|---------|--------|
| `[LC]` | List all courses |
| `[LT]` | Start a learning session on a topic |
| `[KM]` | Show the knowledge map for a course |
| `[GQ]` | Generate a practice quiz |
| `[RN]` | Generate revision notes |
| `[AQ]` | Answer an exam question with full reasoning |
| `[TP]` | Show topic-by-topic progress |
| `[SP]` | Open the visual progress dashboard |

## Project Structure

```
xara-university-tutor/
├── SKILL.md                  # Skill definition (loaded by AI Edge Gallery)
├── scripts/
│   └── index.html            # Logic runner (file loader + localStorage)
└── assets/
    ├── dashboard.html        # Visual progress dashboard (served by Gallery)
    └── courses/
        ├── artificial-intelligence/
        ├── compiler-construction/
        ├── data-communication-and-networks/
        ├── operating-systems/
        ├── programming-languages/
        └── system-analysis-and-design/
            ├── course-structure.md
            ├── knowledge-map.md
            └── materials/    # Lecture notes, transcripts, outlines
```

## How to Use

This skill is built for the [Google AI Edge Gallery](https://github.com/google-ai-edge/gallery/tree/main/skills) platform.

1. Clone or download this repository.
2. Place the folder in your AI Edge Gallery skills directory.
3. Launch the Gallery app and select the **Xara** skill.
4. Type any command above or just describe what you want to study.
