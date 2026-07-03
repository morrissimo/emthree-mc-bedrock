# Elevators

Instant **vertical teleport** pads. Stack two or more elevators of the **same color** in the same column, and hop between them — no ladders, no scaffolding, no fall damage. Great for mineshafts, towers, and storage silos.

## Crafting

Crafted at the **UC Workbench**. The base is white; for a colored elevator, use that color of wool instead:

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="White Wool"><img src="/images/items/white_wool.png"></div>
    <div class="crafting-slot" data-label="White Wool"><img src="/images/items/white_wool.png"></div>
    <div class="crafting-slot" data-label="White Wool"><img src="/images/items/white_wool.png"></div>
    <div class="crafting-slot" data-label="White Wool"><img src="/images/items/white_wool.png"></div>
    <div class="crafting-slot" data-label="Ender Pearl"><img src="/images/items/ender_pearl.png"></div>
    <div class="crafting-slot" data-label="White Wool"><img src="/images/items/white_wool.png"></div>
    <div class="crafting-slot" data-label="White Wool"><img src="/images/items/white_wool.png"></div>
    <div class="crafting-slot" data-label="White Wool"><img src="/images/items/white_wool.png"></div>
    <div class="crafting-slot" data-label="White Wool"><img src="/images/items/white_wool.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Elevator"><img src="/images/items/elevator.png"></div>
</div>

Comes in all **16 wool colors** — cosmetic, but color also controls linking (see below).

## How to use

- **Go up:** **jump** while standing on the elevator (or right-click it without sneaking).
- **Go down:** **sneak** while standing on it (or sneak + right-click).
- You're teleported to the next elevator directly above/below in the **same X/Z column**.

### Rules

- **Colors must match to link** — a red elevator only teleports to another red elevator. Mix colors in the same column to make independent stops.
- **Must be vertically aligned** — same X/Z, stacked in one column.
- **Range is the whole column** — it searches from the world floor to the ceiling, so there's no max distance between two elevators.
- **Won't teleport into a wall** — if the block above the destination elevator is obstructed, nothing happens (leave headroom).

!!! warning "Nether quirk"
    Riding an elevator **up** in the Nether has a **10% chance to briefly set you on fire** (~1 second). A quirk of the block, not a bug.
