# Redstone Clock

A single **Redstone Clock** block that emits a **repeating, adjustable redstone pulse**. Place it,
tap it to set how fast it ticks, wire it to whatever you want pulsed — a lamp, a piston, a dropper,
a Crafter — and you're done. No repeater loops, no observer contraptions, no redstone-engineering
degree required.

!!! note "One block, does the whole job"
    Vanilla has no simple clock block — you normally build one out of repeaters or observers. This
    is that clock in a single, configurable block.

## Crafting

Crafted at a **vanilla crafting table**. Recipe unlock: having a **redstone torch** in your inventory.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Stone"><img src="/images/items/stone.png"></div>
    <div class="crafting-slot" data-label="Repeater"><img src="/images/items/repeater.png"></div>
    <div class="crafting-slot" data-label="Stone"><img src="/images/items/stone.png"></div>
    <div class="crafting-slot" data-label="Redstone Dust"><img src="/images/items/redstone.png"></div>
    <div class="crafting-slot" data-label="Clock"><img src="/images/items/clock.png"></div>
    <div class="crafting-slot" data-label="Redstone Dust"><img src="/images/items/redstone.png"></div>
    <div class="crafting-slot" data-label="Stone"><img src="/images/items/stone.png"></div>
    <div class="crafting-slot" data-label="Redstone Torch"><img src="/images/items/redstone_torch.png"></div>
    <div class="crafting-slot" data-label="Stone"><img src="/images/items/stone.png"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Redstone Clock"><img src="/images/items/redstone_clock.png"></div>
</div>

## How to use it

- **Place it** anywhere you'd put a normal block. It starts ticking immediately at its defaults:
  a **1-second** interval, in **short-pulse** mode, running.
- **Configure it:** **tap/use** the block (right-click, or tap on touch) to open its settings menu.
- **Wire it up:** any redstone component touching the block reacts to the pulse — lamp, piston,
  dropper, dispenser, Crafter, or redstone dust running away from it.

The clock's face lights up brighter each time it fires, so you can see it working from across the
room — even before you've wired anything to it.

## Settings

Tapping the clock opens a small menu with three controls:

| Setting | What it does |
|---|---|
| **Interval (seconds)** | A slider from **1 to 60 seconds** — the length of one full on/off cycle. |
| **Pulse shape** | **Short pulse** (a brief blip once per cycle) or **Square wave** (on for half the cycle, off for half). |
| **Running** | Turn the clock on or off. Off = quiet and greyed out, but it remembers your settings. |

!!! tip "Which pulse shape do I want?"
    - **Short pulse** (the default) fires one quick tick per cycle — perfect for a **Crafter**,
      dropper, or dispenser, which act once per redstone pulse.
    - **Square wave** stays on for half the cycle — better for a **blinking lamp** or anything you
      want held on for a while, then off for a while.

## Wiring it up

- **Anything touching the clock** — a lamp, piston, Crafter, or redstone dust on the ground beside
  it — reacts to the pulse directly.
- **Dust on top of a block** works if that block is sitting **directly on top of the clock**: the
  clock strongly powers the block above it (like a redstone torch does), so dust on *that* block
  carries the signal. Dust on a block beside the clock will **not** — put your relay block on top.

!!! tip "Line up a bank of them"
    Every clock set to the **same interval blinks in perfect sync**, no matter when you placed it.
    Rows of same-speed clocks (or lamps they drive) pulse together automatically — handy for
    decorative lighting or synchronized farms.

## Good to know

- **Breaking a clock drops it back** as an item, but a **freshly placed clock starts at the defaults
  again** — settings don't carry over a break-and-replace. Set it once it's in position.
- **Settings survive** restarts, reloads, and wandering far away and back — a placed clock keeps its
  configuration as long as it stays placed.
- **Fastest useful pulse is 1 second.** That's plenty for lamps, farms, and Crafters without the
  timing jank that ultra-fast clocks cause.
