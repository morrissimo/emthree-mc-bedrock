# Cobble Generators

Standalone **auto-cobblestone** blocks. Each one quietly produces cobblestone on a timer — no water/lava setup, no power, no redstone. Six tiers, from Copper (slow) to Netherite (a firehose of cobble).

## Tiers & rates

Every tier produces **1 cobblestone per cycle**; higher tiers just cycle faster:

| Tier | Generator | Output rate |
|---|---|---|
| 0 | <img src="/images/items/cobble_gen_copper.png" width="16"> Copper | 1 per 4.0 s (~0.25/s) |
| 1 | <img src="/images/items/cobble_gen_iron.png" width="16"> Iron | 1 per 2.0 s (~0.5/s) |
| 2 | <img src="/images/items/cobble_gen_gold.png" width="16"> Gold | 1 per 1.0 s (~1/s) |
| 3 | <img src="/images/items/cobble_gen_emerald.png" width="16"> Emerald | 1 per 0.5 s (~2/s) |
| 4 | <img src="/images/items/cobble_gen_diamond.png" width="16"> Diamond | 1 per 0.25 s (~4/s) |
| 5 | <img src="/images/items/cobble_gen_netherite.png" width="16"> Netherite | 1 per 0.05 s (~20/s) |

## How it works

- **Fully standalone** — no water/lava blocks need to be adjacent (buckets are only a *crafting* ingredient for the tier-0 block).
- **Auto-outputs** 1 cobble each cycle into the container in the direction it **faces** (face up → drops into the block *below* it; face north → the block to the north; etc.). Point it at a hopper or chest and it feeds straight in.
- **No container?** It buffers internally (up to 64). **Right-click with an empty hand** to collect the buffered stack.

## Recipes

The **Tier-0 (Copper)** generator is the base — vanilla crafting table (returns your 2 buckets):

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Copper Ingot"><img src="/images/items/copper_ingot.png"></div>
    <div class="crafting-slot" data-label="Obsidian"><img src="/images/items/obsidian.png"></div>
    <div class="crafting-slot" data-label="Copper Ingot"><img src="/images/items/copper_ingot.png"></div>
    <div class="crafting-slot" data-label="Water Bucket"><img src="/images/items/water_bucket.png"></div>
    <div class="crafting-slot" data-label="Glass"><img src="/images/items/glass.png"></div>
    <div class="crafting-slot" data-label="Lava Bucket"><img src="/images/items/lava_bucket.png"></div>
    <div class="crafting-slot" data-label="Copper Ingot"><img src="/images/items/copper_ingot.png"></div>
    <div class="crafting-slot" data-label="Obsidian"><img src="/images/items/obsidian.png"></div>
    <div class="crafting-slot" data-label="Copper Ingot"><img src="/images/items/copper_ingot.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Copper Cobble Gen"><img src="/images/items/cobble_gen_copper.png"></div>
</div>

Each higher tier is an **upgrade** — surround the previous-tier generator with **8× the tier material**. E.g. the Iron (Tier-1):

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Copper Cobble Gen"><img src="/images/items/cobble_gen_copper.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Iron Cobble Gen"><img src="/images/items/cobble_gen_iron.png"></div>
</div>

The material per upgrade tier: **Iron** (T1) → **Gold** (T2) → **Emerald** (T3) → **Diamond** (T4) → **Netherite Scrap** (T5), each wrapping the previous tier's generator.
