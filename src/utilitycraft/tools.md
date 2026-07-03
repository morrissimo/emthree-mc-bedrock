# Tools — Paxel & AIOT

UC adds multi-tools at all material tiers: Paxels (pick + axe + shovel) and AIOTs (all-in-one: paxel + hoe + sword).

## Paxel

Combines pickaxe, axe, and shovel into a single item.

### Iron Paxel (vanilla crafting table, shaped)

Pattern: `A X A / Z S C / D S D` (A=string, X=iron_shovel, Z=iron_axe, S=stick, C=iron_pickaxe, D=string)

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="String"><img src="/images/items/string.png"></div>
    <div class="crafting-slot" data-label="Iron Shovel"><img src="/images/items/iron_shovel.png"></div>
    <div class="crafting-slot" data-label="String"><img src="/images/items/string.png"></div>
    <div class="crafting-slot" data-label="Iron Axe"><img src="/images/items/iron_axe.png"></div>
    <div class="crafting-slot" data-label="Stick"><img src="/images/items/stick.png"></div>
    <div class="crafting-slot" data-label="Iron Pickaxe"><img src="/images/items/iron_pickaxe.png"></div>
    <div class="crafting-slot" data-label="String"><img src="/images/items/string.png"></div>
    <div class="crafting-slot" data-label="Stick"><img src="/images/items/stick.png"></div>
    <div class="crafting-slot" data-label="String"><img src="/images/items/string.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Iron Paxel"><img src="/images/items/iron_paxel.png"></div>
</div>

## AIOT — All In One Tool

Adds hoe and sword functionality on top of the paxel. Requires a paxel as an ingredient.

### Steel AIOT (vanilla crafting table, shaped)

Pattern: `D S D / H P A / Z H D` (D=steel_ingot, S=steel_sword, H=string, P=steel_paxel, A=steel_hoe, Z=stick)

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Sword"><img src="/images/items/steel_sword.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="String"><img src="/images/items/string.png"></div>
    <div class="crafting-slot" data-label="Steel Paxel"><img src="/images/items/steel_paxel.png"></div>
    <div class="crafting-slot" data-label="Steel Hoe"><img src="/images/items/steel_hoe.png"></div>
    <div class="crafting-slot" data-label="Stick"><img src="/images/items/stick.png"></div>
    <div class="crafting-slot" data-label="String"><img src="/images/items/string.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Steel AIOT"><img src="/images/items/steel_aiot.png"></div>
</div>

## Tiers

Both Paxels and AIOTs exist at all tiers: wood, copper, iron, steel, diamond, netherite, and others. Each tier follows the same pattern with the appropriate material.

## AIOT Behavior

The AIOT has two modes, toggled by sneaking:

| State | Mode | Effect |
|-------|------|--------|
| **Not sneaking** | Hoe / tractor | 3×3 area: tills soil + tractor farming (auto-harvests fully grown vanilla crops; resets UC metal/gem crops to age 0 and collects them) |
| **Sneaking** | Shovel | 3×3 area: converts dirt/grass to path blocks; clears snow |

> **Note:** Tree-felling while sneaking is not implemented in v3.4.3 despite some documentation suggesting otherwise.

---

## Drills

Handheld **area miners**. Break a block and the Drill destroys a **cube** centered on it (digging into the ground below), with drops obeying normal block loot. Both are enchantable (pickaxe slot) and deal 5 melee damage.

| Drill | Tier | Mining cube | Dig speed | Durability | Repair with |
|---|---|---|---|---|---|
| Drill | Iron | 3×3×3 | 14 | 2031 | iron block (+800) or another drill |
| Heavy Drill | Diamond | 5×5×5 | 20 | 4062 | diamond (+1600) or a drill |

Both are crafted at the **UC Crafter** — the Heavy Drill consumes a Drill:

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Block"><img src="/images/items/iron_block.png"></div>
    <div class="crafting-slot" data-label="Repeater"><img src="/images/items/repeater.png"></div>
    <div class="crafting-slot" data-label="Amethyst Block"><img src="/images/items/amethyst_block.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Repeater"><img src="/images/items/repeater.png"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Drill"><img src="/images/items/drill.png"></div>
</div>

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Diamond"><img src="/images/items/diamond.png"></div>
    <div class="crafting-slot" data-label="Diamond Block"><img src="/images/items/diamond_block.png"></div>
    <div class="crafting-slot" data-label="Repeater"><img src="/images/items/repeater.png"></div>
    <div class="crafting-slot" data-label="Drill"><img src="/images/items/drill.png"></div>
    <div class="crafting-slot" data-label="Diamond"><img src="/images/items/diamond.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Repeater"><img src="/images/items/repeater.png"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Heavy Drill"><img src="/images/items/heavy_drill.png"></div>
</div>

## Steel Tools

The steel tier fills the gap between iron and diamond on **durability** — **750 uses each** (~3× iron), dig speed 7, iron-tier mining (the pickaxe can't mine diamond-tier blocks). Crafted at a vanilla table with steel ingots + sticks. (A Steel Sword and Steel Hoe exist too.)

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Stick"><img src="/images/items/stick.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Stick"><img src="/images/items/stick.png"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Steel Axe"><img src="/images/items/steel_axe.png"></div>
</div>

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Stick"><img src="/images/items/stick.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Stick"><img src="/images/items/stick.png"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Steel Pickaxe"><img src="/images/items/steel_pickaxe.png"></div>
</div>

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Stick"><img src="/images/items/stick.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Stick"><img src="/images/items/stick.png"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Steel Shovel"><img src="/images/items/steel_shovel.png"></div>
</div>

## Flint Knife

An early-game **shears substitute and fiber farming tool**. It mines all leaf types quickly, and breaking any leaf block drops **1–2 [Fiber](explosives.md#fiber)** (~50% chance) — a string substitute for before you've found sheep or spiders. Enchantable (shears slot), 128 durability. Crafted at a vanilla table:

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Flint"><img src="/images/items/flint.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Stick"><img src="/images/items/stick.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Flint Knife"><img src="/images/items/flint_knife.png"></div>
</div>

