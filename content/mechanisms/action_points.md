# Mechanism: [[mechanisms/action_points|Action Points]] ([[mechanisms/action_points|AP]])

## Description
[[mechanisms/action_points|Action Points]] ([[mechanisms/action_points|AP]]) are the primary currency for performing specific tasks on the map. It is displayed as one of the four main status bars.

## Usage
- **Disabling Threats**: Specific quest actions (e.g., disabling a Corrupted Relay) require a set amount of [[mechanisms/action_points|AP]] (e.g., 2 [[mechanisms/action_points|AP]]).
- **Movement**: Consumes **1 [[mechanisms/action_points|AP]] per hex**. This cost is uniform across all tile types (Desert, Mountain, etc.).
- **[[mechanisms/scavenging|Scavenging]]**: Does **not** consume [[mechanisms/action_points|AP]] over time; starting and stopping the activity is also free (0 [[mechanisms/action_points|AP]]).
- **Inventory & [[mechanisms/skills|Skills]]**: Opening the inventory, consuming items, or starting/pausing a skill consumes **0 [[mechanisms/action_points|AP]]**.
- **Restoration**: 
    - **Passive Regeneration**: While the player is in the **Resting** state (not scavenging), they restore **1 [[mechanisms/action_points|AP]] every hour** of real time.
    - **Skill Bonus**: The "Rest Recovery" skill provides a chance (10% per level) to gain an additional +1 [[mechanisms/action_points|AP]] during this hourly window.
    - **Consumables**: 
        - **Stim Packs**: Restored by Stim Packs (+2 AP), Stim Injectors (+4 AP), and Stim Overdrive (+6 AP).
        - **Food & Water**: **Rations, Clean Water, Salad, and Glowing Mushrooms** now restore **+1 AP** upon consumption.
- **[[mechanisms/action_points|AP]] Cap**: Any [[mechanisms/action_points|AP]] gained (e.g., from Stims) that exceeds the current maximum capacity is permanently lost.
