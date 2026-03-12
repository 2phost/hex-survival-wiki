---
title: "Light and Darkness"
---

# Mechanism: Light and Darkness

## [[Mechanisms/light_and_darkness|The Darkness]] Threat
Darkness is the primary existential threat in Hex Survival.
- **Fear**: Entering dark tiles without a lamp increases the player's **[[Vitals/fear|Fear]]** stat.
- **Individual Death**: Moving into unlit hexes without a lamp results in immediate death.
- **Global Game Over**: If the city's critical systems fail and the entire town falls into darkness, **everyone dies and the run is over.**
- **City Survival**: The city only survives as long as it has light. Preventing darkness from taking over is the ultimate objective.

## Light Sources
Players must manage light to safely navigate the map.
- **Personal Light**: [[Items/index|Items]] like the "[[Items/starter_lamp|Starter Lamp]]" provide a mobile radius of safety but have limited duration.
- **Grid Illumination**: **[[Items/power_pole|Power Poles]]** can be placed to permanently illuminate a hex. This requires the hex to be connected to the town's power chain.
- **Radius**: A powered pole illuminates only its **current hex (0-hex radius)**.
- **Hex Light**: The Base has inherent light.

## Duration and Maintenance
- **Degradation**: Light sources like the [[Items/starter_lamp|Starter Lamp]] have a limited lifespan (e.g., "1 day of light remaining").
- **[[Mechanisms/power_grid|Midnight]] Expiration**: Mobile light sources (lamps) degrade at the [[Mechanisms/power_grid|Midnight]] transition. 
- **The "Day Change" Trap**: If a lamp has only "1 day remaining" and the player is standing in an unlit hex during the [[Mechanisms/midnight_cycle|Midnight]] transition, the lamp expires. Without light, the player will begin accumulating **[[Vitals/fear|Fear]]** each hour. If this meter reaches its 3-bar maximum, the player is **"Consumed by Darkness."**
- **Refueling**: [[Items/index|Items]] like the "Empty Lamp" require a "Battery" to be crafted into a functional light source.
