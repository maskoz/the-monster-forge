# Changelog — The Monster Forge

All notable changes to this project will be documented here.

---

## [1.0.0] — 2026-02-24

### Initial Release

**Core Features**
- Six NPC roles: Brute, Soldier, Skirmisher, Artillery, Controller, Support
- Full Shadowdark Quick Combat Statistics baseline (AC, HP, ATK, DC) from level 0–19 and Legendary Boss (30)
- Role-appropriate ability score distribution with stat range clamping
- HP variance scaling by level tier
- Soldier AC +2 bonus
- Role-filtered weapon pools — melee and ranged per role
- Support role guaranteed melee + offensive divine + healing attacks
- Compendium-aware table lookup (searches module compendium first, falls back to world tables)
- Self-contained — no template actor required

**Villain Action System (Matt Colville-inspired)**
- Three-round action card: Setup → Twist → Ultimate
- Phase-tagged table entries ensure correct round assignment
- Universal on-hit rider drawn from Damage Rider, Movement Trick, or Battlefield Control tables
- Bloodied escalations on every ability (triggers at half HP)
- All effects use Close/Near/Far ranges — no saves, no attack rolls on spice effects

**Tables — 15 total, 300 entries**
- 6 Role Malice tables (Brute, Soldier, Skirmisher, Artillery, Controller, Support) — 20 entries each
- 3 Universal tables (Damage Rider, Movement Trick, Battlefield Control) — 20 entries each
- 6 Role Flavor tables — 20 role-specific physical descriptions each

**Name Generator**
- Syllable-based name pools per role flavor
- Auto-generates when name field is left blank
- Supports batch generation (1–10 NPCs)
- Named NPCs get numbered suffixes in batch mode (Guard 1, Guard 2...)
- Name field auto-disables when count > 1

**Output**
- Clean HTML description tab with version tracking
- Flavor text in italics at top
- Baseline stats block
- Villain action card with bloodied effects in dark red
- GM whisper chat card summary
- Version number stamped on every generated NPC
