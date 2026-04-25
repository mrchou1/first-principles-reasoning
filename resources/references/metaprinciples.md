# Metaprinciples Reference

> **Note**: This content is now fully integrated into SKILL.md (v2.0+). This file is kept as a standalone reference for supplementary reading.

These are candidate "first principles" organized by certainty level. Use them as a checklist to find which ones constrain your problem.

## Tier 1: Immutable Physical Laws (cannot be violated)

| Principle | Statement | Application |
|---|---|---|
| Conservation of Energy | Energy cannot be created or destroyed, only transformed. | Every energy conversion has a max theoretical efficiency. |
| Conservation of Momentum | Momentum is conserved in a closed system. | Rocket equations, propulsion design. |
| Second Law of Thermodynamics | Entropy of an isolated system never decreases. | Why 100% efficiency is impossible; why cooling costs energy. |
| Speed of Light Limit | No information or matter exceeds c in vacuum. | Latency limits, communication constraints. |
| Square-Cube Law | Surface area grows with L^2, volume with L^3. | Why large structures need different designs; heat dissipation. |
| Heisenberg Uncertainty | Cannot simultaneously know precise position and momentum. | Limits measurement precision at small scales. |
| Mass-Energy Equivalence | E = mc^2. Mass and energy are interchangeable. | Sets absolute energy content of matter; bounds fuel density. |
| Nash Equilibrium | In a non-cooperative game, stable states exist where no player benefits from changing strategy alone. | Predicts competitive behavior, pricing, and strategic stability. |

## Tier 2: Robust Empirical Patterns (very reliable, theoretically breakable)

| Principle | Statement | Caveat |
|---|---|---|
| Supply & Demand | Price moves to balance quantity supplied and demanded. | Can be distorted by monopolies, regulation, or information asymmetry. |
| Marginal Cost Pricing | In competitive markets, price trends toward marginal cost. | Only applies in competitive markets with low switching costs. |
| Network Effects | Value of a network grows non-linearly with users (Metcalfe's Law). | Only for products with genuine inter-user value. |
| Diminishing Marginal Utility | Each additional unit provides less additional value. | Does not apply to addictive goods or life-saving necessities. |
| Comparative Advantage | Trade benefits all parties when each specializes. | Assumes rational actors and low transaction costs. |

## Tier 3: Useful Heuristics (good rules of thumb, NOT fundamental truths)

| Principle | Statement | Use With Caution |
|---|---|---|
| Moore's Law | Transistor count doubles ~every 2 years. | Historical observation, not a law. Already slowing. Useful for roadmap planning, not for hard constraints. |
| Dunbar's Number | Humans maintain ~150 stable social relationships. | Population-specific; useful for community design, not for proof. |
| Loss Aversion | Losses feel ~2x as impactful as equivalent gains. | Well-replicated finding, but varies by culture and context. |
| Shannon's Information Theory | Information content is measured by unpredictability; compression is bounded by entropy. | Rigorous mathematical framework, but application requires careful modeling of the source distribution. |

## How to Use

1. During decomposition, scan Tier 1 first — these are your hard constraints.
2. Then check Tier 2 — these are strong patterns that likely apply but can be circumvented.
3. Tier 3 are heuristics — useful for intuition, never for proof.
4. Some principles may not apply to your problem. The goal is to find the few that do.
