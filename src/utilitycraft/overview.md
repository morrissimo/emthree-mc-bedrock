# UtilityCraft — Overview & Progression

UtilityCraft v3.4.3 is a tech addon for Bedrock that adds a full industrial progression: resource processing, power generation, and multi-tools. Everything gates behind **steel**, which you manufacture rather than mine.

## Progression Summary

```
Gather materials
  ↓
Craft smeltflare (paper + coal + flint)
  ↓
Make raw_steel → smelt → steel_ingot
  ↓
Build UC Workbench (vanilla crafting table)
  ↓
Craft chip → basic_chip → machine_case
  ↓
Build basic_furnator (power source)
  ↓
Build crusher → ore doubling
  ↓
Energized iron (ore trees) → advanced_chip
  ↓
Advanced machines (infuser, etc.)
  ↓
Expert / Ultimate tiers (diamond, netherite)
```

## Installed Version

**v3.4.3** — Bedrock Edition. The Dorios Studios wiki is often outdated or wrong; all recipe details here are verified from the addon source files.

## Addon Structure

| Component | What it does |
|-----------|-------------|
| [Steel & Smeltflare](steel.md) | Gateway material — manufactured, not mined |
| [UC Workbench](workbench.md) | Required for all mid/late recipes |
| [Chips](chips.md) | Primary gating mechanism for machines |
| [Energized Iron](energized_iron.md) | Gates advanced_chip and mid-game machines |
| [Hammers](hammers.md) | Crafting ingredient (crusher build) |
| [Machine Case](machine_case.md) | Required component for most machines |
| [Power System](power.md) | Generators, batteries, transmitters |
| [Crusher](crusher.md) | Ore doubling via dust intermediate |
| [Infuser](infuser.md) | Catalyst-based processing (chips, energized iron) |
| [Tools](tools.md) | Paxel (pick+axe+shovel), AIOT (all-in-one) |

## Known Bugs (v3.4.3)

- `iron_hammer` — item exists, crusher recipe requires it, **no crafting recipe JSON**. Use a hammer obtained via creative/commands, or see the [Hammers](hammers.md) page for the presumed pattern.
