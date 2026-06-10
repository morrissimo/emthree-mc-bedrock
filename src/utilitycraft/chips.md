# Chips

Chips are the primary gating mechanism for machines. Higher-tier machines require higher-tier chips, and each chip tier requires the previous tier as an ingredient.

All chip recipes are crafted at the [UC Workbench](workbench.md). The [Infuser](infuser.md) provides alternative automated recipes for all tiers.

## Chip Tier Ladder

### chip (base)

Pattern: `_ S _ / S R S / _ S _` (S=steel_ingot, R=redstone)

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Chip"><img src="/images/items/chip.png"></div>
</div>

### basic_chip

Pattern: `R G R / G C G / R G R` (G=gold_ingot, C=chip, R=redstone)

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Gold Ingot"><img src="/images/items/gold_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Gold Ingot"><img src="/images/items/gold_ingot.png"></div>
    <div class="crafting-slot" data-label="Chip"><img src="/images/items/chip.png"></div>
    <div class="crafting-slot" data-label="Gold Ingot"><img src="/images/items/gold_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Gold Ingot"><img src="/images/items/gold_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
</div>

### advanced_chip

Pattern: `R E R / E C E / R E R` (E=energized_iron_ingot, C=basic_chip, R=redstone)

> Requires [energized iron](energized_iron.md) — get it from ore trees or the infuser.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Ingot"><img src="/images/items/energized_iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Ingot"><img src="/images/items/energized_iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Ingot"><img src="/images/items/energized_iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Ingot"><img src="/images/items/energized_iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
</div>

### expert_chip

Pattern: `R D R / D C D / R D R` (D=diamond, C=advanced_chip, R=redstone)

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Diamond"><img src="/images/items/diamond.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Diamond"><img src="/images/items/diamond.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Diamond"><img src="/images/items/diamond.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Diamond"><img src="/images/items/diamond.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
</div>

### ultimate_chip

Pattern: `R N R / N C N / R N R` (N=netherite_ingot, C=expert_chip, R=redstone)

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Netherite Ingot"><img src="/images/items/netherite_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Netherite Ingot"><img src="/images/items/netherite_ingot.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Netherite Ingot"><img src="/images/items/netherite_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Netherite Ingot"><img src="/images/items/netherite_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
</div>

## Infuser Chip Recipes (alternative)

The Infuser can produce chips automatically once powered. See the [Infuser](infuser.md) page for the full recipe table.

| Output | Catalyst | Input | Cycles |
|--------|----------|-------|--------|
| chip | redstone | steel_plate | 2 |
| basic_chip | gold_dust | chip | 2 |
| advanced_chip | energized_iron_dust | basic_chip | 2 |
| expert_chip | diamond_dust | advanced_chip | 2 |
| ultimate_chip | netherite_dust | expert_chip | 2 |
