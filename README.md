# First Principles Reasoning Skill

A structured reasoning skill for [Claude Code](https://claude.ai/code) that guides deep first-principles analysis through an interactive, multi-phase protocol.

**Version 2.0** — Complete rewrite: single self-contained file, interactive checkpoints, depth modes, anti-pattern warnings, and richer reference materials.

---

## What's New in v2

- **Self-contained SKILL.md**: All templates, references, and tools are inlined — no external resource loading needed
- **Interactive checkpoints**: Pause after each phase for user review, instead of dumping everything at once
- **Depth modes**: Quick (2 phases), Standard (4 phases), Full (5 phases) — matched to problem complexity
- **Anti-pattern warnings**: Explicit guidance on when NOT to use first-principles thinking and common failure modes
- **Cleaned metaprinciples**: Separated into Immutable Laws / Empirical Patterns / Heuristics with honest caveats
- **Deepened case studies**: Timelines, alternatives considered, near-death experiences, and specific numbers
- **Priority ranking**: ICE framework for ranking reconstructed concepts
- **Curated biases**: Top 10 biases with specific first-principles misuse scenarios
- **Consolidated stress tests**: 6 genuinely different test dimensions instead of 5 variations of "change the environment"

---

## Installation

1. Copy the `first-principles-reasoning/` folder into your Claude Code skills directory:
   - **Personal**: `~/.claude/skills/first-principles-reasoning/`
   - **Project**: `your-project/.claude/skills/first-principles-reasoning/`
2. Restart Claude Code (or open a new session). The skill will be auto-detected.

---

## Quick Start

Activate the skill by saying:

- *"Think about this from first principles"*
- *"Break down the cost of X to its fundamental materials"*
- *"Why is this done this way? Rethink it from scratch."*
- *"Use the first-principles-reasoning skill."*

---

## The 5-Phase Protocol

| Phase | Name | What Happens | Checkpoint |
|---|---|---|---|
| 1 | Define Prime Objective | Strip away existing solutions, articulate the purest functional goal | Confirm objective with user |
| 2 | Excavate & Destroy Assumptions | List assumptions, classify sources, destroy non-essential ones | Review verdicts with user |
| 3 | Decompose to Fundamentals | MECE breakdown to irreducible elements | Validate completeness with user |
| 4 | Reconstruct from Ground Truths | Generate novel concepts via morphological matrix | Select concepts with user |
| 5 | Falsify & Iterate | Design minimal experiments, rank with ICE framework | Present final recommendation |

Each checkpoint pauses for user input — no more one-shot output dumps.

---

## When to Use / Not Use

**Use it for**: Radical innovation, cost reduction, creative blocks, "impossible" problems.

**Don't use it for**: Routine problems, time-critical decisions, compliance/safety issues, problems requiring domain expertise you lack.

---

## Project Structure

```
first-principles-reasoning/
├── SKILL.md                          # Self-contained skill (all content inlined)
├── README.md                         # This file
├── README.zh.md                      # Chinese README
├── .gitignore
└── resources/                        # Supplementary references (optional reading)
    ├── templates/                    # Standalone copies of templates
    ├── references/                   # Standalone copies of reference materials
    └── tools/                        # Standalone copies of stress test tools
```

The `resources/` directory contains the same content as SKILL.md for convenient standalone reading, but is **not required** for the skill to function.

---

## Author

- **Name:** Mr.Chou
- **Email:** 3965537@qq.com
- **GitHub:** [mrchou1/first-principles-reasoning](https://github.com/mrchou1/first-principles-reasoning)

## License

MIT License. Use, modify, and share freely.
