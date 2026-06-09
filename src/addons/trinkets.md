# Trinkets

Equippable accessories with passive stat effects — rings, goggles, amulets, etc. Uses a slot-based system (ring slot, head slot, etc.).

## Dependency Note

Trinkets bundles its own RPG Core in `scripts/Core/DoriosAPI/` — **no separate addon required**. The `register.js` script checks for an optional external RPG Core companion (for cross-addon stat integration) and logs a warning if not found, but all trinket effects work fully standalone without it.

## Crafted Trinkets

All crafted at a vanilla crafting table.

| Item | Key ingredients | Effect |
|------|----------------|--------|
| empty_ring | base component for all rings | none |
| runner_ring | empty_ring + diamond + rabbit_hide + feather + speed potion + rabbit_foot | speed boost |
| miner_ring | empty_ring + gold_block + redstone_block + golden_pickaxe + glowstone_dust | haste |
| guardian_ring | see in-game recipe | defense |
| healer_ring | see in-game recipe | regeneration |
| night_vision_goggles | leather + iron_ingot + tinted_glass + night_vision_potion | night vision |
| obsidian_skull | see in-game recipe | fire resistance |
| warden_heart | see in-game recipe | — |
| abyssal_orb | see in-game recipe | — |

## Loot / Mob Drop Trinkets

Some trinkets are not craftable and must be found:

- `abyssal_diver_helmet` — drops from drowned or found in ocean chests

## Usage

Equip trinkets in their designated accessory slots (not armor slots). Effects apply passively while equipped.
