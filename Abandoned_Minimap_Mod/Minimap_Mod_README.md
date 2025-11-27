# Abandoned Archive Minimap Mod

## Overview

This mod adds a real-time minimap to the Abandoned Archive game, displaying the dungeon layout, room connections, and important room information. The minimap updates dynamically as you explore, showing your current location, discovered rooms, and available pickups.

## Features

- **Real-time minimap** showing dungeon layout and colored room details
- **Fog of war** - rooms are hidden until discovered by entering them or adjacent rooms
- **Toggle visibility** - show/hide the minimap at any time

## How to Use

### Minimap Location
The minimap appears in the top-left corner of the screen, below the knowledge/buffs Status UI.

### Toggle Minimap
- Press **Tab** or **M** to toggle the minimap on/off

## Room Colors

The minimap uses different colors to indicate room types and states. Colors are prioritized in the following order (highest to lowest):

### 🔴 Red - Current Room
The room you are currently in. Updates in real-time as you move between rooms.

### 🟡 Yellow - Unlooted Relic Bookshelf
A room containing an unlooted relic bookshelf. The room turns white after you collect the relic.

### 🟢 Green - Unused Health Pickup
A room containing an unused health pickup. Updates dynamically if the pickup is pushed to another room.

### 🔵 Blue - Visited Room (Cleared)
A room you have visited and cleared. A room is marked as cleared if you spent 3+ seconds in it and then left.

### ⚪ White - Normal Room
A normal, unexplored room that has been discovered but has no special properties.

## Fog of War
- Adjacent rooms are made visible.

## Known Issues

- The minimap guesses the closest room for health pickup locations but can be wrong.
- Connections between rooms are guesses and will be wrong. (random lines to rooms that aren't connected)
- (Visual bug) Sometimes you might need to revisit a white room for a few seconds and leave again if it didn't update to blue when you left.

- I slapped this together with Cursor in like an hour so it sucks, do not view the code.
- Pray vedal adds a good minimap in updates or a dedicated modder makes a better mod.

## Installation

1. Place the compiled `Abandoned_Minimap_Mod.dll` in your `BepInEx/plugins` folder
2. Launch the game - the minimap will appear automatically when you start a run

## Notes

- The minimap won't appear on the main menu (there's no map... why would it?)
- There are no keybind settings for the minimap - WHY NOY? (I'm lazy)
- No one will read this and know that I stole the minimap idea from kokonuts 
