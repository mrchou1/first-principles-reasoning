# First Principles Case Studies

> **Note**: This content is now fully integrated into SKILL.md (v2.0+). This file is kept as a standalone reference for supplementary reading.

## 1. SpaceX Reusable Rockets

**Timeline**: Founded 2002 -> First successful orbital launch (Falcon 1) 2008 -> First booster landing (Falcon 9) 2015 -> Regular reflight by 2017.

**Prime Objective**: Place payload into orbit at the lowest possible cost per kg.

**Key Destroyed Assumption**: "Rockets must be expendable." This was tradition, not physics. Airplanes are reusable; rockets were single-use by historical accident of early Cold War design choices.

**Fundamental Decomposition**:
- Widely reported raw material cost of a rocket: ~2% of its price (source: Elon Musk interviews; independently estimated by aerospace analysts).
- The remaining ~98%: manufacturing labor, single-use design overhead, supply chain markup, and the cost of throwing away the vehicle each time.
- Physical constraint: Orbital velocity (~7.8 km/s) requires enormous energy. This cannot be circumvented. But the *vehicle* carrying the fuel doesn't have to be destroyed.

**Reconstruction**: If a rocket can launch, re-enter, and land with precision, it can be reused like an airplane. Key engineering challenges: (1) controlled descent propulsion, (2) precision landing guidance, (3) thermal protection for re-entry.

**What Almost Killed It**: Three failed Falcon 1 launches before success. Many spectacular landing failures. The company nearly went bankrupt in 2008.

**Alternatives Considered**: Parachute recovery (insufficient control), helicopter mid-air catch (too risky for large boosters).

**Result**: Falcon 9 launches at ~$67M vs industry average of ~$200M+ at the time. Over 300 booster landings by 2024.

## 2. iPhone Multi-Touch Interface

**Timeline**: Project Purple started ~2004 -> Announced January 2007 -> Shipped June 2007.

**Prime Objective**: Maximize the area for information display while allowing intuitive control of a pocket-sized device.

**Key Destroyed Assumptions**:
- "A phone needs a physical keyboard" (tradition)
- "Touchscreens need a stylus for precision" (tradition)
- "Screen and input are separate surfaces" (tradition)

**Fundamental Decomposition**:
- Human fingers are the primary pointing tool (~10mm touch target)
- A screen can change dynamically to show any interface
- Physical keyboards consume 30-50% of front face area for a function used <10% of the time

**Reconstruction**: Replace fixed keys with a software keyboard that appears only when needed; use the entire surface as a display. Multi-touch (acquired via FingerWorks purchase in 2005) enabled direct manipulation without a stylus.

**What Almost Killed It**: AT&T exclusivity limited reach. No copy-paste at launch. Antenna issues with iPhone 4. The real challenge was convincing carriers to cede control over device software.

**Alternatives Considered**: Click-wheel phone, physical keyboard with larger screen, Motorola ROKR E1 partnership.

**Result**: Redefined the smartphone industry. Multi-touch became the global standard within 3 years.

## 3. Amazon Prime

**Timeline**: Launched February 2005 at $79/year. 100M+ members by 2018, 200M+ by 2021.

**Prime Objective**: Remove every possible friction between a customer wanting something and having it arrive.

**Key Destroyed Assumption**: "Shipping is a per-order cost that must be charged per transaction." Tradition of retail logistics, not a law of physics or economics.

**Fundamental Decomposition**:
- Shipping cost per order creates purchase friction
- Friction reduces purchase frequency
- Purchase frequency drives lifetime customer value
- Marginal cost of shipping one more item in an already-routed truck is very low

**Reconstruction**: Charge a flat annual fee for unlimited fast shipping. This (1) eliminates per-order friction, (2) incentivizes consolidation on Amazon, (3) makes competitors' shipping fees feel painful, (4) funds infrastructure through upfront cash flow.

**What Almost Killed It**: Wall Street called it "Amazon's billion-dollar mistake." Internal models showed deep unprofitability for years.

**Result**: Prime members spend 2-3x more than non-members. Prime became the anchor of Amazon's ecosystem.

## 4. Tesla Battery Cost

**Timeline**: Founded 2003 -> Roadster 2008 -> Model S 2012 -> Gigafactory 1 announced 2014 -> Model 3 2017.

**Prime Objective**: Energy storage at the lowest possible cost per kWh.

**Key Destroyed Assumption**: "Battery packs cost $600/kWh and this is just the market price." Failure to decompose — market price included margins, middlemen, low-volume manufacturing, and no economies of scale.

**Fundamental Decomposition**:
- A battery = raw materials (lithium, nickel, cobalt, manganese, graphite, aluminum, copper) + manufacturing + assembly + supply chain overhead
- Commodity prices set a hard floor (~$40-80/kWh at material level)
- The gap was an engineering and scale problem, not a physics problem

**Reconstruction**: Buy materials at commodity prices, design custom cells, build factory at massive scale -> Gigafactory 1 in Nevada.

**What Almost Killed It**: Model 3 "production hell" (2017-2018). Battery supply constrained. Early quality issues. Multiple near-bankruptcies.

**Alternatives Considered**: Hydrogen fuel cells (lower density, infrastructure problem), ultracapacitors (insufficient density), solid-state batteries (not ready at scale).

**Result**: Battery pack costs reduced from ~$600/kWh (2010) to under $100/kWh by 2023. Not through a single breakthrough, but relentless incremental improvement.

## Patterns Across All Cases

1. **Start by rejecting the industry's answer** to "what does this cost?" or "what form does this take?"
2. **Decompose to basic physical elements**, chemistry, or unchanging human needs — not to the current industry structure.
3. **Build back up from fundamentals**, unconstrained by precedent.
4. **Success looks "obvious" in hindsight** because it aligns with fundamental truths — but was far from obvious at the time.
5. **All faced near-death experiences**. First-principles thinking doesn't guarantee success; it identifies the right target. Execution is still brutal.
6. **None was a single "eureka" moment**. Each involved years of iteration, failure, and incremental improvement.
