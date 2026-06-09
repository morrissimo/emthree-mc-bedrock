# Tools — Paxel & AIOT

UC adds multi-tools at all material tiers: Paxels (pick + axe + shovel) and AIOTs (all-in-one: paxel + hoe + sword).

## Paxel

Combines pickaxe, axe, and shovel into a single item. **Iron Paxel** recipe (vanilla crafting table):

```
str    shovel  str
axe    stick   pick
str    stick   str
```

(`str` = string)

## AIOT — All In One Tool

Adds hoe and sword functionality on top of the paxel. Requires a paxel as an ingredient. **Iron AIOT** (vanilla crafting table):

```
iron_ingot    iron_sword    iron_ingot
string        iron_paxel    iron_hoe
stick         string        iron_ingot
```

## Tiers

Both Paxels and AIOTs exist at all tiers: wood, copper, iron, steel, diamond, netherite, and others. Each tier follows the same pattern with the appropriate material.

## AIOT Behavior

The AIOT has two modes, toggled by sneaking:

| State | Mode | Effect |
|-------|------|--------|
| **Not sneaking** | Hoe / tractor | 3×3 area: tills soil + tractor farming (auto-harvests fully grown vanilla crops; resets UC metal/gem crops to age 0 and collects them) |
| **Sneaking** | Shovel | 3×3 area: converts dirt/grass to path blocks; clears snow |

> **Correction to the Dorios Studios wiki:** The wiki claims AIOTs fell entire trees while sneaking. This is **not implemented in v3.4.3**.
