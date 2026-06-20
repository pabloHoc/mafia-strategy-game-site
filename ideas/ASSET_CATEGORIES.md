# Asset Categories Exploration

**Status:** Exploration

## Core Principle

Assets should represent **leverage**, not modifiers.

Bad:

- Black Market: +2 Logistics
- Safehouse: +1 Stealth

Good:

- Black Market enables access to illegal goods and criminal contacts.
- Safehouse enables hiding agents and sheltering fugitives.

The player should gain new options, not passive numbers.

---

## Core Principle: Multi-System Relevance

Assets should not exist to support a single mechanic.

A good asset can naturally interact with multiple systems.

Example:

### Safehouse

Can support:

- Missions
- Agent protection
- Crisis management
- Heat reduction
- Fugitive sheltering

A Safehouse should feel like a real piece of criminal infrastructure, not a mission modifier.

---

# Infrastructure Assets

Persistent assets embedded in the world.

Examples:

- Black Market
- Smuggling Route
- Safehouse
- Casino
- Front Company
- Spy Network
- Workshop

Characteristics:

- Exist in districts.
- Are deployed geographically.
- Create local opportunities.
- Can be occupied, exposed, attacked, or relocated.
- Represent long-term organizational leverage.

Gameplay loop:

Acquire
→ Deploy
→ Generate Opportunities
→ Commit
→ Create Consequences

---

## Mental Model

Infrastructure Assets answer:

> "What opportunities exist in this territory?"

Examples:

Black Market:
- Contraband
- Forged Documents
- Criminal Specialists

Smuggling Route:
- Secret Transportation
- Cargo Movement
- Cross-Border Escape

Safehouse:
- Lay Low
- Hide Evidence
- Shelter Fugitives

---

# Leverage Assets

Temporary or situational influence.

Examples:

- Police Favor
- Blackmail Material
- Political Debt
- Judicial Contact
- Institutional Support

Characteristics:

- Usually consumed or exhausted.
- Less territorial.
- Solve specific problems.
- Often interact directly with institutions.

Examples:

Police Favor:
- Cancel investigation
- Release prisoner
- Ignore patrols

Blackmail:
- Force cooperation
- Block action
- Extract concessions

---

## Mental Model

Leverage Assets answer:

> "Who owes us?"
>
> "Who can we pressure?"
>
> "What strings can we pull?"

Unlike Infrastructure Assets, these are usually spent when used.

---

# Why Separate Them?

Infrastructure and Leverage currently seem to create very different gameplay.

Infrastructure:

- Persistent
- Territorial
- Positioning-focused
- Vulnerable to attack

Leverage:

- Temporary
- Transactional
- Situation-focused
- Consumed when used

Trying to force both into the same ruleset may create awkward mechanics.

---

# Current Working Structure

Assets
├─ Infrastructure Assets
│  ├─ Persistent
│  ├─ Deployed
│  └─ Territorial
│
└─ Leverage Assets
   ├─ Consumable
   ├─ Situational
   └─ Influence-Based

---

# Design Tests

For every asset:

1. What opportunities does it provide?
2. What requirements can it help solve?
3. Why is it different from every other asset?
4. In which systems besides missions does it matter?

If those questions are difficult to answer, the asset may be too generic or too narrow.

---

# Open Questions

## Categories

- Are Infrastructure and Leverage sufficient?
- Are there additional asset families?
- Should asset categories be visible to players or only a design concept?

## Infrastructure

- How many Infrastructure Assets should a faction realistically own?
- Can assets support neighboring districts?
- How expensive is relocation?
- How long does commitment last?
- Can infrastructure be upgraded?
- Can infrastructure combine into synergies?

## Leverage

- How are favors acquired?
- Do favors expire?
- Can leverage assets be traded?
- Can leverage assets be stolen or exposed?
- Should some leverage become infrastructure over time (e.g. recurring political support)?

## Shared Questions

- Should all assets support missions?
- Which systems should consume leverage besides missions?
- How much overlap between assets is acceptable?
- How do we prevent assets from becoming generic capability providers?
- What is the minimum number of reusable mission requirements needed for assets to interact with missions cleanly?

## Stress Tests

- Design 20 Infrastructure Assets and verify each has a distinct identity.
- Design 20 Leverage Assets and verify they create different decisions.
- Check whether losing one asset meaningfully changes strategy.
- Check whether assets remain relevant outside missions.
- Verify that assets create choices, not passive bonuses.
