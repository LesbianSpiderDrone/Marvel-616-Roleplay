# Canonical Schema
## Marvel-616 Roleplay — Session Log Extraction Template

This schema defines the categories of information to extract from each session log during Phase 1. Every extraction file should use this structure. Not every category will have entries in every session — leave sections blank or mark `N/A` rather than fabricating content.

---

## Header Block

```
Session Log: [filename]
Session Number: [N]
In-story Timeframe: [Week X – Week Y, or approximate]
Real-world Session Date (if known): [date or unknown]
Extractor Notes: [anything unusual about this log's format, gaps, or reliability]
```

---

## Category 1: Characters

Track every named character who appears, is mentioned by name, or is implicitly referenced.

### 1A. 616 Canonical Characters
Characters who exist in published Marvel Earth-616 comics.

| Field | Content |
|---|---|
| Name | Canonical name + alias if used |
| First Appears In Story | Session number / approximate week |
| Role in Story | Protagonist / Ally / Antagonist / Neutral / Referenced-only |
| Status at Session End | Active / Injured / Dead / Missing / Unknown |
| Portrayed as (summary) | Brief description of how they were characterized this session |
| 616-Compliance Notes | Any deviation from published canon characterization |

### 1B. Fabricated Characters
Characters invented by the GM who have no published Marvel counterpart.

| Field | Content |
|---|---|
| Name | As used in session |
| First Appears | Session / week |
| Role | As above |
| Apparent Affiliation | Organization, faction, or independent |
| Description | Physical, personality, or power notes |
| Origin Plausibility | Does the fabrication fit within 616's logic? Flag if implausible. |

### 1C. Original Characters (OC)
The player character and any OC companions or allies.

| Field | Content |
|---|---|
| Name / Alias | As used |
| First Appears | Session / week |
| Role | Protagonist / Supporting OC |
| Key Actions This Session | Bullet points |
| Power Use | How the OC power was used; any new behavior observed |
| Relationships Affected | Who the OC interacted with meaningfully |

---

## Category 2: Locations

### 2A. 616 Canonical Locations
| Field | Content |
|---|---|
| Name | As used |
| Type | City / Country / Facility / Space / Dimensional / etc. |
| First Referenced | Session / week |
| Role | Combat site / Base / Mentioned / Backdrop |
| 616-Compliance Notes | Anything unusual about how it was portrayed |

### 2B. Fabricated Locations
| Field | Content |
|---|---|
| Name | As used |
| Type | As above |
| First Referenced | Session / week |
| Connection to Canon | Near a known location? Affiliated with a known org? |
| Description | As portrayed |

### 2C. OC-Associated Locations
Locations specific to the OC's operation (ship, bases, embassies, etc.).
| Field | Content |
|---|---|
| Name / Designation | As used |
| Type | Ship / Base / Embassy / Other |
| First Established | Session / week |
| Status | Active / Destroyed / Modified |
| Notable Features | Technology, inhabitants, function |

---

## Category 3: Organizations & Teams

### 3A. 616 Canonical Organizations
| Field | Content |
|---|---|
| Name | Canonical name |
| First Referenced | Session / week |
| Role | Ally / Antagonist / Neutral / Referenced-only |
| Status in Story | Intact / Weakened / Eliminated / Unknown |
| Leadership as Portrayed | Who is shown leading them |
| 616-Compliance Notes | Deviations from published status |

### 3B. Fabricated Organizations
| Field | Content |
|---|---|
| Name | As used |
| First Referenced | Session / week |
| Role | As above |
| Apparent Function | Military / Political / Criminal / Commercial / Other |
| Size / Scope | Suggested scale |
| Notes | Origin, affiliation guesses |

---

## Category 4: Events & Plot Points

### 4A. Story Events (in-world)
Events that happen within the story during this session.

| Field | Content |
|---|---|
| Event Name / Label | Short descriptor |
| In-story Date | Week N |
| What Happened | Concise summary |
| Who Was Involved | Characters, orgs |
| Outcome / Consequence | Immediate result |
| Threads Generated | New hooks or questions this created |

### 4B. Referenced 616 Events
Published Marvel events that are mentioned, alluded to, or whose aftermath is visible.

| Field | Content |
|---|---|
| Event Name | As named or implied |
| Reference Type | Direct mention / Implied / Aftermath visible |
| In-story Implication | How it affects the current story state |
| 616-Compliance Notes | Does the reference match published canon? |

---

## Category 5: Relationships & Dynamics

### 5A. Interpersonal Relationships
| Field | Content |
|---|---|
| Characters | Person A — Person B |
| Relationship Type | Alliance / Rivalry / Romance / Mentorship / Suspicion / etc. |
| Current Status | Active / Strained / Severed / New |
| Key Moment This Session | What defined the relationship this session |
| Trend | Improving / Stable / Deteriorating |

### 5B. Faction-Level Relationships
| Field | Content |
|---|---|
| Factions | Org A — Org B |
| Relationship Type | Alliance / Neutrality / Tension / Cold War / Open Conflict |
| Current Status | Stable / Shifting / Broken |
| Key Event This Session | What changed or was reinforced |

---

## Category 6: Powers, Abilities & Limitations

### 6A. OC Powers
Document every observed behavior of the OC's power, including edge cases and new uses.

| Field | Content |
|---|---|
| Power / Ability | Name or description |
| Session Observed | Session / week |
| Trigger Condition | What activated it |
| Effect | What it did |
| Limitations Observed | What it could NOT do / costs / restrictions |
| Consistency Note | Does this match prior behavior? Flag anomalies. |
| Hidden Mechanic Hint? | Flag anything that might be the "threat attractor" or "filter mechanic" |

### 6B. 616 Character Powers (as portrayed)
| Field | Content |
|---|---|
| Character | Name |
| Power / Ability | As portrayed |
| 616-Compliance | Does it match published power profile? |
| Notable Deviations | Anything unusual |

---

## Category 7: Items, Tech & Artifacts

### 7A. 616 Canonical Items
| Field | Content |
|---|---|
| Name | Canonical name |
| First Appears | Session / week |
| Current Holder | Who has it |
| Portrayed Function | How it was used |
| 616-Compliance Notes | Deviations from published function |

### 7B. Fabricated Items & Tech
| Field | Content |
|---|---|
| Name / Descriptor | As used |
| First Appears | Session / week |
| Origin | Looted / Crafted / Given / Unknown |
| Function | As described |
| Significance | Why it matters to the story |

---

## Category 8: Universe Rules & Systems

Document any time the GM establishes or implies a rule about how the universe works. This is especially important for tracking the OC's power logic.

| Field | Content |
|---|---|
| Rule / System | Short label |
| Domain | Magic / Cosmic / Mutant / Tech / Political / Economic / Other |
| Established In | Session / week |
| As Stated | Direct quote or close paraphrase |
| Implications | What this rule enables or prevents |
| 616-Compliance | Does this match known 616 rules? |
| Consistency | Conflicts with any prior established rule? |

---

## Category 9: Player Declarations

Things the player explicitly stated, decided, or established as fact. These have Tier 1 authority.

| Field | Content |
|---|---|
| Declaration | What was stated |
| Session | Session / week |
| Domain | Character / World / Power / Rule / Relationship / Other |
| Downstream Consequences | What this committed the story to |
| Status | Active / Superseded / Ambiguous |

---

## Category 10: Unresolved Threads & Hooks

Plot threads, mysteries, or questions left open at the end of the session.

| Field | Content |
|---|---|
| Thread | Short descriptor |
| Introduced | Session / week |
| Type | Mystery / Threat / Promise / Relationship tension / World-state question |
| Characters Involved | Who is connected to this thread |
| Last Status | What's the most recent information on this thread |
| Priority | High / Medium / Low (story significance) |

---

## Category 11: Tone & Genre Markers

Track the tonal and genre character of each session — what kind of story this is, and how it's evolving.

| Field | Content |
|---|---|
| Primary Genre This Session | Action / Political / Philosophical / Cosmic / Social / Horror / Other |
| Tone | Optimistic / Bleak / Tense / Triumphant / Ambiguous |
| Thematic Concerns | What ideas or questions is the story wrestling with |
| Stylistic Notes | Pacing, narrative voice, set-piece type |
| Shift from Prior Session | Same / Escalating / Pivoting / Softening |

---

## Extraction Notes

Use this section for anything that doesn't fit the above categories:
- Contradictions noticed mid-extraction
- Ambiguities that require cross-referencing other sessions
- Questions for Phase 2 consolidation
- Flagged content for 616-compliance audit

---

*Schema version 1.0 — Phase 0*
*Authority: canon-reconstruction/authority-hierarchy.md*
