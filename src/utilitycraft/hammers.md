# Hammers

Hammers are crafting ingredients, primarily used in the [Crusher](crusher.md) build recipe. They are not used as tools directly.

## Recipe Pattern (vanilla crafting table, shaped)

All hammers share the same pattern:

```
M X M
M D M
_ D _
```

| Symbol | Item |
|--------|------|
| `M` | material ingot (×4) |
| `X` | material block (×1) |
| `D` | stick (×2) |

## Hammer Tiers

| Hammer | M | X |
|--------|---|---|
| wooden_hammer | planks | log |
| stone_hammer | cobblestone | stone |
| copper_hammer | copper_ingot | copper_block |
| steel_hammer | steel_ingot | steel_block |

## Known Bug — iron_hammer Missing Recipe

> The Crusher build recipe requires `iron_hammer`. The `iron_hammer` item IS defined in the UC pack, but **no crafting recipe JSON exists** for it. This appears to be a v3.4.3 bug.
>
> By the pattern above, it would be:
> `iron_ingot×4 + iron_block + stick×2` — but that recipe file is absent from the pack.
>
> Use creative mode or commands to obtain iron_hammer for the crusher build until this is fixed.
