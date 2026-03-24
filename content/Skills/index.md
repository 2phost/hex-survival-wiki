---
title: "Skills"
---

# Skill: [[Skills/index|Index]]

Skills are permanent character specializations that progress in real-time. Training a skill does not consume AP.

## 🔗 Skill Dependencies
```mermaid
graph LR
 subgraph S[Survival]
  AP[AP Capacity]
  SC[Stim Conditioning]
  RR[Rest Recovery]
  PR[Preparedness]
  MF[Mental Fortitude]
 end

 subgraph L[Logistics]
  SE[Scavenger's Eye]
  PM[Pack Mule]
  SL[Salvage]
 end

 subgraph C[Combat]
  WM[Weapon Maintenance]
  SS[Sweeping Strikes]
  CH[Critical Hits]
 end

 subgraph E[Engineering]
  FE[Field Engineering]
  GO[Generator Operations]
  DO[Drone Operator]
  PI[Power Infrastructure]
 end

 subgraph EX[Exploration]
  EI[Eidetic Memory]
 end

 AP -->|Lvl 1| SE
 AP -->|Lvl 1| PM
 AP -->|Lvl 1| SC
 AP -->|Lvl 1| WM
 AP -->|Lvl 1| EI
 AP -->|Lvl 1| MF
 AP -->|Lvl 2| RR
 
 SE -->|Lvl 1| SL
 SE -->|Lvl 2| FE
 
 FE -->|Lvl 1| GO
 FE -->|Lvl 1| DO
 FE -->|Lvl 1| PI

 click AP "/Skills/ap_capacity"
 click RR "/Skills/rest_recovery"
 click SC "/Skills/stim_conditioning"
 click PR "/Skills/preparedness"
 click MF "/Skills/mental_fortitude"
 click SE "/Skills/scavenger_eye"
 click PM "/Skills/pack_mule"
 click SL "/Skills/salvage"
 click FE "/Skills/field_engineering"
 click GO "/Skills/generator_operations"
 click DO "/Skills/drone_operator"
 click PI "/Skills/power_infrastructure"
 click EI "/Skills/eidetic_memory"
 click WM "/Skills/weapon_maintenance"
 click SS "/Skills/sweeping_strikes"
 click CH "/Skills/critical_hits"
```

## 🩸 Survival Skills
Primary skills for basic existence and movement.

| Skill | Effect |
| :--- | :--- |
| **[[Skills/ap_capacity|AP Capacity]]** | Increases max Action Points (+1 per level). |
| **[[Skills/preparedness|Preparedness]]** | Start with gear based on level. |
| **[[Skills/mental_fortitude|Mental Fortitude]]** | Increases maximum Fear cap. |
| **[[Skills/rest_recovery|Rest Recovery]]** | Chance for +1 extra AP per hourly rest. |
| **[[Skills/stim_conditioning|Stim Conditioning]]** | Unlock the use of high-tier AP Stims. |

## 👁️ Exploration Skills
Skills that improve awareness and navigation.

| Skill | Effect |
| :--- | :--- |
| **[[Skills/eidetic_memory|Eidetic Memory]]** | Retain visibility of previously explored tiles. |

## 🔍 Scavenging & Logistics
Skills that improve resource acquisition and inventory.

| Skill | Effect |
| :--- | :--- |
| **[[Skills/scavenger_eye|Scavenger's Eye]]** | Increases loot success chance (+5% per level). |
| **[[Skills/pack_mule|Pack Mule]]** | Increases carried inventory slots (+1 per level). |
| **[[Skills/salvage|Salvage]]** | Enables deconstruction and improves resource yield. |

## ⚔️ Combat & Defense
Specializations for fighting monster hordes.

| Skill | Effect |
| :--- | :--- |
| **[[Skills/weapon_maintenance|Weapon Maintenance]]** | Reduces weapon break chance (-2% per level). |
| **[[Skills/sweeping_strikes|Sweeping Strikes]]** | Chance to kill 1 extra monster (5% per level). |
| **[[Skills/critical_hits|Critical Hits]]** | Chance for critical hit (kill 3 monsters). |

## 🏗️ Engineering & Operations
Advanced skills for town maintenance and facility fabrication.

| Skill | Effect |
| :--- | :--- |
| **[[Skills/field_engineering|Field Engineering]]** | Unlock fabrication in Industrial/Electronic biomes. |
| **[[Skills/generator_operations|Generator Operations]]** | Safely run/refuel town generators. |
| **[[Skills/drone_operator|Drone Operator]]** | Unlocks use of autonomous cargo drones. |
| **[[Skills/power_infrastructure|Power Infrastructure]]** | Deploy and manage field power networks. |

## ⏳ Training Times
Training times are fixed real-world intervals.
- **Level 1**: 1 Hour
- **Level 2**: 24 Hours
- **Level 3**: 7 Days
- **Level 4**: 14 Days
- **Level 5**: 30 Days
