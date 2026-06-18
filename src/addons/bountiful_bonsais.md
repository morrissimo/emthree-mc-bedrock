# Bountiful Bonsais

Bonsai blocks are compact automated tree and plant farms that fit in a single block. Plant a sapling or seed in a Bonsai, optionally add a soil block for bonuses, and it will grow and harvest itself — dropping output into a hopper below.

This feature is part of the **Bountiful Trees** addon and is tightly integrated with UtilityCraft.

---

## Crafting the Bonsai

Crafted at a **vanilla crafting table** (not the UC Workbench).

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Stone Slab"><img src="/images/items/stone_slab.png"></div>
    <div class="crafting-slot" data-label="Hopper"><img src="/images/items/hopper.png"></div>
    <div class="crafting-slot" data-label="Stone Slab"><img src="/images/items/stone_slab.png"></div>
    <div class="crafting-slot" data-label="Planks"><img src="/images/items/planks.png"></div>
    <div class="crafting-slot" data-label="Stone Slab"><img src="/images/items/stone_slab.png"></div>
    <div class="crafting-slot" data-label="Planks"><img src="/images/items/planks.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Bonsai"><img src="/images/items/bonsai.png"></div>
</div>

*Pattern: `SHS / PSP` (2 rows) — Stone Slab (S), Hopper (H), Planks (P)*

---

## How to Use

1. **Place the Bonsai** wherever you want your farm.
2. **Right-click with a sapling or seed** to plant it inside the Bonsai.
3. *(Optional)* **Right-click with a soil block** to set the soil type — different soils give growth speed bonuses and yield multipliers.
4. *(Optional)* **Right-click with a hoe** to manually trigger a harvest cycle, reducing the time to next growth.
5. **Place a hopper below** the Bonsai to collect drops automatically.

The Bonsai handles everything else — growth, harvesting, and outputting drops.

---

## Soil Types

Different soils provide bonuses to growth speed and drop yield. Right-click the Bonsai with the soil block to apply.

| Soil | Growth Bonus | Yield Multiplier | Notes |
|---|---|---|---|
| Dirt | — | 1× | Default, no bonus |
| Grass Block | +10% speed | 1× | Slight speed improvement |
| Podzol | +25% speed | 1.5× | Good for most plants |
| Mycelium | +25% speed | 1.5× | Good for most plants |
| Soul Sand | +50% speed | 1× | Fast growth, normal yield |
| Crimson Nylium | +50% speed | 2× | Best for Nether fungi |
| Warped Nylium | +50% speed | 2× | Best for Nether fungi |
| Sand | — | 1× | Required for some desert plants |
| Red Sand | — | 1× | Alternative desert option |
| End Stone | +15% speed | 1.5× | Works for chorus plants |

---

## Supported Plants

The Bonsai supports all 30 vanilla plantable saplings and seeds, plus additional plants from Bountiful Crops (if installed).

### Trees (Saplings)

| Plant | Primary Drops | Notes |
|---|---|---|
| Oak Sapling | Oak Log, Apple, Stick | — |
| Birch Sapling | Birch Log, Stick | — |
| Spruce Sapling | Spruce Log, Stick | — |
| Jungle Sapling | Jungle Log, Cocoa Beans, Stick | — |
| Acacia Sapling | Acacia Log, Stick | — |
| Dark Oak Sapling | Dark Oak Log, Apple, Stick | — |
| Cherry Sapling | Cherry Log, Pink Petals, Stick | — |
| Mangrove Propagule | Mangrove Log, Mud, Stick | — |
| Pale Oak Sapling | Pale Oak Log, Stick | — |
| **Apple Sapling** | Apple, Oak Log | UC-specific sapling — see recipe below |

### Nether Plants (Saplings/Fungi)

| Plant | Primary Drops | Notes |
|---|---|---|
| Crimson Fungus | Crimson Stem, Nether Wart Block, Weeping Vines | Use Crimson Nylium soil |
| Warped Fungus | Warped Stem, Warped Wart Block, Twisting Vines | Use Warped Nylium soil |

### Crops & Seeds

| Plant | Primary Drops | Notes |
|---|---|---|
| Wheat Seeds | Wheat, Wheat Seeds | — |
| Carrot | Carrots | — |
| Potato | Potatoes, Poisonous Potato | — |
| Beetroot Seeds | Beetroot, Beetroot Seeds | — |
| Melon Seeds | Melon Slice | — |
| Pumpkin Seeds | Pumpkin | — |
| Nether Wart | Nether Wart | Use Soul Sand soil |
| Sweet Berries | Sweet Berries | — |
| Glow Berries | Glow Berries | — |
| Pitcher Pod | Pitcher Plant | — |
| Torchflower Seeds | Torchflower | — |
| Bamboo | Bamboo | — |
| Sugar Cane | Sugar Cane | — |
| Cactus | Cactus | Use Sand soil |
| Chorus Flower | Chorus Fruit, Popped Chorus Fruit | Use End Stone soil |
| Kelp | Kelp | Requires water nearby |
| Lily Pad | Lily Pad | — |
| Brown Mushroom | Brown Mushroom | Use Mycelium or Podzol soil |
| Red Mushroom | Red Mushroom | Use Mycelium or Podzol soil |

---

## Apple Sapling Recipe

The Apple Sapling is a UC-specific sapling that grows in the Bonsai and drops apples along with oak logs. Craft it at a vanilla crafting table.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Apple"><img src="/images/items/apple.png"></div>
    <div class="crafting-slot" data-label="Oak Sapling"><img src="/images/items/oak_sapling.png"></div>
    <div class="crafting-slot" data-label="Apple"><img src="/images/items/apple.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Apple Sapling"><img src="/images/items/apple_sapling.png"></div>
</div>

*Pattern: `ASA` (single row) — Apple (A), Oak Sapling (S)*

