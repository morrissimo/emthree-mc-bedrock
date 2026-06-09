# Power System

UC machines require power from generators. No cables needed at basic tier — power transfers by adjacency.

## Adjacency Rules

Generators tag all **6 cardinal faces** (N/S/E/W/up/down) on placement. Any machine touching any of those faces receives power. A generator can sit above, below, or beside a machine.

## Transfer Modes

Right-click a generator to cycle between:

| Mode | Behavior |
|------|----------|
| **Nearest** (default) | Sends power to closest connected machine first |
| **Farthest** | Sends power to farthest connected machine first |
| **Round** | Distributes evenly across all connected machines |

## Generator Upgrade Pattern (UC Workbench)

All tier upgrades follow this shape:

```
A E A
E B E
C D C
```

`B` = previous-tier machine, `E` = tier's chip, `A`/`C`/`D` = tier-specific materials.

| Tier | Chip | Extra materials |
|------|------|-----------------|
| basic | basic_chip | steel_ingot, iron_ingot, redstone_block |
| advanced | advanced_chip | steel_plate, energized_iron_plate, redstone_block |
| expert | expert_chip | steel_plate, diamond_dust, redstone_block |
| ultimate | ultimate_chip | steel_plate, netherite_plate, redstone_block |

## Generator Types

| Generator | Fuel / Mechanic | Notes |
|-----------|-----------------|-------|
| **Furnator** | Solid fuel (coal, wood, etc.) | Blast furnace in base recipe |
| **Solar Panel** | Daylight only; stops at night | Gold_ingot instead of blast_furnace |
| **Magmator** | Lava (fluid tank required) | basic_fluid_tank + gold_plate + furnace |
| **Thermo Generator** | Temperature differential (lava + ice nearby) | basic_fluid_tank + copper_block + plates |
| **Wind Turbine** | Passive; output scales with height | fan + machine_case in base recipe |

## Energy Storage & Transfer

- **Batteries** — store energy (basic/advanced/expert/ultimate tiers)
- **Transmitters** — send power over distance (beyond adjacency range)
- **Receivers** — receive power from transmitters
