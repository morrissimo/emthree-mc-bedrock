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
3. *(Optional)* **Right-click with a soil block** to set the soil type — better soils harvest faster (soil changes growth *speed*, not drop *quantity*).
4. *(Optional)* **Right-click with a hoe** to manually trigger a harvest cycle, reducing the time to next growth.
5. **Place a hopper below** the Bonsai to collect drops automatically.

The Bonsai handles everything else — growth, harvesting, and outputting drops.

!!! tip "Breaking a Bonsai returns the soil and seed"
    Breaking a planted Bonsai drops the **bonsai block, the soil, and the seed** — nothing is lost. (This fixes an upstream UtilityCraft bug where the inserted items used to vanish on break.)

    You can also retrieve the contents *without* breaking the Bonsai:

    - **Sneak (crouch) + right-click with an empty hand** to pop out the sapling or seed.
    - Repeat with an empty hand (no sneaking required) to pop out the soil block.

---

## Soil Types

Right-click the Bonsai with a soil block to apply it. Soil changes **how fast** the Bonsai harvests — it does **not** change how much drops per harvest. The base cycle is **60 seconds**; better soils shorten it.

### Vanilla Soils

| Soil | Harvest Interval | Notes |
|---|---|---|
| Dirt | 60s | Default, no bonus |
| Grass Block | 50s | Slight speed boost |
| Sand | 60s | Required for cactus and desert plants |
| Red Sand | 50s | Alternative for sand-type plants |
| Soul Sand | 60s | Required for Nether Wart |
| Crimson Nylium | 60s | Required for Crimson Fungus |
| Warped Nylium | 60s | Required for Warped Fungus |
| End Stone | 60s | Required for Chorus Fruit |

Tilling a vanilla-soil Bonsai with a **hoe** shaves another ~10s off the cycle.

### UC Special Soils

UC special soils harvest much faster and **always work for any plant**, including all Bountiful Crops seeds regardless of tier. (They can't be tilled with a hoe.)

| Soil | Harvest Interval |
|---|---|
| Yellow Soil | 45s |
| Red Soil | 30s |
| Blue Soil | 30s |
| Black Soil | 10s |

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

**UC special soils (yellow/red/blue/black) always work for any tier** and harvest significantly faster on top.

!!! note "Drop amounts are per-harvest ranges"
    Tier 1 & 2 crops roll a random amount **each harvest**, and the low end is **0** — so some harvests come up empty. That's intended (the trade-off for fully passive output), not a bug. Every crop also has a flat **5% chance to drop a spare seed** for self-propagation. Tier 3 & 4 instead always drop exactly **1 shard/fragment** that crafts up 9 → 1.

### Tier 1 — Any vanilla soil

| Seed | Primary Drops (per harvest) |
|---|---|
| Coal Seeds | Coal ×0–3 |
| Copper Seeds | Raw Copper ×0–3 |
| Dyes Seeds | Random dye (16 colors, ~5% each) |
| Glass Seeds | Glass ×0–6 |
| Gunpowder Seeds | Gunpowder ×0–4 |
| Iron Seeds | Raw Iron ×0–3 |
| Leather Seeds | Leather ×0–4 |
| Prismarine Crystals Seeds | Prismarine Crystals ×0–5 |
| Prismarine Shards Seeds | Prismarine Shard ×0–5 |
| Water Seeds | Water Ball ×0–2 |
| Wool Seeds | Wool ×0–3 |

### Tier 2 — Sand, Red Sand, Soul Sand, Crimson/Warped Nylium, or End Stone

| Seed | Primary Drops (per harvest) |
|---|---|
| Ghast Seeds | Ghast Tear ×0–1 |
| Glowstone Seeds | Glowstone Dust ×0–3 |
| Gold Seeds | Raw Gold ×0–2 |
| Honey Seeds | Honey Ball ×0–2 |
| Lapis Seeds | Lapis Lazuli ×0–4 |
| Lava Seeds | Lava Ball ×0–2 |
| Quartz Seeds | Nether Quartz ×0–4 |
| Redstone Seeds | Redstone ×0–4 |
| Resin Seeds | Resin Clump ×0–2 |
| Slime Seeds | Slime Ball ×0–2 |

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
