# Mechanism: [[mechanisms/player_status|Player Status]] and Vitals

## Vitals
The player must manage several primary status bars to survive:
1. **[[mechanisms/hunger|Hunger]]**: Replenished by food/rations. **Drains significantly at [[Midnight]].**
2. **[[mechanisms/thirst|Thirst]]**: Replenished by fresh drinking water. **Drains significantly at [[Midnight]].**
3. **Health**: Managed by finding **Medicine** and recovery items. 
4. **[[mechanisms/action_points|Action Points]] ([[mechanisms/action_points|AP]])**: Currency for performing active tasks on the map.
5. **Activity Status**: Displays current state (Resting, [[mechanisms/scavenging|Scavenging]]).

## The [[Midnight]] Transition
Survival vitals (**[[mechanisms/hunger|Hunger]]** and **[[mechanisms/thirst|Thirst]]**) are deducted at the **[[Midnight]]** cycle, creating a daily "survival check" where the player must have enough resources to survive the transition. 
- **The "Midnight Toll"**: Both **[[mechanisms/hunger|Hunger]] and [[mechanisms/thirst|Thirst]] drain by 40%** (4 out of 10 bars) during the transition from Day 3 to Day 4 (and likely every midnight).
- **Lamps**: Standing in an unlit hex during the midnight transition when a lamp expires results in **instant death.**
- **Town Power**: The city's energy reserve also drains at this point.

## Activity Types
- **Resting**: The default state when not performing other tasks. Restores **1 [[mechanisms/action_points|AP]] per hour**.
- **[[mechanisms/scavenging|Scavenging]]**: The act of searching a hex for resources. 
    - **[[mechanisms/action_points|AP]] Cost**: **0 [[mechanisms/action_points|AP]]** for scavenging. Starting and stopping the activity is free.
    - **Recovery**: [[mechanisms/action_points|AP]] regeneration is **paused** while scavenging.
    - **Loot**: [[mechanisms/items|Items]] are discovered at hourly intervals based on a percentage roll.

## [[mechanisms/skills|Skill Training]]
- **Cost**: **0 [[mechanisms/action_points|AP]]** to start or pause training.
- **Duration**: Real-time progression:
    - **Level 1**: 1 Hour
    - **Level 2**: 24 Hours (1 Day)
    - **Level 3**: 7 Days
    - **Level 4**: 14 Days
    - **Level 5**: 30 Days
