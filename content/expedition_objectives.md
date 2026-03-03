# Mechanism: [[mechanisms/expedition_objectives|Expedition Objectives]]

## Overview
[[mechanisms/expedition_objectives|Expedition Objectives]] are time-sensitive tasks that provide rewards upon completion or penalties if ignored. 

### Navigation Logic
- **Relative Positioning**: Objective headings (e.g., SW) and distances (e.g., 2 hexes away) are **always relative to the player's current position**, not the Base. This means the heading will shift as the player moves.

## Current Objectives

### 1. Story Event: Rapid Prototype Request (Medium)
- **Context**: Effect Engineers request a live fabrication queue before assaulting the corrupted relay.
- **Goal**: Set production on any **powered** Industrial, Electronic, or Farm facility.
- **Reward**: +2 Research Material and +2 Scrap Metal in base stores at [[Midnight]].

### 2. Threat: Corrupted Relay (Lvl 1) (High)
- **Goal**: Reach the relay hex and spend **2 [[mechanisms/action_points|AP]]** to disable it.
- **Location**: Use the **[[Watchtower]]** to reveal. (Example: Heading SW, Distance 2 hexes away).
- **Penalty if Ignored**: 
    - **Immediate**: -12% Search Chance town-wide.
    - **Escalation**: -16% Search Chance at next [[Midnight]].

## Objective Types

### 1. Story & Infrastructure Events
- **Goal**: Perform specific base actions or use specialized facilities (e.g., [[Research Lab]], [[Industrial Facility]]) to progress the narrative or gain resources.
- **Reward**: Critical materials or navigation data.

### 2. Threat Mitigation
- **Goal**: Neutralize a specific threat on the map (e.g., Relays, Corrupted Nodes).
- **Penalty if Ignored**: Global negative effects that scale over time.
- **Requirements**:
    - **Navigation**: **Requires [[Watchtower]] to reveal headings.**
    - **Action**: Spend [[mechanisms/action_points|Action Points]] ([[mechanisms/action_points|AP]]) to perform a specific task (e.g., "Disable").
