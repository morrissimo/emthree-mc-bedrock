# Crusher

The crusher is UC's ore doubler. It works via a **dust intermediate** — ore goes in, two dusts come out, smelt the dusts for two ingots instead of one.

!!! warning "The crusher needs power"
    The crusher is a **powered machine** — it draws UC energy every operation (base
    `utilitycraft:crusher`: 64,000 energy buffer, **800 energy per crush**) and does **nothing**
    without a power source. Hook it up to a generator (see [Power System](power.md) /
    [Generators](generators.md)). There is **no** unpowered/hand-crank crusher.

The base `utilitycraft:crusher` (from UC core) handles the everyday ore-doubling. [UC Tiered
Machinery](../addons/tiered_machinery.md) adds higher-throughput tiers — `basic` → `advanced` →
`expert` → `ultimate` crushers — that run faster and unlock the compressed-material recipes (the
higher-tier entries below).

## Recipe (UC Workbench, shaped)

Pattern: `S H S / I M I / S R S` (S=redstone, H=iron_hammer, I=chip, M=machine_case, R=gold_ingot)

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Iron Hammer"><img src="/images/items/iron_hammer.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Chip"><img src="/images/items/chip.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Chip"><img src="/images/items/chip.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Gold Ingot"><img src="/images/items/gold_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Crusher"><img src="/images/items/crusher.png"></div>
</div>

## Ore Doubling — Raw Ores

1 raw ore → 2× dust → smelt each → **2 ingots** (vs 1 direct)

| Input | Output | Net ingots |
|-------|--------|------------|
| raw_iron | 2× iron_dust | 2 |
| raw_copper | 2× copper_dust | 2 |
| raw_gold | 2× gold_dust | 2 |
| raw_energized_iron | 2× energized_iron_dust | 2 |
| coal | 2× coal_dust | 2 |
| diamond | 2× diamond_dust | 2 |
| emerald | 2× emerald_dust | 2 |
| nether quartz | 2× quartz_dust | 2 |
| amethyst shard | 2× amethyst_dust | 2 |

## Raw Ore Block Bonus (~+33% vs direct)

A raw ore block is 9 raw ore. Crushing it yields **12 dust** → 12 ingots, vs **9** from
direct-smelting the same 9 raw ore — about **33% more** (needs 1,600 energy per block):

| Input | Output | Net ingots |
|-------|--------|------------|
| raw_iron_block | 12× iron_dust | 12 (vs 9 direct) |
| raw_copper_block | 12× copper_dust | 12 |
| raw_gold_block | 12× gold_dust | 12 |

## Other Crusher Recipes

| Input | Output | Notes |
|-------|--------|-------|
| cobblestone | gravel | |
| gravel | dirt | chain: cobble→gravel→dirt→sand |
| dirt | sand | |
| iron_ingot | 1× iron_dust | Downgrade — lossy, rarely useful |
| iron_block | 6× iron_dust | ~80% recovery, lossy |
| white wool | 4× string | white wool only |
| bone | 3× bone_meal | |
| bone_block | 9× bone_meal | |
| nether_wart_block | 4× nether_wart | |
| blaze_rod | 2× blaze_powder | |
| magma_block | 4× magma_cream | |
| slime_block | 9× slime_ball | |
| blue_ice | 9× packed_ice | chain: blue_ice→packed_ice→ice |
| packed_ice | 9× ice | |
