# Transport & Routing

Items and blocks for moving energy, fluids, and items across your automation network. The **Wrench** is used to configure most of them.

---

## Wrench

Right-click a machine, cable, or transport block with the Wrench to cycle its settings — output direction, transfer mode, color network, etc. Crafted at a regular crafting table (not the UC Workbench).

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Wrench"><img src="/images/items/wrench.png"></div>
</div>

---

## Energy Cables

The simplest way to run wired power between generators, batteries, and machines when adjacency isn't enough. Yields 8 per craft.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Nugget"><img src="/images/items/steel_nugget.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Steel Nugget"><img src="/images/items/steel_nugget.png"></div>
    <div class="crafting-slot" data-label="Copper Nugget"><img src="/images/items/copper_nugget.png"></div>
    <div class="crafting-slot" data-label="Copper Nugget"><img src="/images/items/copper_nugget.png"></div>
    <div class="crafting-slot" data-label="Copper Nugget"><img src="/images/items/copper_nugget.png"></div>
    <div class="crafting-slot" data-label="Steel Nugget"><img src="/images/items/steel_nugget.png"></div>
    <div class="crafting-slot" data-label="Redstone"><img src="/images/items/redstone_dust.png"></div>
    <div class="crafting-slot" data-label="Steel Nugget"><img src="/images/items/steel_nugget.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Energy Cable ×8"><img src="/images/items/energy_cable.png"><span class="stack">8</span></div>
</div>

*Pattern: `SRS / CCC / SRS` — Steel Nugget (S), Redstone (R), Copper Nugget (C)*

---

## Wireless Energy: Transmitters & Receivers

Transmitters broadcast UC power wirelessly; Receivers pick it up at the destination. Place one of each and use the Wrench to pair them to a matching color channel. Both come in 4 tiers — higher tiers transfer more power per tick.

**Transmitter** uses a **Repeater** as the signal component; **Receiver** uses a **Redstone Torch**. All other materials are identical for the same tier.

### Basic Transmitter

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Repeater"><img src="/images/items/repeater.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Basic Battery"><img src="/images/items/basic_battery.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Basic Transmitter"><img src="/images/items/basic_energy_transmitter.png"></div>
</div>

### Basic Receiver

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Redstone Torch"><img src="/images/items/redstone_torch.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Basic Battery"><img src="/images/items/basic_battery.png"></div>
    <div class="crafting-slot" data-label="Basic Chip"><img src="/images/items/basic_chip.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Basic Receiver"><img src="/images/items/basic_energy_receiver.png"></div>
</div>

*Pattern: `ETE / CBC / ERE` — Ender Pearl Dust (E), Repeater or Torch (T), Chip (C), Battery (B), Redstone Block (R)*

---

### Advanced Transmitter

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Basic Transmitter"><img src="/images/items/basic_energy_transmitter.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Advanced Transmitter"><img src="/images/items/advanced_energy_transmitter.png"></div>
</div>

### Advanced Receiver

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Basic Receiver"><img src="/images/items/basic_energy_receiver.png"></div>
    <div class="crafting-slot" data-label="Advanced Chip"><img src="/images/items/advanced_chip.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Advanced Receiver"><img src="/images/items/advanced_energy_receiver.png"></div>
</div>

*Pattern: `ECE / CBC / ERE` — Ender Pearl Dust (E), Chip (C), Previous Tier (B), Redstone Block (R)*

---

### Expert Transmitter

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Advanced Transmitter"><img src="/images/items/advanced_energy_transmitter.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Expert Transmitter"><img src="/images/items/expert_energy_transmitter.png"></div>
</div>

### Expert Receiver

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Advanced Receiver"><img src="/images/items/advanced_energy_receiver.png"></div>
    <div class="crafting-slot" data-label="Expert Chip"><img src="/images/items/expert_chip.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Expert Receiver"><img src="/images/items/expert_energy_receiver.png"></div>
</div>

---

### Ultimate Transmitter

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Expert Transmitter"><img src="/images/items/expert_energy_transmitter.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Ultimate Transmitter"><img src="/images/items/ultimate_energy_transmitter.png"></div>
</div>

### Ultimate Receiver

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Expert Receiver"><img src="/images/items/expert_energy_receiver.png"></div>
    <div class="crafting-slot" data-label="Ultimate Chip"><img src="/images/items/ultimate_chip.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
    <div class="crafting-slot" data-label="Redstone Block"><img src="/images/items/redstone_block.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl Dust"><img src="/images/items/ender_pearl_dust.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Ultimate Receiver"><img src="/images/items/ultimate_energy_receiver.png"></div>
</div>

---

## Fluid Pipes

Move fluids (water, lava, XP fluid, etc.) between tanks, machines, and generators. Connect to Fluid Tanks and Thermo Generators. Use the Wrench to set flow direction and color network. Yields 8 per craft.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Nugget"><img src="/images/items/steel_nugget.png"></div>
    <div class="crafting-slot" data-label="Steel Nugget"><img src="/images/items/steel_nugget.png"></div>
    <div class="crafting-slot" data-label="Steel Nugget"><img src="/images/items/steel_nugget.png"></div>
    <div class="crafting-slot" data-label="Glass"><img src="/images/items/glass.png"></div>
    <div class="crafting-slot" data-label="Bucket"><img src="/images/items/bucket.png"></div>
    <div class="crafting-slot" data-label="Glass"><img src="/images/items/glass.png"></div>
    <div class="crafting-slot" data-label="Steel Nugget"><img src="/images/items/steel_nugget.png"></div>
    <div class="crafting-slot" data-label="Steel Nugget"><img src="/images/items/steel_nugget.png"></div>
    <div class="crafting-slot" data-label="Steel Nugget"><img src="/images/items/steel_nugget.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Fluid Pipe ×8"><img src="/images/items/fluid_pipe.png"><span class="stack">8</span></div>
</div>

*Pattern: `SSS / GCG / SSS` — Steel Nugget (S), Glass (G), Bucket (C)*

---

## Item Conduits

Move items between containers and machines. Connect chests, barrels, and machines into automated pipelines. Yields 8 per craft. Use the Wrench to set color network and filtering.

### Item Conduit

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Nugget"><img src="/images/items/steel_nugget.png"></div>
    <div class="crafting-slot" data-label="Steel Nugget"><img src="/images/items/steel_nugget.png"></div>
    <div class="crafting-slot" data-label="Steel Nugget"><img src="/images/items/steel_nugget.png"></div>
    <div class="crafting-slot" data-label="Glass"><img src="/images/items/glass.png"></div>
    <div class="crafting-slot" data-label="Chest"><img src="/images/items/chest.png"></div>
    <div class="crafting-slot" data-label="Glass"><img src="/images/items/glass.png"></div>
    <div class="crafting-slot" data-label="Steel Nugget"><img src="/images/items/steel_nugget.png"></div>
    <div class="crafting-slot" data-label="Steel Nugget"><img src="/images/items/steel_nugget.png"></div>
    <div class="crafting-slot" data-label="Steel Nugget"><img src="/images/items/steel_nugget.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Item Conduit ×8"><img src="/images/items/item_conduit.png"><span class="stack">8</span></div>
</div>

*Pattern: `SSS / GCG / SSS` — Steel Nugget (S), Glass (G), Chest (C)*

### Item Exporter

Active push — pulls items from the attached inventory and pushes them into the conduit network. Craft at the UC Workbench.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Item Conduit"><img src="/images/items/item_conduit.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Item Conduit"><img src="/images/items/item_conduit.png"></div>
    <div class="crafting-slot" data-label="Hopper"><img src="/images/items/hopper.png"></div>
    <div class="crafting-slot" data-label="Item Conduit"><img src="/images/items/item_conduit.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Item Conduit"><img src="/images/items/item_conduit.png"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Item Exporter"><img src="/images/items/item_exporter.png"></div>
</div>

### Item Importer

Active pull — draws items from the conduit network into the attached inventory.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Item Conduit"><img src="/images/items/item_conduit.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Item Conduit"><img src="/images/items/item_conduit.png"></div>
    <div class="crafting-slot" data-label="Item Conduit"><img src="/images/items/item_conduit.png"></div>
    <div class="crafting-slot" data-label="Item Conduit"><img src="/images/items/item_conduit.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Hopper"><img src="/images/items/hopper.png"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Item Importer"><img src="/images/items/item_conduit.png"></div>
</div>

---

## XP Drain & Spout

Converts player experience into storable XP fluid and releases it back. Useful for automating enchanting or safely banking XP from mob farms.

### XP Drain

Stand on the XP Drain to pull XP from the player and store it as fluid in a connected Fluid Tank.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Bars"><img src="/images/items/iron_bars.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Bars"><img src="/images/items/iron_bars.png"></div>
    <div class="crafting-slot" data-label="Hopper"><img src="/images/items/hopper.png"></div>
    <div class="crafting-slot" data-label="Iron Bars"><img src="/images/items/iron_bars.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Iron Bars"><img src="/images/items/iron_bars.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="XP Drain"><img src="/images/items/xp_drain.png"></div>
</div>

*Pattern: `SMS / MHM / SMS` — Steel Ingot (S), Iron Bars (M), Hopper (H)*

### XP Spout

Releases stored XP fluid from a connected Fluid Tank back to the player standing nearby.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Lever"><img src="/images/items/lever.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot" data-label="Dropper"><img src="/images/items/dropper.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot" data-label="Steel Ingot"><img src="/images/items/steel_ingot.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="XP Spout"><img src="/images/items/xp_spout.png"></div>
</div>

*Pattern: `SL / SDI / S` — Steel Ingot (S), Lever (L), Dropper (D), Iron Ingot (I)*
