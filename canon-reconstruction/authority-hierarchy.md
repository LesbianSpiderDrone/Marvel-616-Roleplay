# Canonical Authority Hierarchy
## Marvel-616 Roleplay — *Grandmaster × Salvage*

This document defines the authority structure for resolving conflicts between different sources of story and universe information during the canon reconstruction process.

The hierarchy is **not** a judgment of what is "real." It is a **tiebreaker** — a clear ruleset for what wins when two sources give contradictory information about the same fact.

---

## Overview

| Tier | Name | Description | Authority Domain |
|---|---|---|---|
| **Tier 1** | Player-Declared Facts | Things the player explicitly stated or decided | Story canon — absolute |
| **Tier 2** | Published 616 Canon | Verified published Marvel universe | Universe facts — absolute within 616 |
| **Tier 3** | First-Established Story Facts | GM-originated content that doesn't contradict higher tiers | Default story content |
| **Tier 4** | Most-Recent Consistent Version | Later GM/session content that organically evolved an earlier fact | Case-by-case |
| **Tier 5** | Unreinforced Details | Single-mention details never reinforced or built upon | Lowest — pruning candidates |

---

## Tier 1: Player-Declared Facts

**Authority: Absolute for story canon.**

These are facts the player (you) explicitly stated, decided, or established during play — not just things that happened in the story, but things you *chose* as true about the world or your character.

**Examples:**
- "Salvage has a self-imposed rule against working with governments, militaries, or corporations."
- "SalNet has 22 million members."
- "Hydra is completely gone."
- "My character doesn't know the Grandmaster exists."

**When Tier 1 conflicts with Tier 2 (published 616):** Tier 1 wins for your story. This is a roleplay, not a homework assignment. If you declared that Hydra is permanently eliminated, then in *your* story it is. The 616 baseline is a resource for flavor and calibration, not a constraint that overwrites your decisions.

**How to identify Tier 1 facts during extraction:** Look for:
- First-person statements by the player in the log text
- Explicit corrections ("no, actually..." or "I decide that...")
- Character rules the player stated (the Five Rules, etc.)
- Backstory the player provided for Salvage
- Decisions about who the crew is, how the power works, etc.

**Tier 1 facts must be logged.** See Schema Category 9 (Player Declarations).

---

## Tier 2: Published 616 Canon

**Authority: Absolute for universe facts — supersedes GM portrayal when they conflict.**

This tier covers what published Marvel Comics actually established about characters, organizations, locations, events, and universe mechanics in Earth-616. Verified via web research and cited sources (see `616-baseline.md`).

**This tier exists for one specific purpose:** When the GM's in-session portrayal of a 616 character or concept conflicts with what that character or concept actually is in published comics, published 616 wins for the purpose of the reconstruction. The GM may have been working from incomplete knowledge, blending universes, or deliberately adapting — but we need to know what the baseline actually is so you can make informed decisions.

**Examples of Tier 2 authority in action:**
- The GM portrayed Cecilia Reyes as a Brotherhood spy. Published 616 has no such connection. The reconstruction notes this deviation; the Tier 3 portrayal is what exists in your story, but the deviation is flagged.
- The GM portrayed Lucia von Bardas as a cooperative ally. Published 616 has her as a cyborg villain. Flagged — the GM's version governs your story (Tier 3), but the discrepancy is documented.
- The GM described Crystal's powers as earth/air/fire/water. Published 616 confirms this exactly. No conflict.

**When Tier 2 conflicts with Tier 1:** Tier 1 wins. Your player declarations override what 616 "should" be. If you declared something about the universe, that's your universe.

**When Tier 2 conflicts with Tier 3:** Tier 2 wins for the purpose of identifying what the baseline *is*. Whether your story uses the baseline or departs from it is then a Tier 1 decision.

**How to apply Tier 2:** Cross-reference the `616-baseline.md` document. Any GM portrayal tagged `[616-CONFIDENT]` or `[616-PROBABLE]` in that document can be treated as canonical universe fact. Portrayals that deviate from those baselines are documented as Tier 3 departures.

---

## Tier 3: First-Established Story Facts

**Authority: Default for story content that doesn't conflict with higher tiers.**

This tier covers the GM's world-building — everything they introduced, invented, described, or established that doesn't have a published 616 counterpart and wasn't overridden by player declaration.

The "first-established" part matters: **the first time something was established in your story is the authoritative version** unless a higher tier overrides it. This prevents later sessions from silently rewriting earlier facts.

**Examples of Tier 3 content:**
- Salvage's crew composition (First and Second Cohorts as described)
- Phlanax as Ultron's child (GM-fabricated character)
- The specific mechanics of Salvage's looting power (as portrayed)
- The "hidden threat-attraction mechanic" in the power
- Lucia von Bardas's cooperative characterization (departure from 616)
- Cecilia's Brotherhood affiliation (departure from 616)
- SalNet's structure and mechanics
- The Badoon scout recording events at Week 95

**When Tier 3 conflicts with another Tier 3 (a contradiction within the story):** The **first-established version wins** unless there's a clear in-story explanation for the change. Unexplained contradictions are flagged in the drift analysis (Phase 3).

**When Tier 3 conflicts with Tier 2:** Document the deviation. The story uses Tier 3. The baseline document records what 616 actually says.

---

## Tier 4: Most-Recent Consistent Version

**Authority: Case-by-case. May represent organic story evolution.**

Some facts change over time through the natural flow of the story — a character develops, a situation evolves, an earlier detail gets refined. When a later session's version of a fact *consistently replaces* an earlier version without explicit declaration or contradiction, that may represent genuine narrative evolution rather than a continuity error.

**When to apply Tier 4:**
- The later version is consistent with all the sessions between the first mention and the later version
- The change makes story sense (a relationship grew, a power developed, an organization changed)
- There is no clear sign the GM forgot or mis-remembered the earlier version

**When NOT to apply Tier 4:**
- The earlier and later versions flatly contradict each other
- The change benefits from being flagged as a potential retcon
- The change affects Tier 1 player-declared facts

**Tier 4 decisions are made during Phase 3 (drift analysis) and Phase 4 (resolution).** They are not automatic. Each case is evaluated individually with the player's input.

**Example:** If a character's crew role was described vaguely in Session 3 and very specifically in Session 9, the Session 9 version is Tier 4 — probably the "real" version that the earlier sessions were approximating.

---

## Tier 5: Unreinforced Details

**Authority: Lowest. Candidates for pruning.**

These are single-mention details that appear once, are never referenced again, and were not established as significant at the time. They may be:
- Ambient flavor that didn't become plot-relevant
- Early-session details that were organically superseded
- GM improvisations that didn't develop
- Throwaway worldbuilding

**Tier 5 details are not automatically discarded.** They are flagged during Phase 1 extraction so you can decide whether to keep them, develop them, or prune them during Phase 4 resolution.

**Examples:**
- A named NPC who appeared in one combat encounter and never returned
- A location described once with specific details never revisited
- A piece of loot from an early session that was never used or mentioned again
- An offhand reference to a historical event that had no follow-on

---

## Conflict Resolution Protocol

When two sources conflict, apply this sequence:

1. **Identify the tiers** of both conflicting claims.
2. **Higher tier wins** — the lower tier claim is flagged as a deviation, not deleted.
3. **If same-tier conflict:** Apply the "first-established" rule (earlier version wins) unless Tier 4 logic applies.
4. **Flag for player review** during Phase 4 if the conflict has meaningful story implications.
5. **Document the resolution** in `resolution/` — what was chosen, why, and what was set aside.

**No claim is silently deleted.** Everything flagged as a deviation remains documented. The reconstruction captures what the story actually was, including its internal contradictions.

---

## Special Cases

### The GM-as-616-Guide Problem
Claude served dual roles in your sessions: as a Game Master and as a guide to the 616 universe. These roles sometimes conflict. When the GM said something about a 616 character, they may have been:
- (A) Accurately describing 616 canon
- (B) Adapting 616 for your story
- (C) Incorrectly remembering 616

The reconstruction cannot assume which one without cross-referencing Tier 2. When a GM statement aligns with published 616, it is Tier 2 reinforced. When it departs, it is Tier 3 (story adaptation) until a player declaration elevates it.

### The Hidden Mechanics Problem
Two mechanics in Salvage's power were apparently unknown to the player character in-story:
- The threat-attraction mechanic
- The filter mechanic (Five Rules structurally blocking governments/militaries/corporations)

These were established by the GM and have Tier 3 authority as-established. If the player retroactively declares something about these mechanics (e.g., "I decide the filter is actually conscious"), that declaration becomes Tier 1 and supersedes the GM's version.

### Fabricated Characters Played as 616 Characters
Some fabricated characters (like Phlanax) exist in the space of 616-adjacent concepts (Ultron's children). For these, the baseline documents what 616 actually says about the broader concept, and the specific fabricated character is Tier 3. If the concept later needs to be reconciled with 616 (e.g., Phlanax is retconned as a named canonical Ultron creation), that becomes a Phase 4 resolution task.

---

## Quick Reference

**"Did the player decide this?"** → Tier 1. It wins against everything except another Tier 1 declaration.

**"Is this in published Marvel comics, verified by source?"** → Tier 2. It defines the baseline and wins against GM portrayal.

**"Did the GM establish this as a story fact, first time?"** → Tier 3. Default authority for story content.

**"Did this organically evolve across sessions?"** → Tier 4. Case-by-case; evaluate in Phase 3.

**"Was this mentioned once and never again?"** → Tier 5. Flag for pruning consideration.

---

*Authority Hierarchy version 1.0 — Phase 0*
*Cross-references: `schema.md`, `616-baseline.md`*
