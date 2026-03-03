# Mechanism: [[mechanisms/player_status|Player Status]] and Vitals

## Vitals
The player must manage several primary status bars to survive:
1. **Hunger**: Replenished by food/rations. **Drains significantly at [[Midnight]].**
2. **Thirst**: Replenished by fresh drinking water. **Drains significantly at [[Midnight]].**
3. **Health**: Managed by finding **Medicine** and recovery items. 
4. **[[mechanisms/action_points|Action Points]] ([[mechanisms/action_points|AP]])**: Currency for performing active tasks on the map.
5. **Activity Status**: Displays current state (Resting, [[mechanisms/scavenging|Scavenging]]).

## The [[Midnight]] Transition
Survival vitals ([[Hunger]] and [[Thirst]]) are likely deducted at the **[[Midnight]]** cycle, creating a daily "survival check" where the player must have enough resources to survive the transition. 
- **Lamps**: Standing in an unlit hex during the midnight transition when a lamp expires results in **instant death.**
- **Town Power**: The city's energy reserve also drains at this point.

## Activity Types
- **Resting**: The default state when not performing other tasks. Restores **1 [[mechanisms/action_points|AP]] per hour**.
- **[[mechanisms/scavenging|Scavenging]]**: The act of searching a hex for resources. 
    - **[[mechanisms/action_points|AP]] Cost**: **0 [[mechanisms/action_points|AP]]** to start or stop. The activity itself does **not** drain [[mechanisms/action_points|AP]] over time.
    - **Recovery**: [[mechanisms/action_points|AP]] regeneration is **paused** while scavenging; you cannot rest and scavenge simultaneously.
    - **Loot**: [[mechanisms/items|Items]] are discovered at hourly intervals based on a percentage roll.

## [[mechanisms/skills|Skill Training]]
- **Cost**: **0 [[mechanisms/action_points|AP]]** to start or pause training.
- **Duration**: Real-time progression (Lvl 1 = 1h, Lvl 2 = 24h, Lvl 3 = 7d, Lvl 4 = 14d, Lvl 5 = 30d).
