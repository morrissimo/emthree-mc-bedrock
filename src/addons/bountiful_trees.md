# Bountiful Trees

Ore trees — grow trees whose logs drop raw ore materials instead of (or in addition to) wood. The primary renewable source of energized iron and other ores.

## Tree Types & Log Drops

| Tree | Log drops | Amount per log |
|------|-----------|----------------|
| coal tree | coal | 2–6 |
| copper tree | raw_copper | 2–6 |
| gold tree | raw_gold | 1–3 |
| energized iron tree | raw_energized_iron | 1–2 |
| emerald tree | emerald | 1 |
| iron tree | raw_iron (see loot table) | varies |
| redstone tree | redstone (see loot table) | varies |

All logs also drop **1 oak_log** alongside their ore drop.

## Getting Saplings

**Crafting** (vanilla crafting table, shaped) — wrap an oak sapling with 8 of the matching material:

```
M M M
M S M
M M M
```
`M` = ore/ingot, `S` = oak_sapling → 1× ore sapling

| Sapling | Material (`M`) |
|---------|---------------|
| coal | coal |
| copper | raw_copper |
| gold | gold_ingot |
| iron | iron_ingot |
| energized iron | raw_energized_iron |
| emerald | emerald |
| diamond | diamond |
| redstone | redstone |
| lapis | lapis_lazuli |
| quartz | nether_quartz |
| netherite | netherite_ingot |
| steel | steel_ingot |

**Leaf drops** — breaking the colored leaves of a mature ore tree has a ~5% chance to drop the corresponding sapling. Good for expanding your orchard without spending more materials.

## Growing Trees

1. Obtain the appropriate ore sapling
2. Right-click on appropriate soil to plant
3. Tree grows on random tick — **20% chance per tick**
4. Or apply bone meal — **20% chance per bone meal** (instant growth if it triggers)

**Mature tree structure:** 2–4 block trunk, 5×5 canopy base, 3×3 middle layer, cross-shaped top layer

**Harvesting:** Chop logs with an axe. Drops apply to log blocks only, not leaves.

## Key Use Case

The **energized iron tree** is the only renewable source of `raw_energized_iron` without a powered [Infuser](../utilitycraft/infuser.md). It's the early-game path to [advanced_chip](../utilitycraft/chips.md) and mid-game machines.

## Notes

- Saplings are the progression gate — find or trade for your first sapling of each type
- Once you have one mature tree, you can farm saplings from its leaves to expand your orchard
- Bone meal farming is efficient: keep a stack handy and apply until the tree grows
