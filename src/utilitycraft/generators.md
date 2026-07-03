# Power System & Generators

UC machines need power, produced by **generators**. UC has several generator families — Magmators
(lava), Furnators (solid fuel), Solar Panels, Thermo Generators, and Wind Turbines. Power reaches
machines by **adjacency** (or over energy cables); see [Power System](power.md) for adjacency rules,
transfer modes, and cables.

**Magmator fuel:** a Magmator burns lava from its **own internal lava buffer** — you fill it
directly with lava buckets (or pipe lava in). There is **no** separate fluid tank placed underneath,
and every tier yields the **same 100 energy per mB** of lava (100,000 per bucket). Higher tiers just
burn faster and hold more; they don't extract more per bucket. (Fluid Tanks are standalone storage
blocks + a *crafting ingredient* in the recipes below — not something you place under the magmator.)

---

## Energy at a glance (basic tier)

Values from the block definitions. Each higher tier is roughly **4× the previous** in both buffer
and generation rate. Generators push **rate × 4** energy per tick into adjacent machines.

| Generator | Buffer | Gen rate / tick | Fuel buffer |
|---|---|---|---|
| Magmator | 80,000 | 50 | 32,000 mB lava (internal) |
| Furnator | 64,000 | 40 | solid-fuel slot |
| Solar Panel | 32,000 | 12 (noon peak) | — |
| Thermo Generator | 32,000 | 20 × heat mult | 2,000 mB water (internal) |
| Wind Turbine | 64,000 | 8 × altitude/weather | — |
| Battery | 256,000 | 100 (I/O) | — (stores only) |

Magmator lava yield is a flat **100 energy/mB** at every tier (100,000 per bucket).

---

## Magmators

Each tier is crafted by upgrading the previous one — you'll build all four in sequence.

### Basic Magmator

Entry-level lava generator. Sufficient to power a handful of low-tier machines.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Basic Fluid Tank"><img src="/images/items/basic_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Furnace"><img src="/images/items/furnace.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Basic Magmator"><img src="/images/items/basic_magmator.png"></div>
</div>

*Pattern: `GDG / EBE / SES` — Gold Plate (G), Basic Fluid Tank (D), Basic Chip (E), Furnace (B), Steel Plate (S)*

---

### Advanced Magmator

Significantly higher output than Basic. Upgrade by wrapping the Basic Magmator in new materials — keep your old one in the recipe.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Energized Iron Plate"><img src="/images/items/energized_iron_plate.png"></div>
    <div class="crafting-slot" data-label="Advanced Fluid Tank"><img src="/images/items/advanced_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Plate"><img src="/images/items/energized_iron_plate.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Basic Magmator"><img src="/images/items/basic_magmator.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Advanced Magmator"><img src="/images/items/advanced_magmator.png"></div>
</div>

*Pattern: `GDG / EBE / SES` — Energized Iron Plate (G), Advanced Fluid Tank (D), Advanced Chip (E), Basic Magmator (B), Steel Plate (S)*

---

### Expert Magmator

High-tier output for mid-to-late-game machine arrays. Requires Diamond Dust and Expert Chip.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Diamond Dust"><img src="/images/items/diamond_dust.png"></div>
    <div class="crafting-slot" data-label="Expert Fluid Tank"><img src="/images/items/expert_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Diamond Dust"><img src="/images/items/diamond_dust.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Advanced Magmator"><img src="/images/items/advanced_magmator.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Expert Magmator"><img src="/images/items/expert_magmator.png"></div>
</div>

*Pattern: `GDG / EBE / SES` — Diamond Dust (G), Expert Fluid Tank (D), Expert Chip (E), Advanced Magmator (B), Steel Plate (S)*

---

### Ultimate Magmator

Maximum power output. Late-game generator; requires Netherite Plate and Ultimate Chip.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Netherite Plate"><img src="/images/items/netherite_plate.png"></div>
    <div class="crafting-slot" data-label="Ultimate Fluid Tank"><img src="/images/items/ultimate_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Netherite Plate"><img src="/images/items/netherite_plate.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Expert Magmator"><img src="/images/items/expert_magmator.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Netherite Plate"><img src="/images/items/netherite_plate.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Netherite Plate"><img src="/images/items/netherite_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Ultimate Magmator"><img src="/images/items/ultimate_magmator.png"></div>
</div>

*Pattern: `GDG / EBE / GEG` — Netherite Plate (G), Ultimate Fluid Tank (D), Ultimate Chip (E), Expert Magmator (B)*

---

## Fluid Tanks

Fluid Tanks are standalone **fluid storage** blocks (lava, water, etc.) — fill them by right-clicking
with a bucket or wiring them into a fluid-pipe network. They're used as a **crafting ingredient** in
Magmator and Thermo Generator recipes; they are **not** placed underneath a machine. Capacities:
**32,000 / 128,000 / 512,000 / 3,200,000 mB** (basic→ultimate), and they're an **upgrade chain** —
each tier consumes 3× of the previous tier's tank.

### Basic Fluid Tank

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Glass"><img src="/images/items/glass.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Glass"><img src="/images/items/glass.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Glass"><img src="/images/items/glass.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Glass"><img src="/images/items/glass.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Basic Fluid Tank"><img src="/images/items/basic_fluid_tank.png"></div>
</div>

*Gold Plate (4 corners) + Glass (4 edges) + Basic Chip (center).*

---

### Advanced Fluid Tank

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Energized Iron Ingot"><img src="/images/items/energized_iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Basic Fluid Tank"><img src="/images/items/basic_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Ingot"><img src="/images/items/energized_iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Basic Fluid Tank"><img src="/images/items/basic_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Basic Fluid Tank"><img src="/images/items/basic_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Ingot"><img src="/images/items/energized_iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Glass"><img src="/images/items/glass.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Ingot"><img src="/images/items/energized_iron_ingot.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Advanced Fluid Tank"><img src="/images/items/advanced_fluid_tank.png"></div>
</div>

*Energized Iron Ingot (4) + Basic Fluid Tank (3) + Advanced Chip (center) + Glass. Each tier consumes 3× the previous tank.*

---

### Expert Fluid Tank

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Diamond Dust"><img src="/images/items/diamond_dust.png"></div>
    <div class="crafting-slot" data-label="Advanced Fluid Tank"><img src="/images/items/advanced_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Diamond Dust"><img src="/images/items/diamond_dust.png"></div>
    <div class="crafting-slot" data-label="Advanced Fluid Tank"><img src="/images/items/advanced_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Advanced Fluid Tank"><img src="/images/items/advanced_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Diamond Dust"><img src="/images/items/diamond_dust.png"></div>
    <div class="crafting-slot" data-label="Glass"><img src="/images/items/glass.png"></div>
    <div class="crafting-slot" data-label="Diamond Dust"><img src="/images/items/diamond_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Expert Fluid Tank"><img src="/images/items/expert_fluid_tank.png"></div>
</div>

*Diamond Dust (4) + Advanced Fluid Tank (3) + Expert Chip (center) + Glass.*

---

### Ultimate Fluid Tank

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Netherite Dust"><img src="/images/items/netherite_dust.png"></div>
    <div class="crafting-slot" data-label="Expert Fluid Tank"><img src="/images/items/expert_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Netherite Dust"><img src="/images/items/netherite_dust.png"></div>
    <div class="crafting-slot" data-label="Expert Fluid Tank"><img src="/images/items/expert_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Expert Fluid Tank"><img src="/images/items/expert_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Netherite Dust"><img src="/images/items/netherite_dust.png"></div>
    <div class="crafting-slot" data-label="Glass"><img src="/images/items/glass.png"></div>
    <div class="crafting-slot" data-label="Netherite Dust"><img src="/images/items/netherite_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Ultimate Fluid Tank"><img src="/images/items/ultimate_fluid_tank.png"></div>
</div>

*Netherite Dust (4) + Expert Fluid Tank (3) + Ultimate Chip (center) + Glass. Netherite dust comes from the [Crusher](crusher.md).*

---

## Batteries

Batteries store UC power and can buffer output between generators and machines. They follow the same upgrade-chain pattern as Magmators and Fluid Tanks.

### Basic Battery

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Gold Dust"><img src="/images/items/gold_dust.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Basic Battery"><img src="/images/items/basic_battery.png"></div>
</div>

### Advanced Battery

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Basic Battery"><img src="/images/items/basic_battery.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Basic Battery"><img src="/images/items/basic_battery.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Basic Battery"><img src="/images/items/basic_battery.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Dust"><img src="/images/items/energized_iron_dust.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Advanced Battery"><img src="/images/items/advanced_battery.png"></div>
</div>

### Expert Battery

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Advanced Battery"><img src="/images/items/advanced_battery.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Advanced Battery"><img src="/images/items/advanced_battery.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Advanced Battery"><img src="/images/items/advanced_battery.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Diamond Dust"><img src="/images/items/diamond_dust.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Expert Battery"><img src="/images/items/expert_battery.png"></div>
</div>

### Ultimate Battery

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Expert Battery"><img src="/images/items/expert_battery.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Expert Battery"><img src="/images/items/expert_battery.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Expert Battery"><img src="/images/items/expert_battery.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Netherite Dust"><img src="/images/items/netherite_dust.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Ultimate Battery"><img src="/images/items/ultimate_battery.png"></div>
</div>

---

## Furnators

Furnators burn solid fuel (like a Blast Furnace) to generate UC power. They follow the same upgrade-chain pattern as Magmators.

### Basic Furnator

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Blast Furnace"><img src="/images/items/blast_furnace.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Basic Furnator"><img src="/images/items/basic_furnator.png"></div>
</div>

*Pattern: `AEA / EBE / CDC` — Steel Ingot (A), Basic Chip (E), Blast Furnace (B), Iron Ingot (C), Redstone Block (D)*

---

### Advanced Furnator

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Basic Furnator"><img src="/images/items/basic_furnator.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Plate"><img src="/images/items/energized_iron_plate.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Plate"><img src="/images/items/energized_iron_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Advanced Furnator"><img src="/images/items/advanced_furnator.png"></div>
</div>

*Pattern: `AEA / EBE / CDC` — Steel Plate (A), Advanced Chip (E), Basic Furnator (B), Energized Iron Plate (C), Redstone Block (D)*

---

### Expert Furnator

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Advanced Furnator"><img src="/images/items/advanced_furnator.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Diamond Dust"><img src="/images/items/diamond_dust.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Diamond Dust"><img src="/images/items/diamond_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Expert Furnator"><img src="/images/items/expert_furnator.png"></div>
</div>

*Pattern: `AEA / EBE / CDC` — Steel Plate (A), Expert Chip (E), Advanced Furnator (B), Diamond Dust (C), Redstone Block (D)*

---

### Ultimate Furnator

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Expert Furnator"><img src="/images/items/expert_furnator.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Netherite Plate"><img src="/images/items/netherite_plate.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Netherite Plate"><img src="/images/items/netherite_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Ultimate Furnator"><img src="/images/items/ultimate_furnator.png"></div>
</div>

*Pattern: `AEA / EBE / CDC` — Steel Plate (A), Ultimate Chip (E), Expert Furnator (B), Netherite Plate (C), Redstone Block (D)*

---

## Solar Panels

Solar Panels generate UC power during the **day**. Output is a pure function of **time of day** — it
ramps from zero at dawn to a **peak at noon** and back to zero at night. There is **no sky-access or
light-level check**, so a panel still works fully enclosed or underground; it just has to be daytime.

### Basic Solar Panel

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Gold Ingot"><img src="/images/items/gold_ingot.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Gold Ingot"><img src="/images/items/gold_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Gold Ingot"><img src="/images/items/gold_ingot.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Basic Solar Panel"><img src="/images/items/basic_solar_panel.png"></div>
</div>

*Pattern: `AEA / ECE / CDC` — Steel Ingot (A), Basic Chip (E), Gold Ingot (C), Redstone Block (D)*

---

### Advanced Solar Panel

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Basic Solar Panel"><img src="/images/items/basic_solar_panel.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Plate"><img src="/images/items/energized_iron_plate.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Plate"><img src="/images/items/energized_iron_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Advanced Solar Panel"><img src="/images/items/advanced_solar_panel.png"></div>
</div>

*Pattern: `AEA / EBE / CDC` — Steel Plate (A), Advanced Chip (E), Basic Solar Panel (B), Energized Iron Plate (C), Redstone Block (D)*

---

### Expert Solar Panel

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Advanced Solar Panel"><img src="/images/items/advanced_solar_panel.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Diamond Dust"><img src="/images/items/diamond_dust.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Diamond Dust"><img src="/images/items/diamond_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Expert Solar Panel"><img src="/images/items/expert_solar_panel.png"></div>
</div>

*Pattern: `AEA / EBE / CDC` — Steel Plate (A), Expert Chip (E), Advanced Solar Panel (B), Diamond Dust (C), Redstone Block (D)*

---

### Ultimate Solar Panel

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Expert Solar Panel"><img src="/images/items/expert_solar_panel.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Netherite Plate"><img src="/images/items/netherite_plate.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Netherite Plate"><img src="/images/items/netherite_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Ultimate Solar Panel"><img src="/images/items/ultimate_solar_panel.png"></div>
</div>

*Pattern: `AEA / EBE / CDC` — Steel Plate (A), Ultimate Chip (E), Expert Solar Panel (B), Netherite Plate (C), Redstone Block (D)*

---

## Thermo Generators

Thermo Generators produce UC power from a **heat-source block placed directly below** them, using
**water as coolant** from their own internal buffer. Valid heat blocks (with output multipliers):
**blaze block ×1.5**, lava ×1, soul fire / soul torch / soul campfire ×0.75, fire / campfire / magma
×0.5, torch ×0.25. Keep **water** in it (it consumes 1 energy per mB of water) — *not lava, not
ice*. The Fluid Tank is only a **crafting ingredient**, not placed underneath.

### Basic Thermo Generator

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Copper Block"><img src="/images/items/copper_block.png"></div>
    <div class="crafting-slot" data-label="Copper Plate"><img src="/images/items/copper_plate.png"></div>
    <div class="crafting-slot" data-label="Copper Block"><img src="/images/items/copper_block.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Basic Fluid Tank"><img src="/images/items/basic_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
    <div class="crafting-slot" data-label="Copper Block"><img src="/images/items/copper_block.png"></div>
    <div class="crafting-slot" data-label="Gold Plate"><img src="/images/items/gold_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Basic Thermo Generator"><img src="/images/items/basic_thermo_generator.png"></div>
</div>

*Copper Plate (top-center) + Copper Block (top corners + bottom-center) + Basic Chip (sides) + Basic Fluid Tank (center) + Gold Plate (bottom corners).*

---

### Advanced Thermo Generator

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Copper Block"><img src="/images/items/copper_block.png"></div>
    <div class="crafting-slot" data-label="Advanced Fluid Tank"><img src="/images/items/advanced_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Copper Block"><img src="/images/items/copper_block.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Basic Thermo Generator"><img src="/images/items/basic_thermo_generator.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Plate"><img src="/images/items/energized_iron_plate.png"></div>
    <div class="crafting-slot" data-label="Copper Block"><img src="/images/items/copper_block.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Plate"><img src="/images/items/energized_iron_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Advanced Thermo Generator"><img src="/images/items/advanced_thermo_generator.png"></div>
</div>

*Pattern: `ADA / EBE / CAC` — Copper Block (A), Advanced Fluid Tank (D), Advanced Chip (E), Basic Thermo Generator (B), Energized Iron Plate (C)*

---

### Expert Thermo Generator

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Copper Block"><img src="/images/items/copper_block.png"></div>
    <div class="crafting-slot" data-label="Expert Fluid Tank"><img src="/images/items/expert_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Copper Block"><img src="/images/items/copper_block.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Advanced Thermo Generator"><img src="/images/items/advanced_thermo_generator.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Diamond Dust"><img src="/images/items/diamond_dust.png"></div>
    <div class="crafting-slot" data-label="Copper Block"><img src="/images/items/copper_block.png"></div>
    <div class="crafting-slot" data-label="Diamond Dust"><img src="/images/items/diamond_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Expert Thermo Generator"><img src="/images/items/expert_thermo_generator.png"></div>
</div>

*Pattern: `ADA / EBE / CAC` — Copper Block (A), Expert Fluid Tank (D), Expert Chip (E), Advanced Thermo Generator (B), Diamond Dust (C)*

---

### Ultimate Thermo Generator

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Copper Block"><img src="/images/items/copper_block.png"></div>
    <div class="crafting-slot" data-label="Ultimate Fluid Tank"><img src="/images/items/ultimate_fluid_tank.png"></div>
    <div class="crafting-slot" data-label="Copper Block"><img src="/images/items/copper_block.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Expert Thermo Generator"><img src="/images/items/expert_thermo_generator.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Netherite Plate"><img src="/images/items/netherite_plate.png"></div>
    <div class="crafting-slot" data-label="Copper Block"><img src="/images/items/copper_block.png"></div>
    <div class="crafting-slot" data-label="Netherite Plate"><img src="/images/items/netherite_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Ultimate Thermo Generator"><img src="/images/items/ultimate_thermo_generator.png"></div>
</div>

*Pattern: `ADA / EBE / CAC` — Copper Block (A), Ultimate Fluid Tank (D), Ultimate Chip (E), Expert Thermo Generator (B), Netherite Plate (C)*

---

## Wind Turbines

Wind Turbines generate UC power passively, scaling with **altitude** and **weather** — output rises
the higher you place them (base around Y 63; below ~Y 20 they cut out with "Low Altitude", up to
~**4×** at high altitude) and with weather (**clear ×1, rain ×1.5, thunder ×2.25**). There is **no
open-space-above requirement**. Higher tiers produce more base power.

### Basic Wind Turbine

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Fan"><img src="/images/items/fan.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Machine Case"><img src="/images/items/machine_case.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Basic Wind Turbine"><img src="/images/items/basic_wind_turbine.png"></div>
</div>

*Pattern: `AEA / EBE / CDC` — Steel Ingot (A), Basic Chip (E), Fan (B), Machine Case (C), Redstone Block (D)*

---

### Advanced Wind Turbine

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Basic Wind Turbine"><img src="/images/items/basic_wind_turbine.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Plate"><img src="/images/items/energized_iron_plate.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Energized Iron Plate"><img src="/images/items/energized_iron_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Advanced Wind Turbine"><img src="/images/items/advanced_wind_turbine.png"></div>
</div>

*Pattern: `AEA / EBE / CDC` — Steel Plate (A), Advanced Chip (E), Basic Wind Turbine (B), Energized Iron Plate (C), Redstone Block (D)*

---

### Expert Wind Turbine

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Advanced Wind Turbine"><img src="/images/items/advanced_wind_turbine.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Diamond Dust"><img src="/images/items/diamond_dust.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Diamond Dust"><img src="/images/items/diamond_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Expert Wind Turbine"><img src="/images/items/expert_wind_turbine.png"></div>
</div>

*Pattern: `AEA / EBE / CDC` — Steel Plate (A), Expert Chip (E), Advanced Wind Turbine (B), Diamond Dust (C), Redstone Block (D)*

---

### Ultimate Wind Turbine

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Steel Plate"><img src="/images/items/steel_plate.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Expert Wind Turbine"><img src="/images/items/expert_wind_turbine.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Netherite Plate"><img src="/images/items/netherite_plate.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Netherite Plate"><img src="/images/items/netherite_plate.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Ultimate Wind Turbine"><img src="/images/items/ultimate_wind_turbine.png"></div>
</div>

*Pattern: `AEA / EBE / CDC` — Steel Plate (A), Ultimate Chip (E), Expert Wind Turbine (B), Netherite Plate (C), Redstone Block (D)*
