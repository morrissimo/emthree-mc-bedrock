# Machine Upgrades

Most UC machines and transport blocks can be boosted with **upgrade items**. *How* you apply one depends on the target — UC uses two systems:

- **Processing machines** (Crusher, Infuser, Harvester, Auto Sieve, Assembler, Seed Synthesizer, Auto Fisher…): open the machine and drop upgrades into its **upgrade slots**. These accept **Speed**, **Energy**, and **Range** (stack them for higher levels).
- **Transport & simple blocks** (Mechanical Hoppers/Uppers/Droppers, pipes, Mob Grinder, Mechanical Spawner, Way Center, Fan): **hold the upgrade and right-click the block** — each use bumps a level. **Breaking the block returns the applied upgrades.** These accept **Filter**, **Damage**, **Quantity** (plus Range/Speed on some).

## The upgrades

| Upgrade | What it does | How it's applied | Cap |
|---|---|---|---|
| <img src="/images/items/base_upgrade.png" width="16"> **Base** | Crafting core only — the center of every other upgrade recipe | (not applied) | — |
| <img src="/images/items/speed_upgrade.png" width="16"> **Speed** | Faster processing, at the cost of more energy draw. Slot machines scale up to ~**10×** at level 8; on a Spawner/Hopper it shortens the cycle interval | slot **or** interact | 8 (slot) / 4 (block) |
| <img src="/images/items/energy_upgrade.png" width="16"> **Energy** | Cheaper per-operation energy — roughly **−20% per level** (levels 1–4), trending to about **−95%** by level 8. Offsets Speed's added draw | slot | 8 |
| <img src="/images/items/range_upgrade.png" width="16"> **Range** | Bigger work area — Harvester **3×3 → 5×5 → 7×7…**, Mob Grinder reach (0.5–2.5 blocks), hopper/pipe distance | slot **or** interact | 8 (slot) / 4 (block) |
| <img src="/images/items/filter_upgrade.png" width="16"> **Filter** | Enables item **filtering** on transport blocks (opens a whitelist/blacklist menu on the hopper/pipe/importer) | interact | 1 |
| <img src="/images/items/damage_upgrade.png" width="16"> **Damage** | Raises the **Mob Grinder's** damage per hit | interact (grinder) | 8 |
| <img src="/images/items/quantity_upgrade.png" width="16"> **Quantity** | More mobs per **Mechanical Spawner** cycle | interact (spawner) | 4 |

## Recipes

Everything is crafted at the **UC Crafter**. The **Base Upgrade** is the shared core:

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Gold Ingot"><img src="/images/items/gold_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Base Upgrade"><img src="/images/items/base_upgrade.png"></div>
</div>

Each of the other six puts a **Base Upgrade in the center** and rings it with materials:

| Upgrade | Corners | Top | Sides | Bottom |
|---|---|---|---|---|
| Speed | steel plate | emerald dust | redstone block | emerald block |
| Energy | steel plate | diamond dust | diamond dust | redstone block |
| Range | steel plate | blue dye | redstone | gold ingot |
| Filter | redstone | comparator | steel ingot | hopper |
| Damage | steel plate | iron sword | energized iron dust | redstone block |
| Quantity | steel ingot | cyan dye | lapis block | spawner core |
