# Abandoned Archive Relic Descriptions Mod

## Overview

Adds additional details to relic tooltips to clarify their stat effects and mechanics. This mod enhances relic descriptions with exact values, formulas, and specific stat information that aren't shown in the base game descriptions.

## Screenshot

<img width="319" height="223" alt="image" src="https://github.com/user-attachments/assets/c71a99b2-6325-4558-a8a8-3e7a314db78c" /> <img width="339" height="206" alt="image" src="https://github.com/user-attachments/assets/6f51f399-0807-4227-a565-3502250cb8ed" />

## Features

- **Enhanced tooltips** - Adds precise stat values and formulas to relic descriptions
- **Dynamic information** - Shows current values for relics that scale (like knowledge-based damage)
- **Clarified mechanics** - Explains conversion formulas and hidden penalties
- **Better decision making** - Helps players understand exactly what each relic does

## Affected Relics

This mod enhances the descriptions of the following relics:

### Clockwork Boots (FasterRollRelic)
**Added Description:**
- "+0.5x roll speed modifier (33% faster rolling)"

### Unfinished Tome (KnowledgeDamageBoostRelic)
**Added Description:**
- Shows current knowledge value
- Shows current damage multiplier percentage
- Format: "Current Knowledge: {value}\nDamage Multiplier: +{X.X}%"

### Ring of Chaos / Emerald Sword (DamageBoostRelic)
**Added Description:**
- "+33% spell damage multiplier"
- "Cooldown penalty: -12% cooldown speed for 6 seconds after casting"

### Ship in a Bottle (ShipInABottle)
**Added Description:**
- "Reduces collider size by 1.5x (33% smaller)"

### Miniature Rapiers (KillBoostRelic)
**Added Description:**
- "Per kill: +0.1x speed, +10% damage, +10% knowledge gain"
- "Duration: 3 seconds (stacks)"

### Damage Buff Relic (DamageBuffRelic)
**Added Description:**
- "+25% damage to enemies within 1.5 units"

### Room Knowledge Relic (RoomKnowledgeRelic)
**Added Description:**
- "Grants 2 knowledge when completing rooms"

## Installation

1. Place the relic descriptions mod folder with the dll in your `BepInEx/plugins` folder
2. Launch the game - enhanced descriptions will appear automatically when hovering over those relics

## Notes

- Descriptions are added dynamically when viewing relic tooltips
- The mod uses Harmony patches to enhance tooltip text without modifying game files
- No one will read this and know that I made this simply because I wanted to min-max the damage of my spells while taking unfinished tomes knowledge scaling into account. And know what the heck ship in a bottle actually does.
