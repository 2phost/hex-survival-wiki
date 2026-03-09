---
title: "Monster Hordes"
---

# Mechanism: [[Mechanisms/monster_hordes|Monster Hordes]]

![[assets/players/monster.png|150]]

The Monster Horde system, introduced on March 9, 2026, represents the primary external threat to the town. Corrupted tiles now serve as spawning grounds for organized threats that march toward the base.

## 1. The Horde Life Cycle

### Phase 1: Spawning
Every **[[Mechanisms/midnight_cycle|Midnight]]**, corrupted tiles have a chance to spawn a new monster horde. 

### Phase 2: Gathering
Newly spawned hordes spend their first night in the **Gathering** phase. During this time, they remain stationary on the corrupted tile and do not move.

### Phase 3: Marching
After the gathering phase, the horde enters the **Marching** phase. At every subsequent **[[Mechanisms/midnight_cycle|Midnight]]**, the horde moves **one hex closer** to the town base.

## 2. World Impact & Damage
Hordes are not just a threat to players; they actively degrade the environment as they advance.
- **Loot Consumption**: If a horde steps onto a hex, they consume all ground loot currently present on that tile.
- **Infrastructure Destruction**: Hordes will destroy any built **[[Items/power_pole|Power Poles]]** on a tile they enter, severing town power lines.

## 3. Combat & Defense

### Attacking Monsters
Players can engage hordes by moving onto their hex and selecting the **Attack Monsters** action.
- **Weapon Damage**: Each point of weapon damage converts directly into 1 monster kill.
- **Weapon Durability**: Weapons have a chance to break with each use.
- **AP Cost**: (Testing) Confirm the AP cost for the "Attack Monsters" action.

### Town Sieges
If a horde reaches the **[[Base/overview|Base]]** tile, it contributes its total count to the nightly **Attack Strength**.
- **The Defense Check**: If **Attack Strength > Town Defense**, the town is overrun and the instance ends.
- **Defense Bonuses**: Town defense is increased by building upgrades like **[[Base/constructions|Barbed Wire]]**, **[[Base/constructions|Reinforced Bulkheads]]**, and **[[Base/constructions|Sentry Turrets]]**.

## 4. Escalation
The threat level is not static. A global **Spawn Bonus** increases every night, meaning that hordes spawned later in the game will be significantly larger than those encountered in the early days.

## 5. UI & Scouting
- **Tactical Markers**: The map displays monster markers with stacked counts per hex.
- **Phase Info**: Server state includes whether a horde is "Gathering" or "Marching," allowing players to prioritize threats.
- **Strategic Advice**: Clear nearby corrupted zones early to prevent hordes from forming close to the base.
