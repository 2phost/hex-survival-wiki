---
title: "User Interface and Navigation"
---

# Mechanism: [[Mechanisms/user_interface|User Interface]] and Navigation

The UI of Hex Survival is designed to provide maximum information with minimal clutter, using a context-sensitive approach to player actions.

## Main Navigation (Bottom Bar)
The primary interface for player actions is located at the bottom of the screen:
- **Scavenge**: Accesses the map and current hex interaction tools.
- **Inventory & Recipes**: Upgraded UI for managing carried items and equipment. This now includes the **Recipe Book View**, a dedicated space for viewing all known crafting combinations. The panel has been redesigned with **4 rows** to accommodate larger backpack capacities.
- **[[Skills/index|Skills]]**: Opens the permanent progression menu.
- **Chat**: Communication with other survivors. Opens in the **bottom right** and includes clickable tile and item links.

## Inventory & Logistics
- **Relocated Actions**: To improve the flow of material management, the **Deposit**, **Deliver** (via drone), and **Drop-All** actions have been moved to more accessible positions within the inventory and town interaction panels.
- **Recipe Book UX**: Each row in the Recipe Book has been enhanced with new icons and a refined layout to make identifying requirements easier at a glance.
- **Town Resource UI**: Adjusted to display a wider variety of shared town assets and materials.
- **Base Management UI**: Enhanced layout for managing the Town Bank and construction projects.
- **Cargo Drone Panel**: A dedicated interface that allows players to select items and send them back to the base from the field.
- **Upgrade Readability**: The Base Upgrade menu features improved spacing, vertical resource scrolling, clearer cost labels, and explicit build-effect descriptions. Upgrade rows have been redesigned with increased height and proper item names.
- **Tooltips**: Improved base panel tooltips that remain visible and stable while moving the pointer over items.


## Suggestions & Feedback Panel
Players can contribute to game development through the suggestions panel.
- **Backlog**: Features a right-hand backlog column to track the status of proposed features.
- **Persistence**: Backlog status and position are persisted across sessions.

## Dynamic Action System
The UI is context-sensitive. Specific buttons and actions unlock based on:
- **Location**: Unique options appear at the **[[Base/overview|Base]]** or specialized facilities.
- **Requirements**: Specific items (like **[[Items/power_pole|Power Poles]]**) or skills (like **[[Skills/field_engineering|Field Engineering]]**) reveal new interactions.
- **Combat**: The **Attack Monsters** action appears when occupying a hex with a monster horde.

## Visual Handling
- **Tile Overlays**: Improved handling for overflowing tile icons (e.g., large piles of loot or multiple monsters) to prevent visual bleeding into adjacent hexes.
- **Monster Map Readability**: Monster markers feature increased texture size and reliable rendering. The UI prevents marker/count overlap with player icons, ensuring clear visibility during sieges.
