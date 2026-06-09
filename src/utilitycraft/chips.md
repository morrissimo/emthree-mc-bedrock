# Chips

Chips are the primary gating mechanism for machines. Higher-tier machines require higher-tier chips, and each chip tier requires the previous tier as an ingredient.

All chip recipes are crafted at the [UC Workbench](workbench.md). The [Infuser](infuser.md) provides alternative automated recipes for all tiers.

## Chip Tier Ladder

### chip (base)
```
_ S _
S R S
_ S _
```
`S` = steel_ingot, `R` = redstone

### basic_chip
```
R G R
G C G
R G R
```
`G` = gold_ingot, `C` = chip, `R` = redstone

### advanced_chip
```
R E R
E C E
R E R
```
`E` = energized_iron_ingot, `C` = basic_chip, `R` = redstone

> Requires [energized iron](energized_iron.md) — get it from ore trees or the infuser.

### expert_chip
```
R D R
D C D
R D R
```
`D` = diamond, `C` = advanced_chip, `R` = redstone

### ultimate_chip
```
R N R
N C N
R N R
```
`N` = netherite_ingot, `C` = expert_chip, `R` = redstone

## Infuser Chip Recipes (alternative)

The Infuser can produce chips automatically once powered. See the [Infuser](infuser.md) page for the full recipe table.

| Output | Catalyst | Input | Cycles |
|--------|----------|-------|--------|
| chip | redstone | steel_plate | 2 |
| basic_chip | gold_dust | chip | 2 |
| advanced_chip | energized_iron_dust | basic_chip | 2 |
| expert_chip | diamond_dust | advanced_chip | 2 |
| ultimate_chip | netherite_dust | expert_chip | 2 |
