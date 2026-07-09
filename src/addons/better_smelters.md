# Better Smelters

Tiered standalone furnaces, independent of the UC power system. Upgrading isn't *just* about speed —
higher tiers also burn **far less fuel per item**, and two tiers have special modes (a **fuel-free**
furnace and a **whole-stack batch smelter**). See the tier table before you commit to a path.

## Furnace tiers at a glance

Three things improve as you climb, not one:

| Furnace | Relative speed | Fuel / item (lower = better) | Special |
|---|---|---|---|
| Oak Wood | 1× | 1.0 | starter |
| Copper | 1.5× | 1.0 | |
| Iron | 2× | 1.0 | |
| **Netherrack** | 2× | **0 — no fuel, ever** | set-and-forget, never feed it |
| Gold | 3× | 0.8 | |
| Emerald | 5× | 0.6 | |
| Diamond | 10× | 0.4 | |
| Amethyst | 15× | 0.4 | faster branch off Emerald (see below) |
| Netherite | 20× | 0.2 | |
| Blazing | 25× | 0.1 | ~10× less fuel than Iron |
| **Nether Star** | 10× | 0.01 | **smelts a whole input stack in one operation** + near-free fuel |

- **Speed** runs 1× (Oak) → 25× (Blazing).
- **Fuel economy** is the underrated axis: a Blazing furnace burns roughly **10× less fuel per item**
  than Iron, and the Nether Star **~100× less**. At volume that beats raw speed.
- **Two special furnaces:** the **Netherrack** furnace needs **no fuel at all** (only 2× speed, but
  zero upkeep — great for an always-on smelting line), and the **Nether Star** furnace **batch-smelts
  an entire input stack at once** — the bulk-throughput endgame furnace.

!!! tip "Amethyst vs Diamond — Amethyst wins on paper"
    Both branch off the **Emerald** furnace and both upgrade into Netherite, but **Amethyst is
    stat-superior**: 15× vs 10× speed at the *same* 0.4 fuel economy. Go Diamond only if diamonds are
    cheaper for you than amethyst — otherwise Amethyst is strictly the better path.

## Recipes

Most tiers wrap the previous furnace at a vanilla crafting table with 6 material ingots + 1 material block. The **Oak Wood** and **Netherrack** furnaces are the exceptions — standalone builds, not upgrades of a prior tier.

### Oak Wood Furnace

The wooden starter tier — built from scratch, no vanilla furnace needed.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Planks"><img src="/images/items/planks.png"></div>
    <div class="crafting-slot" data-label="Planks"><img src="/images/items/planks.png"></div>
    <div class="crafting-slot" data-label="Planks"><img src="/images/items/planks.png"></div>
    <div class="crafting-slot" data-label="Planks"><img src="/images/items/planks.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Planks"><img src="/images/items/planks.png"></div>
    <div class="crafting-slot" data-label="Planks"><img src="/images/items/planks.png"></div>
    <div class="crafting-slot" data-label="Log"><img src="/images/items/log.png"></div>
    <div class="crafting-slot" data-label="Planks"><img src="/images/items/planks.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Oak Wood Furnace"><img src="/images/items/oak_wood_furnace.png"></div>
</div>

### Netherrack Furnace

A standalone side-grade — wrap a vanilla furnace in netherrack for the **no-fuel** furnace (never needs feeding; see the tier table).

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Netherrack"><img src="/images/items/netherrack.png"></div>
    <div class="crafting-slot" data-label="Netherrack"><img src="/images/items/netherrack.png"></div>
    <div class="crafting-slot" data-label="Netherrack"><img src="/images/items/netherrack.png"></div>
    <div class="crafting-slot" data-label="Netherrack"><img src="/images/items/netherrack.png"></div>
    <div class="crafting-slot" data-label="Furnace"><img src="/images/items/furnace.png"></div>
    <div class="crafting-slot" data-label="Netherrack"><img src="/images/items/netherrack.png"></div>
    <div class="crafting-slot" data-label="Netherrack"><img src="/images/items/netherrack.png"></div>
    <div class="crafting-slot" data-label="Netherrack"><img src="/images/items/netherrack.png"></div>
    <div class="crafting-slot" data-label="Netherrack"><img src="/images/items/netherrack.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Netherrack Furnace"><img src="/images/items/netherrack_furnace.png"></div>
</div>

### Copper Furnace

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Copper Ingot"><img src="/images/items/copper_ingot.png"></div>
    <div class="crafting-slot" data-label="Copper Ingot"><img src="/images/items/copper_ingot.png"></div>
    <div class="crafting-slot" data-label="Copper Ingot"><img src="/images/items/copper_ingot.png"></div>
    <div class="crafting-slot" data-label="Copper Ingot"><img src="/images/items/copper_ingot.png"></div>
    <div class="crafting-slot" data-label="Furnace"><img src="/images/items/furnace.png"></div>
    <div class="crafting-slot" data-label="Copper Ingot"><img src="/images/items/copper_ingot.png"></div>
    <div class="crafting-slot" data-label="Copper Ingot"><img src="/images/items/copper_ingot.png"></div>
    <div class="crafting-slot" data-label="Copper Block"><img src="/images/items/copper_block.png"></div>
    <div class="crafting-slot" data-label="Copper Ingot"><img src="/images/items/copper_ingot.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Copper Furnace"><img src="/images/items/copper_furnace.png"></div>
</div>

### Iron Furnace

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Copper Furnace"><img src="/images/items/copper_furnace.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Block"><img src="/images/items/iron_block.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Iron Furnace"><img src="/images/items/iron_furnace.png"></div>
</div>

### Gold Furnace

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Gold Ingot"><img src="/images/items/gold_ingot.png"></div>
    <div class="crafting-slot" data-label="Gold Ingot"><img src="/images/items/gold_ingot.png"></div>
    <div class="crafting-slot" data-label="Gold Ingot"><img src="/images/items/gold_ingot.png"></div>
    <div class="crafting-slot" data-label="Gold Ingot"><img src="/images/items/gold_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Furnace"><img src="/images/items/iron_furnace.png"></div>
    <div class="crafting-slot" data-label="Gold Ingot"><img src="/images/items/gold_ingot.png"></div>
    <div class="crafting-slot" data-label="Gold Ingot"><img src="/images/items/gold_ingot.png"></div>
    <div class="crafting-slot" data-label="Gold Block"><img src="/images/items/gold_block.png"></div>
    <div class="crafting-slot" data-label="Gold Ingot"><img src="/images/items/gold_ingot.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Gold Furnace"><img src="/images/items/gold_furnace.png"></div>
</div>

### Emerald Furnace

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Emerald"><img src="/images/items/emerald.png"></div>
    <div class="crafting-slot" data-label="Emerald"><img src="/images/items/emerald.png"></div>
    <div class="crafting-slot" data-label="Emerald"><img src="/images/items/emerald.png"></div>
    <div class="crafting-slot" data-label="Emerald"><img src="/images/items/emerald.png"></div>
    <div class="crafting-slot" data-label="Gold Furnace"><img src="/images/items/gold_furnace.png"></div>
    <div class="crafting-slot" data-label="Emerald"><img src="/images/items/emerald.png"></div>
    <div class="crafting-slot" data-label="Emerald"><img src="/images/items/emerald.png"></div>
    <div class="crafting-slot" data-label="Emerald Block"><img src="/images/items/emerald_block.png"></div>
    <div class="crafting-slot" data-label="Emerald"><img src="/images/items/emerald.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Emerald Furnace"><img src="/images/items/emerald_furnace.png"></div>
</div>

### Amethyst Furnace

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Amethyst Shard"><img src="/images/items/amethyst_shard.png"></div>
    <div class="crafting-slot" data-label="Amethyst Shard"><img src="/images/items/amethyst_shard.png"></div>
    <div class="crafting-slot" data-label="Amethyst Shard"><img src="/images/items/amethyst_shard.png"></div>
    <div class="crafting-slot" data-label="Amethyst Shard"><img src="/images/items/amethyst_shard.png"></div>
    <div class="crafting-slot" data-label="Emerald Furnace"><img src="/images/items/emerald_furnace.png"></div>
    <div class="crafting-slot" data-label="Amethyst Shard"><img src="/images/items/amethyst_shard.png"></div>
    <div class="crafting-slot" data-label="Amethyst Shard"><img src="/images/items/amethyst_shard.png"></div>
    <div class="crafting-slot" data-label="Amethyst Block"><img src="/images/items/amethyst_block.png"></div>
    <div class="crafting-slot" data-label="Amethyst Shard"><img src="/images/items/amethyst_shard.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Amethyst Furnace"><img src="/images/items/amethyst_furnace.png"></div>
</div>

### Diamond Furnace

Uses **Emerald Furnace** as base (skips amethyst tier).

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Diamond"><img src="/images/items/diamond.png"></div>
    <div class="crafting-slot" data-label="Diamond"><img src="/images/items/diamond.png"></div>
    <div class="crafting-slot" data-label="Diamond"><img src="/images/items/diamond.png"></div>
    <div class="crafting-slot" data-label="Diamond"><img src="/images/items/diamond.png"></div>
    <div class="crafting-slot" data-label="Emerald Furnace"><img src="/images/items/emerald_furnace.png"></div>
    <div class="crafting-slot" data-label="Diamond"><img src="/images/items/diamond.png"></div>
    <div class="crafting-slot" data-label="Diamond"><img src="/images/items/diamond.png"></div>
    <div class="crafting-slot" data-label="Diamond Block"><img src="/images/items/diamond_block.png"></div>
    <div class="crafting-slot" data-label="Diamond"><img src="/images/items/diamond.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Diamond Furnace"><img src="/images/items/diamond_furnace.png"></div>
</div>

### Netherite Furnace

Uses a different pattern: `M B M / B F B / M B M` (M=netherite_scrap, B=netherite_ingot, F=diamond_furnace).

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Netherite Scrap"><img src="/images/items/netherite_scrap.png"></div>
    <div class="crafting-slot" data-label="Netherite Ingot"><img src="/images/items/netherite_ingot.png"></div>
    <div class="crafting-slot" data-label="Netherite Scrap"><img src="/images/items/netherite_scrap.png"></div>
    <div class="crafting-slot" data-label="Netherite Ingot"><img src="/images/items/netherite_ingot.png"></div>
    <div class="crafting-slot" data-label="Diamond Furnace"><img src="/images/items/diamond_furnace.png"></div>
    <div class="crafting-slot" data-label="Netherite Ingot"><img src="/images/items/netherite_ingot.png"></div>
    <div class="crafting-slot" data-label="Netherite Scrap"><img src="/images/items/netherite_scrap.png"></div>
    <div class="crafting-slot" data-label="Netherite Ingot"><img src="/images/items/netherite_ingot.png"></div>
    <div class="crafting-slot" data-label="Netherite Scrap"><img src="/images/items/netherite_scrap.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Netherite Furnace"><img src="/images/items/netherite_furnace.png"></div>
</div>

### Blazing Furnace

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Blaze Rod"><img src="/images/items/blaze_rod.png"></div>
    <div class="crafting-slot" data-label="Blaze Rod"><img src="/images/items/blaze_rod.png"></div>
    <div class="crafting-slot" data-label="Blaze Rod"><img src="/images/items/blaze_rod.png"></div>
    <div class="crafting-slot" data-label="Blaze Rod"><img src="/images/items/blaze_rod.png"></div>
    <div class="crafting-slot" data-label="Netherite Furnace"><img src="/images/items/netherite_furnace.png"></div>
    <div class="crafting-slot" data-label="Blaze Rod"><img src="/images/items/blaze_rod.png"></div>
    <div class="crafting-slot" data-label="Blaze Rod"><img src="/images/items/blaze_rod.png"></div>
    <div class="crafting-slot" data-label="Netherite Block"><img src="/images/items/netherite_block.png"></div>
    <div class="crafting-slot" data-label="Blaze Rod"><img src="/images/items/blaze_rod.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Blazing Furnace"><img src="/images/items/blazing_furnace.png"></div>
</div>

### Nether Star Furnace

Uses a cross pattern: `_ M _ / M F M / _ M _` (M=nether_star, F=blazing_furnace).

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Nether Star"><img src="/images/items/nether_star.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Nether Star"><img src="/images/items/nether_star.png"></div>
    <div class="crafting-slot" data-label="Blazing Furnace"><img src="/images/items/blazing_furnace.png"></div>
    <div class="crafting-slot" data-label="Nether Star"><img src="/images/items/nether_star.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Nether Star"><img src="/images/items/nether_star.png"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Nether Star Furnace"><img src="/images/items/nether_star_furnace.png"></div>
</div>

## Automatic Item I/O

All smelters have built-in hopper-like behavior that runs every tick. The directions are **fixed** (relative to the way the furnace faces) and cannot be reconfigured:

| Slot | Source/Destination | Direction |
|------|--------------------|-----------|
| Fuel | Pulled from | Block **above** |
| Input (ingredients) | Pulled from | Block to the **left** |
| Output | Pushed to | Block to the **right** |

"Left" and "right" are relative to the furnace's facing direction (the side with the fire animation). A furnace facing **south**, for example, pulls input from the **east** side and pushes output to the **west** side.

Only vanilla containers count as valid sources/destinations (chests, barrels, hoppers, etc.). Place and orient the furnace before connecting containers — orientation determines which side is which.

## Key Points

- Higher tiers improve **speed, fuel economy, and (top tiers) special modes** — not just speed (see the [tier table](#furnace-tiers-at-a-glance))
- Not connected to UC power — no generators needed
- Functions as a direct drop-in replacement for vanilla furnaces
- Good parallel investment alongside UC machines; doesn't require the chip/power progression
- Opening the furnace UI requires using the **Open** button that appears when looking at it — direct right-click/tap does not open it (by design)
