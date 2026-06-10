# Crusher

The crusher is UC's ore doubler. It works via a **dust intermediate** — ore goes in, two dusts come out, smelt the dusts for two ingots instead of one.

The base crusher from UC core is the unpowered version. [UC Tiered Machinery](../addons/tiered_machinery.md) wraps it into a powered `basic_crusher` and adds higher tiers.

## Recipe (UC Workbench, shaped)

```
S H S
I M I
S R S
```

| Symbol | Item |
|--------|------|
| `S` | redstone |
| `H` | iron_hammer (see [Hammers](hammers.md)) |
| `I` | chip |
| `M` | machine_case |
| `R` | gold_ingot |

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

## Raw Ore Block Bonus (~120% efficiency)

Raw ore blocks skip smelting penalties for a better yield than 9× direct-smelted ore:

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
| wool | 4× string | |
| bone | bone_meal | |
| bone_block | bone_meal (×9) | |
| nether_wart_block | 4× nether_wart | |
| blaze_rod | 2× blaze_powder | |
| magma_block | 4× magma_cream | |
| slime_block | 9× slime_ball | |
| blue_ice | 9× packed_ice | chain: blue_ice→packed_ice→ice |
| packed_ice | 9× ice | |
