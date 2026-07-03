# Machines

Most UtilityCraft machines are crafted at the **UC Workbench** and run on **UC energy** from a
generator or battery — power reaches them by **adjacency**, or over **energy cables** for
non-adjacent placement (see [Power System](power.md)). But a few of the blocks below run on
**player XP** or need **no power at all** — check the "Power source" column below.

For the foundational processing machines see also: [Crusher](crusher.md) and [Infuser](infuser.md).

## Energy specs

Values from the block definitions (buffer = energy storage, cost = energy per operation):

| Machine | Buffer | Cost / op | Power source |
|---|---|---|---|
| Electro Press | 64,000 | 800 | UC energy |
| Incinerator | 64,000 | 800 | UC energy |
| Induction Anvil | 64,000 | 1,000 | UC energy |
| Assembler | 256,000 | 1,600 | UC energy |
| Block Breaker | 64,000 | 200 | UC energy |
| Block Placer | 64,000 | 200 | UC energy |
| Harvester | 128,000 | 100 | UC energy |
| Auto Fisher | 512,000 | 6,400 | UC energy |
| Auto Sieve | 512,000 | 6,400 | UC energy |
| Digitizer | 32,000 | 400 | UC energy |
| Seed Synthesizer | 2,048,000 | 8,000 | UC energy |
| Magmatic Chamber | 640,000 | 8,000 | UC energy |
| **XP Condenser** | — | — | **player XP** (not energy) |
| **Way Center** | — | — | **XP levels** (not energy) |
| Fan, Ender Hopper, XP Magnet, Mob Grinder, Trash Can | — | — | **none** |
| **Mechanical Spawner** | — | — | **none** — mob essence |

---

## Processing

### Electro Press

Compresses items into plates and compressed blocks. The primary way to make iron, steel, gold, copper, and netherite plates used in advanced recipes.

> Requires UC power.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Piston"><img src="/images/items/piston.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Chip"><img src="/images/items/chip.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Chip"><img src="/images/items/chip.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Compressed Cobble"><img src="/images/items/compressed_cobblestone.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Electro Press"><img src="/images/items/machine_case.png"></div>
</div>

*Pattern: `PAP / CBC / PRP` — Redstone (P), Piston (A), Chip (C), Machine Case (B), Compressed Cobble (R)*

---

### Incinerator

UC's **powered smelter** (an electric furnace). Feed it dusts, raw materials, or ores and it outputs the **smelted result** — `iron_dust → iron ingot`, `raw_steel → steel ingot`, `gold_dust → gold ingot`, `cobbled_deepslate → deepslate`, etc. — running on UC energy instead of fuel. Pairs with the [Crusher](crusher.md) for a fuel-free ore-doubling line (crush → smelt). It uses a **curated** recipe set (mainly UC dusts/raws + a few stone conversions), not every vanilla furnace recipe.

> Requires UC power (64,000 buffer, 800 / op).

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Blast Furnace"><img src="/images/items/blast_furnace.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Incinerator"><img src="/images/items/incinerator.png"></div>
</div>

---

### Induction Anvil

A powered anvil that repairs and combines items without consuming experience levels. Place the item to repair and its repair material (or an identical item) in the input slots.

> Requires UC power.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Anvil"><img src="/images/items/anvil.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Induction Anvil"><img src="/images/items/induction_anvil.png"></div>
</div>

*Pattern: `CAC / EBE / CDC` — Gold Plate (C), Anvil (A), Advanced Chip (E), Machine Case (B), Redstone Block (D)*

---

### Assembler

An automated crafting machine. Load a Blueprint (made in the Digitizer) and it will craft that recipe automatically from items fed by hoppers.

> Requires UC power.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Iron Plate"><img src="/images/items/iron_plate.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Iron Plate"><img src="/images/items/iron_plate.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Crafter"><img src="/images/items/crafter.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Assembler"><img src="/images/items/assembler.png"></div>
</div>

*Pattern: `PIP / IMI / SRS` — Iron Plate (P), Expert Chip (I), Machine Case (M), Steel Plate (S), Crafter (R)*

> **Note:** The center-bottom slot requires a vanilla **Crafter** block (crafting_table mechanic block added in 1.21).

---

### XP Condenser

Collects and stores experience orbs from nearby sources, converting them into bottled XP or storing them for later use.

> Runs on **player XP**, not UC energy — no generator required.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Emerald Dust"><img src="/images/items/emerald_dust.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Emerald Dust"><img src="/images/items/emerald_dust.png"></div>
    <div class="crafting-slot" data-label="Lapis Block"><img src="/images/items/lapis_lazuli.png"></div>
    <div class="crafting-slot" data-label="Emerald Dust"><img src="/images/items/emerald_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="XP Condenser"><img src="/images/items/machine_case.png"></div>
</div>

*Pattern: `CAC / EBE / ADA` — Steel Plate (C), Emerald Dust (A), Expert Chip (E), Machine Case (B), Lapis Block (D)*

> No dedicated texture found for the XP Condenser output icon.

---

## Automation

### Block Breaker

Breaks the block in front of it and drops the items into an adjacent hopper or chest. It runs **continuously while powered** — no redstone signal needed.

> Requires UC power (64,000 buffer, 200 / op).

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Iron Pickaxe"><img src="/images/items/iron_pickaxe.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Chip"><img src="/images/items/chip.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Chip"><img src="/images/items/chip.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Iron Plate"><img src="/images/items/iron_plate.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Block Breaker"><img src="/images/items/block_breaker.png"></div>
</div>

---

### Block Placer

Places the block from its inventory into the world directly in front of it. Feed blocks via hopper.

> Requires UC power.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Dropper"><img src="/images/items/dropper.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Chip"><img src="/images/items/chip.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Chip"><img src="/images/items/chip.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Iron Plate"><img src="/images/items/iron_plate.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Block Placer"><img src="/images/items/block_placer.png"></div>
</div>

---

### Harvester

Automatically harvests crops in front of it when powered — a **3×3 area at base**, expanding up to **9×9** with range upgrades. Works with any vanilla plantable crop. Place it at the edge of your farm facing the crops.

> Requires UC power.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Iron Hoe"><img src="/images/items/iron_hoe.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Harvester"><img src="/images/items/harvester.png"></div>
</div>

---

### Auto Fisher

Automatically fishes, including treasure and enchanted book drops. Place near water and keep it powered — it handles the rod itself.

> Requires UC power.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Fishing Rod"><img src="/images/items/fishing_rod.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Steel Block"><img src="/images/items/steel_block.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Auto Fisher"><img src="/images/items/autofisher.png"></div>
</div>

---

### Auto Sieve

Powered version of the UC Sieve. Feed it gravel, sand, dust, or other sieveable materials via hopper and it processes them automatically.

> Requires UC power.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Sieve"><img src="/images/items/sieve.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Chip"><img src="/images/items/chip.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Chip"><img src="/images/items/chip.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Gold Block"><img src="/images/items/gold_block.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Auto Sieve"><img src="/images/items/autosieve.png"></div>
</div>

*Requires a UC Sieve item (crafted separately) in the recipe.*

---

## Mob Farm

The **Mechanical Spawner** is the mob *source*; pair it with a Mob Grinder (kills), Fan (funnels), and Ender Hopper (collects) for a fully automatic mob farm.

### Mechanical Spawner

A configurable spawner — load it with a mob **essence** and it spawns that mob right next to itself, over and over, while switched on. **No UC power and no per-spawn cost:** once it's assigned a mob and toggled on, it just runs.

> No power required — runs on essence (see below).

Build the **Spawner Core** first, then the Spawner itself (both at the **UC Workbench**):

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Soul Sand"><img src="/images/items/soul_sand.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Soul Sand"><img src="/images/items/soul_sand.png"></div>
    <div class="crafting-slot" data-label="Diamond Block"><img src="/images/items/diamond_block.png"></div>
    <div class="crafting-slot" data-label="Soul Sand"><img src="/images/items/soul_sand.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Soul Sand"><img src="/images/items/soul_sand.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Spawner Core"><img src="/images/items/spawner_core.png"></div>
</div>

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Crying Obsidian"><img src="/images/items/crying_obsidian.png"></div>
    <div class="crafting-slot" data-label="Diamond"><img src="/images/items/diamond.png"></div>
    <div class="crafting-slot" data-label="Crying Obsidian"><img src="/images/items/crying_obsidian.png"></div>
    <div class="crafting-slot" data-label="Iron Bars"><img src="/images/items/iron_bars.png"></div>
    <div class="crafting-slot" data-label="Spawner Core"><img src="/images/items/spawner_core.png"></div>
    <div class="crafting-slot" data-label="Iron Bars"><img src="/images/items/iron_bars.png"></div>
    <div class="crafting-slot" data-label="Crying Obsidian"><img src="/images/items/crying_obsidian.png"></div>
    <div class="crafting-slot" data-label="Iron Bars"><img src="/images/items/iron_bars.png"></div>
    <div class="crafting-slot" data-label="Crying Obsidian"><img src="/images/items/crying_obsidian.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Mechanical Spawner"><img src="/images/items/mechanical_spawner.png"></div>
</div>

*Spawner Core: `RSR / SBS / RSR` — Redstone Block (R), Soul Sand (S), Diamond Block (B). Spawner: `ODO / ICI / OIO` — Crying Obsidian (O), Diamond (D), Iron Bars (I), Spawner Core (C).*

**Using it:** hold a mob **essence** and **sneak + interact** to assign that mob ("Assigned X Essence!"). Interact again (no sneak) to toggle it **on** — it then spawns the mob beside itself on a repeating timer. Sneak + a **glass bottle** pops the essence back out so you can swap mobs.

#### Getting essence — the Essence Vessel

Essences aren't crafted directly; you farm them with an **Essence Vessel** (vanilla crafting table):

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Lapis Lazuli"><img src="/images/items/lapis_lazuli.png"></div>
    <div class="crafting-slot" data-label="Soul Soil"><img src="/images/items/soul_soil.png"></div>
    <div class="crafting-slot" data-label="Lapis Lazuli"><img src="/images/items/lapis_lazuli.png"></div>
    <div class="crafting-slot" data-label="Soul Sand"><img src="/images/items/soul_sand.png"></div>
    <div class="crafting-slot" data-label="Glass Bottle"><img src="/images/items/glass_bottle.png"></div>
    <div class="crafting-slot" data-label="Soul Sand"><img src="/images/items/soul_sand.png"></div>
    <div class="crafting-slot" data-label="Lapis Lazuli"><img src="/images/items/lapis_lazuli.png"></div>
    <div class="crafting-slot" data-label="Soul Soil"><img src="/images/items/soul_soil.png"></div>
    <div class="crafting-slot" data-label="Lapis Lazuli"><img src="/images/items/lapis_lazuli.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Essence Vessel"><img src="/images/items/essence_vessel.png"></div>
</div>

1. **Use the empty vessel on a live target mob to *tag* it.** This sacrifices that one mob to lock the vessel to its type, but captures **no essence yet** — the vessel starts at **0%**. (Using it just picks the mob; it doesn't fill anything.)
2. **Fill it by killing that mob type with the vessel in your off-hand.** This is where *all* the progress comes from — **+1–5% per kill** (so roughly **20–100 kills** to fill one vessel), shown as a live % on the action bar.
3. At **100%** the vessel becomes that mob's **Essence**, ready to load into a Mechanical Spawner.

#### Quantity Upgrade

Apply to a spawner to raise how many mobs it spawns per cycle (up to ~3× the base count, with a bonus roll at max). Crafted at the **UC Workbench**:

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Cyan Dye"><img src="/images/items/cyan_dye.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Lapis Block"><img src="/images/items/lapis_block.png"></div>
    <div class="crafting-slot" data-label="Base Upgrade"><img src="/images/items/base_upgrade.png"></div>
    <div class="crafting-slot" data-label="Lapis Block"><img src="/images/items/lapis_block.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Spawner Core"><img src="/images/items/spawner_core.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Quantity Upgrade"><img src="/images/items/quantity_upgrade.png"></div>
</div>

#### Capturable mobs

Blaze, Chicken, Cow, Creeper, Enderman, Guardian (& Elder Guardian), Hoglin, Illager (Pillager / Vindicator / Evoker / Witch), Magma Cube, Mooshroom, Pig, Piglin, Sheep, Skeleton, Slime, Spider, Wither Skeleton, Zombie.

---

### Mob Grinder

Damages and kills mobs within its effect radius (not just those directly on top). Combine with spawners or mob farms to automate mob drops. **No power required** — toggle it on/off via its own in-block menu (no redstone).

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Iron Sword"><img src="/images/items/iron_sword.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Iron Sword"><img src="/images/items/iron_sword.png"></div>
    <div class="crafting-slot" data-label="Cobblestone"><img src="/images/items/cobblestone.png"></div>
    <div class="crafting-slot" data-label="Cobblestone"><img src="/images/items/cobblestone.png"></div>
    <div class="crafting-slot" data-label="Cobblestone"><img src="/images/items/cobblestone.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Mob Grinder"><img src="/images/items/mob_grinder.png"></div>
</div>

*Pattern: ` I / SRS / CCC` — Iron Ingot (I), Iron Sword (S), Redstone Block (R), Cobblestone (C)*

---

### Fan

Pushes entities (including mobs and items) in the direction it faces. Useful for funneling mobs into a grinder or items into a hopper.

> **No power required** — it just applies directional knockback (its range is set in-block).

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Fan"><img src="/images/items/fan.png"></div>
</div>

---

### Ender Hopper

A wireless hopper that collects item drops in a large radius around it — no need for items to physically fall into it. Great for mob farm collection rooms.

*No UC power required.*

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Obsidian"><img src="/images/items/obsidian.png"></div>
    <div class="crafting-slot" data-label="Ender Eye"><img src="/images/items/ender_eye.png"></div>
    <div class="crafting-slot" data-label="Obsidian"><img src="/images/items/obsidian.png"></div>
    <div class="crafting-slot" data-label="Obsidian"><img src="/images/items/obsidian.png"></div>
    <div class="crafting-slot" data-label="Chest"><img src="/images/items/chest.png"></div>
    <div class="crafting-slot" data-label="Obsidian"><img src="/images/items/obsidian.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Obsidian"><img src="/images/items/obsidian.png"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Ender Hopper"><img src="/images/items/ender_hopper.png"></div>
</div>

*Pattern: `OEO / OCO / _O_` — Obsidian (O), Ender Eye (E), Chest (C)*

---

### XP Magnet

Pulls experience orbs from a wide area into itself, storing them for later retrieval via right-click or piping into an XP Condenser.

*No UC power required.*

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Experience Bottle"><img src="/images/items/experience_bottle.png"></div>
    <div class="crafting-slot" data-label="Experience Bottle"><img src="/images/items/experience_bottle.png"></div>
    <div class="crafting-slot" data-label="Experience Bottle"><img src="/images/items/experience_bottle.png"></div>
    <div class="crafting-slot" data-label="Experience Bottle"><img src="/images/items/experience_bottle.png"></div>
    <div class="crafting-slot" data-label="Ender Eye"><img src="/images/items/ender_eye.png"></div>
    <div class="crafting-slot" data-label="Experience Bottle"><img src="/images/items/experience_bottle.png"></div>
    <div class="crafting-slot" data-label="Experience Bottle"><img src="/images/items/experience_bottle.png"></div>
    <div class="crafting-slot" data-label="Experience Bottle"><img src="/images/items/experience_bottle.png"></div>
    <div class="crafting-slot" data-label="Experience Bottle"><img src="/images/items/experience_bottle.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="XP Magnet"><img src="/images/items/xp_magnet.png"></div>
</div>

---

## Misc

### Way Center

A teleportation hub block. Right-click to set a named waypoint; right-click again to teleport to any stored waypoint. Excellent for large bases or long-distance travel.

> Charges each teleport in **XP levels**, not UC energy — no generator required.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Ender Eye"><img src="/images/items/ender_eye.png"></div>
    <div class="crafting-slot" data-label="Echo Shard"><img src="/images/items/echo_shard.png"></div>
    <div class="crafting-slot" data-label="Ender Eye"><img src="/images/items/ender_eye.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Lapis Block"><img src="/images/items/lapis_lazuli.png"></div>
    <div class="crafting-slot" data-label="Diamond Dust"><img src="/images/items/diamond_dust.png"></div>
    <div class="crafting-slot" data-label="Lapis Block"><img src="/images/items/lapis_lazuli.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Way Center"><img src="/images/items/machine_case.png"></div>
</div>

*Pattern: `CAC / EBE / FDF` — Ender Eye (C), Echo Shard (A), Expert Chip (E), Machine Case (B), Lapis Block (F), Diamond Dust (D)*

> No dedicated Way Center texture found in the RP — recipe visual uses Machine Case as placeholder.

---

### Digitizer

Creates Blueprints from existing crafting recipes. Place items in the input slots matching a recipe shape, and it outputs a Blueprint for the Assembler.

> Requires UC power.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Iron Plate"><img src="/images/items/iron_plate.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Iron Plate"><img src="/images/items/iron_plate.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Blueprint Paper"><img src="/images/items/blueprint_paper.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Digitizer"><img src="/images/items/digitizer.png"></div>
</div>

*Pattern: `PIP / IMI / SRS` — Iron Plate (P), Expert Chip (I), Machine Case (M), Steel Plate (S), Blueprint Paper (R)*

---

### Seed Synthesizer

Generates UC crop seeds (iron, gold, diamond, etc.) from base materials. Required to unlock the Bountiful Crops farming system.

> Requires UC power.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Amethyst Shard"><img src="/images/items/amethyst_shard.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Seed Synthesizer"><img src="/images/items/machine_case.png"></div>
</div>

*Pattern: `CAC / EBE / CDC` — Gold Plate (C), Amethyst Shard (A), Expert Chip (E), Machine Case (B), Redstone Block (D)*

> No dedicated Seed Synthesizer texture found — recipe visual uses Machine Case as placeholder.

---

### Magmatic Chamber

Converts lava into useful resources — produces obsidian, stone, or other thermal outputs depending on configuration. Works as a passive processing block.

> Requires UC power.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Copper Plate"><img src="/images/items/copper_plate.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Netherite Plate"><img src="/images/items/netherite_plate.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Magmatic Chamber"><img src="/images/items/magmatic_chamber.png"></div>
</div>

*Pattern: `CAC / EBE / FDF` — Gold Plate (C), Copper Plate (A), Advanced Chip (E), Machine Case (B), Redstone Block (F), Netherite Plate (D)*

---

### Trash Can

Destroys items permanently. Right-click to open, drop in anything you want gone. Does not require power.

*No UC power required.*

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Barrel"><img src="/images/items/barrel.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Flint & Steel"><img src="/images/items/flint_and_steel.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Trash Can"><img src="/images/items/trash_can.png"></div>
</div>

*Crafted at the **UC Workbench**. Result identifier: `utilitycraft:basic_trash_can`.*
