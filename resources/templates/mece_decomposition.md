# MECE Decomposition Guide

> **Note**: This content is now fully integrated into SKILL.md (v2.0+). This file is kept as a standalone reference.

MECE = Mutually Exclusive, Collectively Exhaustive. Break down a problem into non-overlapping components that together cover everything.

## How to Build a MECE Tree
1. Start with the Prime Objective or the problem statement at the top.
2. Ask: "What are the major, independent categories that make this up?"
3. For each category, split further until you reach irreducible elements.

## Example: "Reduce the Cost of a Smartphone"
Reduce Smartphone Cost
├── Bill of Materials
│ ├── Display
│ ├── Battery
│ ├── Processor & Memory
│ ├── Camera Module
│ ├── Casing & Buttons
│ └── Other Electronics (sensors, connectors)
├── Manufacturing & Assembly
│ ├── Labor
│ ├── Equipment Depreciation
│ └── Yield Loss
├── Logistics & Distribution
│ ├── Shipping
│ ├── Warehousing
│ └── Retail Margin
├── R&D & Intellectual Property
│ ├── Patent Licensing
│ └── Engineering Salaries
└── Software & Ecosystem (may be secondary)


## Rules
- Each parent must be fully decomposed into its children.
- Children must not overlap (mutually exclusive).
- The sum of children must equal the parent (collectively exhaustive).
- Stop when you cannot split further without losing meaning (irreducible elements).