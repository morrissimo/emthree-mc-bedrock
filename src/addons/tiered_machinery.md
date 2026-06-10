# UC Tiered Machinery

Adds powered, tiered versions of UC's core machines — crushers, incinerators, and an electro press. The base UC machines upgrade into powered versions via this addon.

## Tiered Crusher

Powered crusher with four tiers: basic → advanced → expert → ultimate.

**basic_crusher** = UC base `crusher` wrapped with:
```
basic_chip + steel_ingot + iron_ingot + redstone_block
```

**Higher tiers** — each wraps the previous:
```
higher_chip + steel_plate + energized_iron_plate + redstone_block
```

Powered versions process faster and handle higher-tier inputs than the base unpowered crusher.

## Tiered Incinerator

A powered furnace/smelter that integrates with the UC power system.

- Four tiers: basic → advanced → expert → ultimate
- This is the UC-power-connected smelting option
- Distinct from [Better Smelters](better_smelters.md), which are standalone (no UC power required)

## Electro Press

Makes **plates** from ingots. Plates are required ingredients for advanced-tier generators and machine upgrades.

Four tiers: basic → advanced → expert → ultimate.

**Plates produced:**
- iron_plate
- gold_plate
- steel_plate
- copper_plate
- energized_iron_plate
- netherite_plate
- diamond_plate (and others)

Plates are used heavily in advanced/expert/ultimate tier upgrades throughout UC. Build an electro press early once you have power — it unlocks the full progression path.
