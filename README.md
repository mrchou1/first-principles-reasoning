# First Principles Reasoning Skill

A structured reasoning skill for [Claude Code](https://claude.ai/code) that enables deep first-principles analysis. It guides the model through a rigorous 5‑phase protocol to challenge assumptions, decompose problems into irreducible elements, and reconstruct novel solutions from fundamental truths.

---

## Installation

1. Copy the entire `first-principles-reasoning/` folder into your Claude Code skills directory:
   - **Personal**: `~/.claude/skills/first-principles-reasoning/`
   - **Project**: `your-project/.claude/skills/first-principles-reasoning/`
2. Restart Claude Code (or open a new session). The skill will be automatically detected.

---

## Quick Start

Once installed, you can activate the skill by saying things like:

- *"Think about this from first principles"*
- *"Break down the cost of X to its fundamental materials"*
- *"Why is this done this way? Rethink it from scratch."*
- *"Do a radical redesign of our onboarding flow using first principles."*

You can also reference it explicitly: *"Use the first-principles-reasoning skill."*

---

## What's Inside

The skill includes a carefully designed `SKILL.md` with a full reasoning protocol, plus a rich set of supporting resources:
first-principles-reasoning/
├── SKILL.md # Main skill definition & protocol
└── resources/
├── templates/
│ ├── assumptions_inventory.md # Template: Assumptions table
│ ├── mece_decomposition.md # Template: MECE tree for problem breakdown
│ ├── concept_morphological_matrix.md # Template: Morphological matrix for idea generation
│ └── experiment_canvas.md # Template: Lean experiment design
├── references/
│ ├── cognitive_biases_cheatsheet.md # Top 20 biases that distort reasoning
│ ├── first_principles_case_studies.md # Classic examples (SpaceX, iPhone, Amazon Prime, etc.)
│ ├── metaprinciples.md # Universal principles across physics, economics, logic
│ └── logical_fallacies_guide.md # Common fallacies and how to avoid them
└── tools/
└── assumption_stress_test_prompt.md # Deep attack on assumptions


---

## The 5‑Phase Protocol

When invoked, the skill walks through this loop:

1. **Define the Prime Objective** – strip away existing solutions and articulate the purest functional goal.
2. **Excavate & Destroy Assumptions** – list at least 10 assumptions, determine which are true constraints and which are merely tradition, then destroy the latter.
3. **Decompose to Fundamental Elements** – use MECE decomposition to find irreducible components (materials, energy, unchanging needs).
4. **Reconstruct from Ground Truths** – generate radically different concept combinations using a morphological matrix.
5. **Falsify & Iterate** – design minimal experiments to test the riskiest assumption, then loop back if needed.

Every phase is supported by templates and reference sheets that Claude Code can load on-demand, keeping the context lean while providing deep support.

---

## Usage Tips

- **Big, expensive problems** benefit most. Don't use it for trivial decisions.
- **Trust the process.** The protocol may feel slow at first, but it's designed to break mental shortcuts.
- **Combine with domain knowledge.** The skill provides the *how to think*; you (or other skills) provide the *what to think about*.
- **Iterate.** The skill encourages cycling through the loop multiple times as new information emerges.

---

## Contributing

This skill is meant to be improved over time. If you find better templates, more relevant metaprinciples, or sharper bias descriptions, feel free to edit the resource files. Keep the structure intact so that the main `SKILL.md` can still reference them.

---

## License

This project is provided under the MIT License. Use it, modify it, share it freely.

---

## Author

- **Name:** Mr.Chou
- **Email:** 3965537@qq.com
- **GitHub:** [mrchou1/first-principles-reasoning](https://github.com/mrchou1/first-principles-reasoning)

---