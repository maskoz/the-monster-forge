# ⚒ The Monster Forge

**A Shadowdark NPC generator for Foundry VTT**

The Monster Forge instantly creates action-oriented NPCs with role-based stats, three-round villain action cards, bloodied escalations, creature flavor text, and auto-generated names — all from a single macro dialog.

Designed for **Shadowdark RPG** by Arcane Library. Inspired by Matt Colville's Action-Oriented Monsters and the Dungeon Coach Monster Playbook.

---

## Features

- **6 NPC Roles** — Brute, Soldier, Skirmisher, Artillery, Controller, Support
- **Shadowdark Quick Combat Statistics** — AC, HP, ATK, and DC pulled directly from the official baseline chart
- **Three-Round Villain Action Card** — Setup → Twist → Ultimate, drawn from phase-tagged tables
- **Bloodied Escalations** — every ability has a half-HP escalation that changes the fight
- **No rolls, no saves on spice effects** — effects just happen, keeping combat fast
- **Close / Near / Far ranges** — pure Shadowdark language throughout
- **Creature Flavor Text** — role-specific physical descriptions, 20 per role
- **Auto-Generated Names** — role-flavored syllable combinations
- **Batch Generation** — forge 1–10 NPCs at once
- **Self-Contained** — no template actor required, works out of the box

---

## Installation

### Method 1 — Foundry Module Manager (recommended)
1. Open Foundry VTT → **Add-on Modules** → **Install Module**
2. Paste the manifest URL:
   ```
   https://raw.githubusercontent.com/maskoz/the-monster-forge/main/module.json
   ```
3. Click **Install**
4. Enable the module in your world

### Method 2 — Manual
1. Download the latest release zip from the [Releases page](https://github.com/maskoz/the-monster-forge/releases)
2. Extract into your Foundry `Data/modules/` folder
3. Enable the module in your world

---

## Usage

1. Open the **Monster Forge Macros** compendium
2. Import **The Monster Forge** macro into your world
3. Click the macro to open the dialog
4. Choose a level, role (or Random), and how many to generate
5. Leave the name blank for auto-generated names
6. Click **Forge It**

The NPC appears in your Actors directory. Open the **Description** tab for the full stat block and villain action card.

---

## The Tables

The **Action Monsters** compendium contains 15 roll tables:

| Table | Entries | Purpose |
|-------|---------|---------|
| Brute: Malice | 20 | Villain actions for Brute role |
| Soldier: Malice | 20 | Villain actions for Soldier role |
| Skirmisher: Malice | 20 | Villain actions for Skirmisher role |
| Artillery: Malice | 20 | Villain actions for Artillery role |
| Controller: Malice | 20 | Villain actions for Controller role |
| Support: Malice | 20 | Villain actions for Support role |
| Universal: Damage Rider | 20 | On-hit effects |
| Universal: Movement Trick | 20 | Movement-based villain actions |
| Universal: Battlefield Control | 20 | Zone and control effects |
| Brute: Flavor | 20 | Physical descriptions |
| Soldier: Flavor | 20 | Physical descriptions |
| Skirmisher: Flavor | 20 | Physical descriptions |
| Artillery: Flavor | 20 | Physical descriptions |
| Controller: Flavor | 20 | Physical descriptions |
| Support: Flavor | 20 | Physical descriptions |

**300 total unique entries.**

---

## Compatibility

- **System**: Shadowdark RPG
- **Foundry VTT**: v12–v13
- **Verified**: v13.351, Shadowdark system v3.6.2

---

## Credits

- **Design & Development**: maskoz (Lee McKinney)
- **Inspired by**: Matt Colville's [Action-Oriented Monsters](https://www.youtube.com/watch?v=y_zl8WWaSyI) and the Dungeon Coach Monster Playbook
- **Built for**: Shadowdark RPG by Kelsey Dionne / [Arcane Library](https://www.thearcanelibrary.com)

*The Monster Forge is an independent, fan-made tool. It is not affiliated with or endorsed by Arcane Library.*

---

## License

See [LICENSE.md](LICENSE.md)
