---
title: "Combat & Defense"
---

# Mechanism: [[Mechanisms/combat_and_defense|Combat & Defense]]

Introduced in the March 9, 2026 "Monster Siege" update, combat is the active process of thinning out monster hordes to prevent them from overrunning the town.

## ⚔️ Player Combat: The Armory
Players can engage monsters by moving onto a hex containing a horde and selecting the **Attack Monsters** action.

### The Combat Formula
- **Damage to Kills**: 1 point of Weapon Damage = 1 Monster Kill.
- **Extra Kills**: Skills like **[[Skills/sweeping_strikes|Sweeping Strikes]]** and **[[Skills/critical_hits|Critical Hits]]** provide chances to kill additional monsters beyond the base weapon damage.
- **Weapon Durability**: Every attack triggers a roll against the weapon's **Break Chance**. If the roll fails, the weapon is destroyed.

### Weapon Comparison
| Weapon | Damage | Break % | Requirement |
| :--- | :---: | :---: | :--- |
| <span style="white-space: nowrap;"><img src="../assets/items/plasma_lance.png" width="20" style="vertical-align: middle; margin-right: 4px;">&nbsp;[[Items/plasma_lance|Plasma&nbsp;Lance]]</span> | **6** | **8%** | None |
| <span style="white-space: nowrap;"><img src="../assets/items/shock_maul.png" width="20" style="vertical-align: middle; margin-right: 4px;">&nbsp;[[Items/shock_maul|Shock&nbsp;Maul]]</span> | **4** | **14%** | None |
| <span style="white-space: nowrap;"><img src="../assets/items/alloy_plate.png" width="20" style="vertical-align: middle; margin-right: 4px;">&nbsp;[[Items/alloy_plate|Alloy&nbsp;Plate]]</span> | **3** | **12%** | Field Engineering Lvl 1 |
| <span style="white-space: nowrap;"><img src="../assets/items/rebar_blade.png" width="20" style="vertical-align: middle; margin-right: 4px;">&nbsp;[[Items/rebar_blade|Rebar&nbsp;Blade]]</span> | **3** | **20%** | None |
| <span style="white-space: nowrap;"><img src="../assets/items/burnt_motor.png" width="20" style="vertical-align: middle; margin-right: 4px;">&nbsp;[[Items/burnt_motor|Burnt-Out&nbsp;Motor]]</span> | **2** | **22%** | None |
| <span style="white-space: nowrap;"><img src="../assets/items/scrap_spear.png" width="20" style="vertical-align: middle; margin-right: 4px;">&nbsp;[[Items/scrap_spear|Scrap&nbsp;Spear]]</span> | **2** | **28%** | None |
| <span style="white-space: nowrap;"><img src="../assets/items/makeshift_shiv.png" width="20" style="vertical-align: middle; margin-right: 4px;">&nbsp;[[Items/makeshift_shiv|Makeshift&nbsp;Shiv]]</span> | **1** | **40%** | None |
| <span style="white-space: nowrap;"><img src="../assets/items/rusty_tool.png" width="20" style="vertical-align: middle; margin-right: 4px;">&nbsp;[[Items/rusty_tool|Rusty&nbsp;Tool]]</span> | **1** | **35%** | None |

---

## 🛡️ Town Defense: The Siege
When a horde reaches the **[[Base/overview|Base]]** tile at **[[Mechanisms/midnight_cycle|Midnight]]**, it triggers a Town Siege.

### Defense Strength
Town Defense is the sum of all defensive base upgrades. If **Attack Strength (Horde Count) > Town Defense**, the town is overrun.

| Upgrade | Defense Bonus | Special Effect |
| :--- | :---: | :--- |
| **[[Base/constructions#BarbedWirePerimeter|Barbed Wire]]** | **+1** | Slows enemy movement by 1 hex |
| **[[Base/constructions#ReinforcedSteelBulkhead|Reinforced Bulkhead]]** | **+3** | Blocks breaches for 2 turns |
| **[[Base/constructions#AutomatedSentry|Automated Sentry]]** | **+5** | Fires 10 ammo per night |

---

## 🏋️ Combat Specializations
To become an effective defender, survivors should focus on the combat skill branch:
1. **[[Skills/weapon_maintenance|Weapon Maintenance]]**: Reduces the base break chance of your armory.
2. **[[Skills/sweeping_strikes|Sweeping Strikes]]**: Grants a chance to kill 1 extra monster per swing.
3. **[[Skills/critical_hits|Critical Hits]]**: Grants a small chance to kill 3 monsters in a single hit.

## 💡 Tactical Advice
- **Patrol Approach Paths**: Don't wait for hordes to reach the base. Intercept them while they are in the **Marching** phase to reduce the total Attack Strength before Midnight.
- **Clear Corrupted Zones**: The most effective defense is preventing spawns. Use high-AP scouts to locate and clear **[[Biomes/corrupted_1|Corrupted Tiles]]** near the base.
