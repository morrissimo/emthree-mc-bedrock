# Infuser

The Infuser is a powered mid-game machine that infuses a **catalyst** into an **input** item to produce an output. Primary uses: automated chip production and energized iron.

## Build Recipe (UC Workbench, shaped)

```
R S R
C M C
R D R
```

| Symbol | Item |
|--------|------|
| `R` | redstone |
| `S` | lapis_lazuli |
| `C` | basic_chip |
| `M` | machine_case |
| `D` | redstone_block |

## Recipe Format

All infuser recipes follow: **catalyst | input → output (N cycles)**

The catalyst is consumed once; the input is consumed each cycle.

## Chip Recipes

These are an automated alternative to the [UC Workbench chip recipes](chips.md).

| Catalyst | Input | Output | Cycles |
|----------|-------|--------|--------|
| redstone | steel_plate | chip | 2 |
| gold_dust | chip | basic_chip | 2 |
| energized_iron_dust | basic_chip | advanced_chip | 2 |
| diamond_dust | advanced_chip | expert_chip | 2 |
| netherite_dust | expert_chip | ultimate_chip | 2 |

> Note: infuser chip recipes use **dusts and plates** as inputs/catalysts, not raw ingots. You'll need a [Crusher](crusher.md) and [Electro Press](../addons/tiered_machinery.md#electro-press) to supply these.

## Energized Iron Recipes

| Catalyst | Input | Output | Cycles |
|----------|-------|--------|--------|
| redstone | iron_ingot | energized_iron_ingot | 4 |
| redstone | iron_dust | energized_iron_dust | 4 |

The infuser is the mid-game automated source of energized iron once you have power infrastructure running.
