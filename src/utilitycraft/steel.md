# Steel & Smeltflare

Steel is the gateway material for all of UtilityCraft. It is **manufactured**, not mined — no steel ore spawns in the world.

## Crafting Chain

### Step 1 — smeltflare (vanilla crafting table, shapeless)

**With coal:**

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Paper ×2"><img src="/images/items/paper.png"><span class="stack">2</span></div>
    <div class="crafting-slot" data-label="Coal"><img src="/images/items/coal.png"></div>
    <div class="crafting-slot" data-label="Flint"><img src="/images/items/flint.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Smeltflare ×8"><img src="/images/items/smeltflare.png"><span class="stack">8</span></div>
</div>

**With charcoal:**

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Paper ×2"><img src="/images/items/paper.png"><span class="stack">2</span></div>
    <div class="crafting-slot" data-label="Charcoal"><img src="/images/items/charcoal.png"></div>
    <div class="crafting-slot" data-label="Flint"><img src="/images/items/flint.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Smeltflare ×8"><img src="/images/items/smeltflare.png"><span class="stack">8</span></div>
</div>

Smeltflare is a catalyst/fuel item used in the steel chain. Stock up — you need it twice in the full process.

### Step 2 — raw_steel (vanilla crafting table, shapeless)

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Coal"><img src="/images/items/coal.png"></div>
    <div class="crafting-slot" data-label="Raw Iron"><img src="/images/items/raw_iron.png"></div>
    <div class="crafting-slot" data-label="Smeltflare"><img src="/images/items/smeltflare.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Raw Steel"><img src="/images/items/raw_steel.png"></div>
</div>

### Step 3 — steel_ingot (two options)

**Option A — Furnace/blast furnace (smelting):**

<div class="crafting-recipe">
  <div class="crafting-output" data-label="Raw Steel"><img src="/images/items/raw_steel.png"></div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
</div>

**Option B — Crafting table shortcut (shapeless):**

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Smeltflare"><img src="/images/items/smeltflare.png"></div>
    <div class="crafting-slot" data-label="Raw Steel"><img src="/images/items/raw_steel.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
</div>

This skips the furnace entirely, consuming a second smeltflare.

### Step 4 — steel_block (vanilla crafting table)

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Steel Block"><img src="/images/items/steel_block.png"></div>
</div>

## Usage

Steel ingots and blocks are used throughout the mod:

- [UC Workbench](workbench.md) build recipe
- [Machine Case](machine_case.md)
- [Chips](chips.md) — `chip` recipe uses steel_ingot
- [Crusher](crusher.md) and [Infuser](infuser.md) build recipes
- Generator builds (all tiers)
- Hammer recipes
- Plates (via Electro Press, required for advanced+ tier upgrades)

## Notes

- You can chain-produce: make a batch of smeltflare, use half for raw_steel, use the other half to skip furnace smelting
- The smeltflare shortcut is useful early-game when fuel or furnace access is limited
