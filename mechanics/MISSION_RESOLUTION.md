# Mission Resolution

**Status:** WIP

## Purpose

Define how missions are discovered, contested, escalated, and resolved while preserving player agency and avoiding last-mover advantage.

## Core Concept

Mission resolution is a conflict framework based on incomplete information, simultaneous escalation, and hidden reserves. Missions are contests of preparation, information, and commitment rather than contests of who can add resources last.

Both attackers and defenders make decisions under uncertainty. Intel quality determines what information is available before committing to escalation.

## Entities

- Mission
- Faction
- Intel
- Reserves
- Interference

## Rules

### Planning

The initiating faction commits resources to a mission.

Resources committed become unavailable elsewhere.

The faction may also allocate hidden reserves.

### Hidden Reserves

A mission may include reserve resources that are not initially revealed.

Reserves are only activated during escalation.

Design purpose:

- Create bluffing.
- Prevent last-mover advantage.
- Reward preparation.

### Discovery & Interference

Missions may be discovered.

Once discovered, other factions may interfere and commit their own resources.

They may also prepare reserves.

### Information Asymmetry

Players should not automatically receive perfect information.

Notifications depend on Intel quality.

Information tiers:

- Low Intel
- Medium Intel
- High Intel
- Perfect Intel

Higher Intel reveals increasingly precise information.

### Escalation

After interference is detected, involved factions receive a final decision window.

Each faction chooses simultaneously:

- Hold
- Activate Reserves
- Retreat

Important:

- Decisions are simultaneous and hidden.
- No further escalation occurs.

### Resolution

After escalation choices are revealed:

Mission strength is calculated and outcomes are resolved.

### Outcome Types

Mission outcomes should not be binary.

Possible outcomes:

- Critical Success
- Success
- Partial Success
- Failure
- Catastrophic Failure

## Player Interaction & Tradeoffs

- Commit resources now or preserve flexibility.
- Gather intel or act quickly.
- Escalate or retreat.
- Reveal reserves or save them.
- Interfere with rivals or focus elsewhere.

## Progression

- Early game: Limited intel and reserves.
- Mid game: Greater interference and counterplay.
- Late game: Complex conflicts driven by information warfare.

## Interactions

- `MISSIONS.md`
- `INTEL.md`
- `HEAT.md`
- `ORGANIZATIONS.md`
- `TERRITORIES.md`

## Design Notes

Design principles:

- Both sides must have agency.
- No player gains last-mover advantage.
- One escalation window creates tension without creating auctions.
- Composition matters more than raw numbers.
- Every mission should leave traces in the world.

## Open Questions

- [QUESTION] How are reserves generated and replenished?
- [QUESTION] How is mission strength calculated?
- [QUESTION] Which resources may be used as reserves?
- [QUESTION] How much information does each Intel tier reveal?

## TODO

- [ ] Define mission strength formula.
- [ ] Define discovery mechanics.
- [ ] Define Intel system.
- [ ] Define interference actions.
- [ ] Define consequences and world-state changes.
