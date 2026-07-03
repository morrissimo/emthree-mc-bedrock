# Power System

UC machines require power from generators. Power transfers by **adjacency** — a generator feeds any
machine touching it — at *every* tier. **Energy cables** (`utilitycraft:energy_cable`, an optional
block) extend a generator's reach to machines that aren't directly adjacent; they're never required,
at any tier.

## Adjacency Rules

Generators tag all **6 cardinal faces** (N/S/E/W/up/down) on placement. Any machine touching any of those faces receives power. A generator can sit above, below, or beside a machine.

## Transfer Modes

**Use a wrench** (`utilitycraft:wrench`) on a generator to open its transfer-mode **dropdown** — a
plain right-click just opens the generator's container. Modes:

| Mode | Behavior |
|------|----------|
| **Nearest** (default) | Sends power to closest connected machine first |
| **Farthest** | Sends power to farthest connected machine first |
| **Round** | Distributes evenly across all connected machines |

## Generator Upgrade Pattern (UC Workbench)

The **Furnator, Solar Panel, and Wind Turbine** share this upgrade shape:

```
A E A
E B E
C D C
```

`E` = the tier's chip; `B` = the previous-tier machine — **except at basic tier**, where `B` is the
vanilla base block (a `blast_furnace` for the furnator, `gold_ingot` for the solar panel, etc.).
`A`/`C`/`D` = tier materials:

| Tier | Chip | Extra materials |
|------|------|-----------------|
| basic | basic_chip | steel_ingot, iron_ingot, redstone_block |
| advanced | advanced_chip | steel_plate, energized_iron_plate, redstone_block |
| expert | expert_chip | steel_plate, diamond_dust, redstone_block |
| ultimate | ultimate_chip | steel_plate, netherite_plate, redstone_block |

The **Magmator** and **Thermo Generator do NOT use this shape or material table** — they need fluid
tanks + their own plates (magmator: `GDG/EBE/SES` with gold plates; thermo: `ADA/EBE/CAC` with copper
block + plates). Check each in-game at the UC Workbench.

## Generator Types

| Generator | Fuel / Mechanic | Notes |
|-----------|-----------------|-------|
| **Furnator** | Solid fuel (coal, wood, etc.) | Blast furnace in base recipe |
| **Solar Panel** | Daylight only; stops at night | Gold_ingot instead of blast_furnace |
| **Magmator** | Lava — burned from the magmator's **own internal lava buffer** (fill by bucket or fluid pipe; no separate tank block underneath) | basic_fluid_tank + gold_plate + furnace |
| **Thermo Generator** | A **heat-source block directly below** (blaze block, lava, fire, magma, etc.) + **water** coolant in its own buffer — *not* lava, *not* ice | basic_fluid_tank + copper_block + plates |
| **Wind Turbine** | Passive; output scales with **altitude** and **weather** (clear 1× / rain 1.5× / thunder 2.25×) — no clearance-above requirement | fan + machine_case in base recipe |

## Energy Storage & Transfer

- **Energy cables** (`utilitycraft:energy_cable`) — carry power from a generator to non-adjacent machines (wired, optional at every tier).
- **Batteries** — store/buffer energy (basic/advanced/expert/ultimate tiers).
- **Transmitters / Receivers** — **wireless** energy links. They're the *same* block toggled between transmit/receive with a **wrench**; transfer is **range-limited** (32 blocks at basic tier) and only works between blocks on a **matching color-channel network** (set via the sneaking-wrench "Basic Network" menu). Not unlimited distance.
