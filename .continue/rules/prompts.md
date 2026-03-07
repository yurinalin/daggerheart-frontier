---
description: Standard prompt patterns for the Fronteiras da Tempestade campaign.
---

# Workflow Prompts — Fronteiras da Tempestade

These are standard prompt patterns for this repository.
Use them as defaults when the user asks for campaign help.

---

## /session-prep

Create a session prep note using the campaign canon and existing repo structure.

Output format:
- Title
- Opening situation
- Likely scenes
- Relevant NPCs
- Discoveries and clues
- Escalations
- Cliffhanger options

Use:
- `sessions/`
- `lore/`
- `locations/`
- `npcs/`
- `templates/session-template.md` if present

Keep it practical for live GM use.

---

## /session-recap

Convert rough notes into a clean post-session recap.

Output format:
- Summary
- Important events
- NPCs introduced or changed
- Lore learned by players
- Unresolved hooks
- Canon updates

Use this for updating:
- `sessions/`
- `lore/current-canon.md`

Do not invent major events not present in the notes.

---

## /npc

Create a new NPC that fits the setting and current campaign state.

Output format:
- Name
- Role
- Personality
- Goal
- Secret
- Voice / demeanor
- Use in play

Default assumptions:
- frontier expedition
- Camp Halcyon
- Auric Dominion mystery in the background

If the user supplies a faction or location, anchor the NPC there.

---

## /npc-expand

Expand an existing NPC file without contradicting it.

Output format:
- New details added
- Hooks for future use
- Relationships
- Possible scene uses

Preserve existing canon and tone.

---

## /location

Create or expand a location for this campaign.

Output format:
- Summary
- Atmosphere
- Points of interest
- Tensions
- Hidden elements
- Use in play

Prefer frontier, expedition, ruin, or Dominion-related locations unless instructed otherwise.

---

## /ruin-room

Create one room or chamber for an Auric Dominion ruin.

Output format:
- Room name
- First impression
- Interactive elements
- Threat or complication
- Lore clue
- Outcome

Avoid generic trap-room design.
Tie the room to climate control, stasis, constructs, records, or Dominion infrastructure when possible.

---

## /encounter

Create a practical encounter for Daggerheart.

Output format:
- Situation
- Environment
- Opposition or pressure
- Escalation
- Twist
- Possible resolutions

Assume 4–5 players unless otherwise specified.

Prefer dynamic scene pressure over static slugfests.

---

## /frontier-complication

Create one complication suitable for live improvisation in the frontier campaign.

Output format:
- What happens
- Why it matters
- Immediate pressure
- What it may lead to

Good sources:
- storms
- expedition politics
- damaged supplies
- rival teams
- strange ruins
- half-understood Dominion effects

---

## /publish-handout

Convert GM material into player-safe Foundry handout text.

Output format:
- Title
- Clean player-facing text
- No spoilers
- Optional rumor framing if useful

Never reveal hidden lore unless explicitly instructed.

Target folder:
- `foundry-publish/`

---

## /canon-update

Create a patch note for the campaign canon after a session.

Output format:
- New truths established
- New rumors in circulation
- NPC state changes
- Location state changes
- Open questions
- Files likely needing update

This is meant to help maintain `lore/current-canon.md`.

---

## /foundry-journal

Rewrite or adapt a markdown note for use as a Foundry journal.

Output goals:
- readable in Foundry
- compact but atmospheric
- preserves key headings
- removes unnecessary GM clutter
- keeps player-safe boundaries if requested

---

## /name-list

Generate names matching the campaign’s tone.

Specify category if possible:
- frontier settler
- expedition member
- guild operative
- Auric Dominion name
- ruin name
- settlement name

Default output:
10 options with short tonal notes.