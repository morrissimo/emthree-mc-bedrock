# Sieve

The **Sieve** sifts cheap, bulk blocks — gravel, sand, dirt, soul sand, and crusher "crushed" blocks — into useful resources (ore chunks, seeds, flowers, nether goodies, and more). It's one of UC's core early/mid-game resource multipliers. Sift by hand, or automate it with the [Auto Sieve](machines.md).

The key knob is the **mesh** you install: a better mesh unlocks rarer drops **and** boosts every drop's odds.

## Crafting the Sieve

Crafted at a **vanilla crafting table**:

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Planks"><img src="/images/items/planks.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Planks"><img src="/images/items/planks.png"></div>
    <div class="crafting-slot" data-label="Planks"><img src="/images/items/planks.png"></div>
    <div class="crafting-slot" data-label="Wooden Slab"><img src="/images/items/wooden_slab.png"></div>
    <div class="crafting-slot" data-label="Planks"><img src="/images/items/planks.png"></div>
    <div class="crafting-slot" data-label="Stick"><img src="/images/items/stick.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Stick"><img src="/images/items/stick.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Sieve"><img src="/images/items/sieve.png"></div>
</div>

## How to use

1. **Install a mesh** — right-click the sieve holding a mesh (only the 8 UC meshes below work; anything else is rejected). Right-clicking with a different mesh swaps it; **sneak + empty hand** pops the mesh back out when the sieve is idle.
2. **Load material** — right-click with an accepted block (see [inputs](#sieve-drops)). This consumes 1 block.
3. **Sift** — keep right-clicking (~4 clicks) until it finishes; the drops pop out on top of the sieve.

!!! tip "One click sifts a whole field"
    Interacting with a sieve also advances **every sieve in a 5×5 area** around it. Lay out a grid of sieves, load them, and a single click drives them all. **Compressed** inputs (compressed gravel/dirt/etc.) sift into **9×** the normal output.

## Meshes

The mesh sets your results in two ways: it **unlocks** drops (a drop only appears once your mesh's *tier* ≥ the drop's listed tier), and its **multiplier** scales every drop's chance (`chance × multiplier`).

| Mesh | Tier | Drop multiplier | Crafted at |
|---|---|---|---|
| <img src="/images/items/string_mesh.png" width="16"> String | 0 | ×0.75 | crafting table |
| <img src="/images/items/flint_mesh.png" width="16"> Flint | 1 | ×1.0 | crafting table |
| <img src="/images/items/copper_mesh.png" width="16"> Copper | 2 | ×1.25 | crafting table |
| <img src="/images/items/iron_mesh.png" width="16"> Iron | 3 | ×1.5 | crafting table |
| <img src="/images/items/golden_mesh.png" width="16"> Golden | 4 | ×2.0 | crafting table |
| <img src="/images/items/emerald_mesh.png" width="16"> Emerald | 5 | ×2.5 | crafting table |
| <img src="/images/items/diamond_mesh.png" width="16"> Diamond | 6 | ×3.0 | crafting table |
| <img src="/images/items/netherite_mesh.png" width="16"> Netherite | 7 | ×4.0 | smithing table |

- Drop tiers cap at **5**, so an **Emerald mesh already unlocks every drop** — Diamond and Netherite only add bigger multipliers.
- Because `chance × multiplier` can exceed 1.0, high-tier meshes effectively **guarantee** common drops.
- **Netherite** trades away one thing: it stops gravel from yielding flint, in exchange for its ×4 multiplier.

### Mesh recipes

The **String Mesh** is the base:

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="String"><img src="/images/items/string.png"></div>
    <div class="crafting-slot" data-label="Stick"><img src="/images/items/stick.png"></div>
    <div class="crafting-slot" data-label="String"><img src="/images/items/string.png"></div>
    <div class="crafting-slot" data-label="Stick"><img src="/images/items/stick.png"></div>
    <div class="crafting-slot" data-label="String"><img src="/images/items/string.png"></div>
    <div class="crafting-slot" data-label="Stick"><img src="/images/items/stick.png"></div>
    <div class="crafting-slot" data-label="String"><img src="/images/items/string.png"></div>
    <div class="crafting-slot" data-label="Stick"><img src="/images/items/stick.png"></div>
    <div class="crafting-slot" data-label="String"><img src="/images/items/string.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="String Mesh"><img src="/images/items/string_mesh.png"></div>
</div>

Every higher tier is a **ring of that tier's material around the previous mesh** — e.g. the Flint Mesh:

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Flint"><img src="/images/items/flint.png"></div>
    <div class="crafting-slot" data-label="Flint"><img src="/images/items/flint.png"></div>
    <div class="crafting-slot" data-label="Flint"><img src="/images/items/flint.png"></div>
    <div class="crafting-slot" data-label="Flint"><img src="/images/items/flint.png"></div>
    <div class="crafting-slot" data-label="String Mesh"><img src="/images/items/string_mesh.png"></div>
    <div class="crafting-slot" data-label="Flint"><img src="/images/items/flint.png"></div>
    <div class="crafting-slot" data-label="Flint"><img src="/images/items/flint.png"></div>
    <div class="crafting-slot" data-label="Flint"><img src="/images/items/flint.png"></div>
    <div class="crafting-slot" data-label="Flint"><img src="/images/items/flint.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Flint Mesh"><img src="/images/items/flint_mesh.png"></div>
</div>

Same ring for the rest, swapping the outer material and the previous mesh in the center: **Copper** (copper ingot + flint mesh), **Iron** (iron ingot + copper mesh), **Golden** (gold ingot + iron mesh), **Emerald** (emerald + golden mesh), **Diamond** (diamond + emerald mesh). The **Netherite Mesh** is a **smithing table** upgrade: netherite upgrade template + Diamond Mesh + netherite ingot.

## Sieve drops

Sifting an input rolls its drop table. Listed **chance is the base** (before the mesh multiplier); the **min mesh** column is the mesh tier you need before that drop can appear at all. The `_chunk` items are UC intermediates that process into the real ingots/gems.

**Gravel**

| Drop | Base chance | Min mesh |
|---|---|---|
| Flint | 20% | String (t0, *gone at Netherite*) |
| Coal chunk | 25% | String (t0) |
| Iron chunk | 15% | Flint (t1) |
| Gold chunk | 5% | Iron (t3) |
| Lapis chunk | 2.5% | Iron (t3) |
| Emerald chunk | 2% | Golden (t4) |
| Diamond chunk | 1% | Golden (t4) |

**Sand**

| Drop | Base chance | Min mesh |
|---|---|---|
| Copper chunk | 25% | Flint (t1) |
| Bone meal | 25% | String (t0) |
| Redstone chunk | 20% | Copper (t2) |
| Gunpowder / Glowstone dust | 12% / 8% | String (t0) |
| Prismarine shard / crystals, Clay | 10% each | Copper (t2) |
| Blaze powder | 10% | Iron (t3) |
| Cactus / Kelp | 10% each | String (t0) |
| Conduit | 0.5% | Golden (t4) |

**Dirt** → 18 crops & saplings (carrot, potato, every seed, sugar cane, bamboo, and every sapling incl. cherry/pale oak), **~10% each, String mesh**.

**Grass Block** → 6 flowers/plants (flowers, double plants, torchflower, pitcher plant, pink petals), **~20% each, String mesh**.

**Soul Sand**

| Drop | Base chance | Min mesh |
|---|---|---|
| Nether quartz chunk (+ 3× bonus roll) | 33% (+10%) | Flint (t1) |
| Bone / Nether wart | 15% / 12% | String (t0) |
| Warped / Crimson fungus | 10% each | String (t0) |
| Ghast tear | 8% | Golden (t4) |

**Crushed Netherrack** → nether quartz chunk 33% (Flint), gold nugget 20% + nether gold chunk 33% (Iron t3), **ancient debris chunk 2.5%** (Emerald t5).

**Crushed Endstone** → **needs Golden mesh (t4)**: chorus fruit 80%, ender pearl 16%, chorus flower 1%.

**Crushed Cobbled Deepslate** → deepslate coal chunk 30% (String), deepslate iron chunk 25% (Flint), deepslate lapis chunk 15% (Iron), deepslate gold/emerald/diamond chunks (Golden t4), **echo shard 5% + amethyst 1% + sculk catalyst 0.5%** (Emerald t5).

## Auto Sieve

The powered **[Auto Sieve](machines.md)** does all of the above automatically — same meshes, same drop table — consuming energy instead of clicks and depositing drops into its output. Install a mesh + speed/energy upgrades and feed it with a hopper.
