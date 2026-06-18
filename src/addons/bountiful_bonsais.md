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

Right-click the Bonsai with a soil block to apply it. The base growth cycle is **60 seconds** with no soil bonus.

### Vanilla Soils

| Soil | Growth Bonus | Yield Multiplier | Notes |
|---|---|---|---|
| Dirt | — | 1× | Default, no bonus |
| Grass Block | ~17% faster | 1× | Slight speed improvement |
| Sand | — | 1× | Required for cactus and desert plants |
| Red Sand | ~17% faster | 1× | Alternative for sand-type plants |
| Soul Sand | — | 1× | Required for Nether Wart |
| Crimson Nylium | — | 1× | Required for Crimson Fungus |
| Warped Nylium | — | 1× | Required for Warped Fungus |
| End Stone | — | 1× | Required for Chorus Fruit |

### UC Special Soils

UC special soils provide much stronger bonuses and **always work for any plant**, including all Bountiful Crops seeds regardless of tier.

| Soil | Growth Bonus | Yield Multiplier |
|---|---|---|
| Yellow Soil | 25% faster | 1× |
| Red Soil | 50% faster | 1× |
| Blue Soil | 50% faster | 2× |
| Black Soil | 83% faster | 4× |

---

## Supported Plants

### Trees (Saplings)

| Plant | Soil | Primary Drops |
|---|---|---|
| Oak Sapling | Dirt / Grass | Oak Log, Apple, Stick |
| Birch Sapling | Dirt / Grass | Birch Log, Stick |
| Spruce Sapling | Dirt / Grass | Spruce Log, Stick |
| Jungle Sapling | Dirt / Grass | Jungle Log, Cocoa Beans, Stick |
| Acacia Sapling | Dirt / Grass | Acacia Log, Stick |
| Dark Oak Sapling | Dirt / Grass | Dark Oak Log, Apple, Stick |
| Cherry Sapling | Dirt / Grass | Cherry Log, Pink Petals, Stick |
| Mangrove Propagule | Dirt / Grass | Mangrove Log, Mud, Stick |
| Pale Oak Sapling | Dirt / Grass | Pale Oak Log, Stick |
| Azalea | Dirt / Grass | Azalea, Oak Log |
| Flowering Azalea | Dirt / Grass | Flowering Azalea, Oak Log |
| **Apple Sapling** | Dirt / Grass | Apple, Oak Log |

*Apple Sapling is a UC-specific item — see recipe below.*

### Nether Plants

| Plant | Soil | Primary Drops |
|---|---|---|
| Crimson Fungus | Crimson Nylium only | Crimson Stem, Nether Wart Block, Weeping Vines |
| Warped Fungus | Warped Nylium only | Warped Stem, Warped Wart Block, Twisting Vines |
| Nether Wart | Soul Sand only | Nether Wart |

### Crops & Seeds

| Plant | Soil | Primary Drops |
|---|---|---|
| Wheat Seeds | Dirt / Grass | Wheat, Wheat Seeds |
| Carrot | Dirt / Grass | Carrots |
| Potato | Dirt / Grass | Potatoes, Poisonous Potato |
| Beetroot Seeds | Dirt / Grass | Beetroot, Beetroot Seeds |
| Melon Seeds | Dirt / Grass | Melon Slice |
| Pumpkin Seeds | Dirt / Grass | Pumpkin |
| Sweet Berries | Dirt / Grass | Sweet Berries |
| Bamboo | Dirt / Grass | Bamboo |
| Sugar Cane | Dirt / Grass / Sand / Red Sand | Sugar Cane |
| Kelp | Sand / Red Sand / Dirt / Grass | Kelp |
| Cactus | Sand / Red Sand only | Cactus |
| Chorus Fruit | End Stone only | Chorus Fruit, Popped Chorus Fruit |
| Brown Mushroom | Dirt / Grass | Brown Mushroom |
| Red Mushroom | Dirt / Grass | Red Mushroom |

---

## Bountiful Crops Seeds

With the **Bountiful Crops Bonsai** addon installed, all 32 Bountiful Crops resource seeds can be planted in a Bonsai. Soil requirements are tier-gated — higher-tier seeds need rarer soils.

**UC special soils (yellow/red/blue/black) always work for any tier** and provide significant growth and yield bonuses on top.

### Tier 1 — Any vanilla soil

| Seed | Primary Drops |
|---|---|
| Coal Seeds | Coal ×2–4 |
| Copper Seeds | Raw Copper ×2–4 |
| Dyes Seeds | Random dye (16 colors) |
| Glass Seeds | Glass ×8–16 |
| Gunpowder Seeds | Gunpowder ×4–8 |
| Iron Seeds | Raw Iron ×1–3 |
| Leather Seeds | Leather ×4–8 |
| Prismarine Crystals Seeds | Prismarine Crystals ×8–12 |
| Prismarine Shards Seeds | Prismarine Shard ×8–12 |
| Water Seeds | Water Ball ×1–2 |
| Wool Seeds | Wool ×2–4 |

### Tier 2 — Sand, Red Sand, Soul Sand, Crimson/Warped Nylium, or End Stone

| Seed | Primary Drops |
|---|---|
| Ghast Seeds | Ghast Tear ×1–2 |
| Glowstone Seeds | Glowstone Dust ×2–4 |
| Gold Seeds | Raw Gold ×1–3 |
| Honey Seeds | Honey Ball ×1–2 |
| Lapis Seeds | Lapis Lazuli ×4–9 |
| Lava Seeds | Lava Ball ×1–2 |
| Quartz Seeds | Nether Quartz ×4–8 |
| Redstone Seeds | Redstone ×3–8 |
| Resin Seeds | Resin Clump ×1–2 |
| Slime Seeds | Slime Ball ×1–3 |

### Tier 3 — Soul Sand, Crimson/Warped Nylium, or End Stone

| Seed | Primary Drops |
|---|---|
| Amethyst Seeds | Amethyst Shard ×2–4 |
| Blaze Seeds | Blaze Rod ×1–2 |
| Diamond Seeds | Diamond Shard ×1 (9 → 1 Diamond) |
| Emerald Seeds | Emerald Shard ×1 (9 → 1 Emerald) |
| Ender Pearl Seeds | Ender Pearl ×1 |
| Obsidian Seeds | Obsidian ×1–2 |

### Tier 4 — End Stone only (or any UC special soil)

| Seed | Primary Drops |
|---|---|
| Netherite Seeds | Netherite Nugget ×1 (9 → 1 Netherite Ingot) |
| Nether Star Seeds | Nether Star Fragment ×1 (9 → 1 Nether Star) |
| Shulker Seeds | Shulker Shell Shard ×1 (9 → 1 Shulker Shell) |
| Totem Seeds | Totem Shard ×1 (9 → 1 Totem of Undying) |
| Wither Seeds | Wither Skull Shard ×1 (9 → 1 Wither Skeleton Skull) |

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
