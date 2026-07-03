# Power System

This page covers how power **moves and is stored** — adjacency, transfer modes, cables, and
batteries. For the generators themselves (types, recipes, and energy output), see the
**[Generators](generators.md)** page.

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

## Generators

UC has five generator families — **Magmator** (lava), **Furnator** (solid fuel), **Solar Panel**
(daylight), **Thermo Generator** (heat block + water), and **Wind Turbine** (altitude/weather). Each
one's mechanic, crafting recipe, tiers, and **energy output** lives on the **[Generators](generators.md)**
page. However you power a base, they all feed machines through the adjacency + transfer rules above
(and the optional cables below).

## Energy Storage & Transfer

- **Energy cables** (`utilitycraft:energy_cable`) — carry power from a generator to non-adjacent machines (wired, optional at every tier).
- **Batteries** — store/buffer energy (basic/advanced/expert/ultimate tiers).
- **Transmitters / Receivers** — **wireless** energy links. They're the *same* block toggled between transmit/receive with a **wrench**; transfer is **range-limited** (32 blocks at basic tier) and only works between blocks on a **matching color-channel network** (set via the sneaking-wrench "Basic Network" menu). Not unlimited distance.
