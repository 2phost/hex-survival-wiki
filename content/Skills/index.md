---
title: "Skills"
---

# Hex Survival Skills

Skills represent your survivor's long-term specialization. Training takes real-time and persists between town instances.

## Skill Progression
Training costs **0 AP** but requires significant actual time to complete.

| Level | Duration |
| :--- | :--- |
| **Level 1** | 1 Hour |
| **Level 2** | 24 Hours (1 Day) |
| **Level 3** | 7 Days |
| **Level 4** | 14 Days |
| **Level 5** | 30 Days |

## Dependency Tree
```mermaid
graph TD
    AP[AP Capacity] -->|Lvl 1| PM[Pack Mule]
    AP -->|Lvl 1| SE[Scavenger's Eye]
    AP -->|Lvl 1| SC[Stim Conditioning]
    AP -->|Lvl 2| RR[Rest Recovery]
    
    SE -->|Lvl 1| SL[Salvage]
    SE -->|Lvl 2| FE[Field Engineering]
    
    FE -->|Lvl 1| GO[Generator Operations]

    classDef default fill:#2d2d2d,stroke:#666,stroke-width:2px,color:#fff;
    classDef highlight fill:#4a4a4a,stroke:#fff,stroke-width:2px,color:#fff;
    class AP highlight;
```

## Skill Directory

### [[Skills/ap_capacity|AP Capacity]]
Increases your maximum Action Point pool.

### [[Skills/rest_recovery|Rest Recovery]]
Provides a chance for bonus AP while resting.

### [[Skills/scavenger_eye|Scavenger's Eye]]
Increases the hourly success rate of scavenging.

### [[Skills/pack_mule|Pack Mule]]
Expands your personal inventory capacity.

### [[Skills/field_engineering|Field Engineering]]
Unlocks production in industrial facilities.

### [[Skills/generator_operations|Generator Operations]]
Required for refueling town power generators.

### [[Skills/stim_conditioning|Stim Conditioning]]
Allows the safe use of high-tier stimulants.

### [[Skills/salvage|Salvage]]
Unlocks the ability to deconstruct items for materials.
