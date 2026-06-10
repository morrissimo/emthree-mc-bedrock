# Trinkets

Equippable accessories with passive stat effects — rings, goggles, amulets, etc. Uses a slot-based system (ring slot, head slot, etc.).

## Opening the Trinket Inventory

Trinkets don't use normal armor slots — they have their own inventory screen opened with a **scroll** item.

**Scroll** (vanilla crafting table, shapeless):

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Paper"><img src="/images/items/paper.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Scroll"><img src="/images/items/scroll.png"></div>
</div>

Hold the scroll in your main hand and **use** (right-click / interact) to open the trinket inventory. Drag trinkets into the appropriate slots — effects apply immediately while equipped.

Two related scrolls:
- **Stats scroll** — shows your current trinket-modified stats
- **Recover scroll** — unequips all trinkets at once (can be crafted back into a regular scroll)

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

### Empty Ring

Pattern: `P I P / I _ I / P I P` (P=iron_nugget, I=iron_ingot)

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Iron Nugget"><img src="/images/items/iron_nugget.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Nugget"><img src="/images/items/iron_nugget.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Nugget"><img src="/images/items/iron_nugget.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Nugget"><img src="/images/items/iron_nugget.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Empty Ring"><img src="/images/items/empty_ring.png"></div>
</div>

### Runner Ring

Pattern: `P D P / H R H / F A F` (P=Potion of Swiftness, D=diamond, H=rabbit_hide, R=empty_ring, F=feather, A=rabbit_foot)

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Potion of Swiftness"><img src="/images/items/potion_speed.png"></div>
    <div class="crafting-slot" data-label="Diamond"><img src="/images/items/diamond.png"></div>
    <div class="crafting-slot" data-label="Potion of Swiftness"><img src="/images/items/potion_speed.png"></div>
    <div class="crafting-slot" data-label="Rabbit Hide"><img src="/images/items/rabbit_hide.png"></div>
    <div class="crafting-slot" data-label="Empty Ring"><img src="/images/items/empty_ring.png"></div>
    <div class="crafting-slot" data-label="Rabbit Hide"><img src="/images/items/rabbit_hide.png"></div>
    <div class="crafting-slot" data-label="Feather"><img src="/images/items/feather.png"></div>
    <div class="crafting-slot" data-label="Rabbit Foot"><img src="/images/items/rabbit_foot.png"></div>
    <div class="crafting-slot" data-label="Feather"><img src="/images/items/feather.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Runner Ring"><img src="/images/items/runner_ring.png"></div>
</div>

### Miner Ring

Pattern: `P D P / G R G / C G C` (P=redstone_block, D=golden_pickaxe, G=gold_block, R=empty_ring, C=glowstone_dust)

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Golden Pickaxe"><img src="/images/items/golden_pickaxe.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Gold Block"><img src="/images/items/gold_block.png"></div>
    <div class="crafting-slot" data-label="Empty Ring"><img src="/images/items/empty_ring.png"></div>
    <div class="crafting-slot" data-label="Gold Block"><img src="/images/items/gold_block.png"></div>
    <div class="crafting-slot" data-label="Glowstone Dust"><img src="/images/items/glowstone_dust.png"></div>
    <div class="crafting-slot" data-label="Gold Block"><img src="/images/items/gold_block.png"></div>
    <div class="crafting-slot" data-label="Glowstone Dust"><img src="/images/items/glowstone_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Miner Ring"><img src="/images/items/miner_ring.png"></div>
</div>

## Loot / Mob Drop Trinkets

Some trinkets are not craftable and must be found:

- `abyssal_diver_helmet` — drops from drowned or found in ocean chests

## Usage

Equip trinkets in their designated accessory slots (not armor slots). Effects apply passively while equipped.
