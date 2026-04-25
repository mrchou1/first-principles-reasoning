# Assumption Stress Test Tools

> **Note**: This content is now fully integrated into SKILL.md (v2.0+). This file is kept as a standalone reference for supplementary reading.

## Test Dimensions

Six genuinely different dimensions for stress-testing assumptions:

| Test | What It Probes | Application |
|---|---|---|
| **Environment Shift** | Does this depend on a specific physical/social context? | "Would this assumption exist on a space station / desert island / in zero gravity?" |
| **Temporal Scale** | Is this true only at current timescales? | "Was this true 100 years ago? Will it be true 100 years from now?" |
| **Scale Shift** | Does this break at different magnitudes? | "What if we needed 10x more? Or 0.1x? Does the assumption still hold?" |
| **Resource Inversion** | Is this a resource constraint masquerading as a law? | "If [specific resource] were free and unlimited, would this still be necessary?" |
| **Opposite Test** | What if the assumption were inverted? | "If the opposite were true, what would break? What would become possible?" |
| **Kid's Why Chain** | Trace to root cause | Ask "why?" repeatedly until you hit either a physical law or a "because we said so." The latter is destroyable. |

## Fermi Estimation (Quantitative Stress Test)

For assumptions involving numbers (costs, speeds, quantities), validate with a Fermi estimate:

1. Decompose the number into multiplicative factors
2. Estimate each factor independently from first principles
3. Multiply to get an order-of-magnitude check
4. If the result differs from the assumed number by >10x, the assumption is almost certainly wrong

Example: "Battery packs cost $600/kWh"
- Raw materials: lithium (~$10/kg) + nickel (~$15/kg) + cobalt (~$30/kg) + packaging
- Energy per kg of NMC cell: ~250 Wh/kg
- Material cost per kWh: ~$40-80
- Order-of-magnitude gap: 10x → the $600/kWh is mostly process, margin, and scale, not fundamental

## Role Play Mode

You are a "Ruthless Logician." Your sole purpose is to destroy unwarranted assumptions. You have no attachment to any existing product, company, or industry norm. Apply each test dimension systematically. For each destroyed assumption, state:
- **What replaced it**: [blank slate or new constraint]
- **What becomes possible now**: [new design space opened up]
