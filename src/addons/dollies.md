# Dollies

A **dolly** (hand truck) for moving storage. Pick up a chest or barrel — *with everything
inside it* — carry it wherever you want, and set it back down. No more emptying a chest
into your inventory just to relocate it.

## Crafting

Crafted at a **vanilla crafting table**. Recipe unlock: having an **iron ingot** in your inventory.

<div class="crafting-recipe">
  <div class="crafting-grid">
    <div class="crafting-slot" data-label="Iron Bars"><img src="/images/items/iron_bars.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot empty"></div>
    <div class="crafting-slot" data-label="Minecart"><img src="/images/items/minecart.png"></div>
    <div class="crafting-slot" data-label="Iron Ingot"><img src="/images/items/iron_ingot.png"></div>
    <div class="crafting-slot empty"></div>
  </div>
  <div class="crafting-arrow">→</div>
  <div class="crafting-output" data-label="Dolly"><img src="/images/items/dolly.png"></div>
</div>

One dolly lasts forever — it's a reusable tool, not consumed.

## How to use it

- **Pick up:** **sneak + use** (crouch, then tap/right-click) the dolly on a chest or barrel. The
  block vanishes and your dolly now shows what it's carrying — *Dolly (Chest)*, *Dolly (Barrel)*,
  etc.
- **Set down:** **use** (tap/right-click, no sneak) the loaded dolly on an open spot. The chest/
  barrel reappears with **all of its contents exactly as they were**, and your dolly is empty again.

!!! tip "Why sneak to pick up?"
    A normal tap on a chest just **opens** it (that's true on every device). Sneaking tells the
    game you want to use the *dolly* on it instead of opening it — the same way you sneak to place
    a block against a chest. Setting down doesn't need sneak.

## What it can carry

| Container | Works? |
|---|---|
| Chest (single) | ✅ |
| **Double chest** | ✅ — picks up the **whole** double chest as one unit |
| Barrel | ✅ |
| Furnaces, hoppers, machines, etc. | ❌ — *"only carries chests and barrels"* |

- **Contents are never lost or changed** — item order, stacks, even enchanted/renamed items come
  back exactly as they went in.
- A **double chest** is carried and placed as a single unit (both halves together). It needs **two
  open blocks in a row** to set back down — if there's no room you'll see a hint and the dolly stays
  loaded.
- **Modded machines are refused on purpose.** Their contents live somewhere a dolly can't safely
  move, so the dolly won't touch them.

!!! warning "Don't lose your loaded dolly"
    A loaded dolly holds its cargo *in the item*. If you destroy the loaded dolly (lava, the void),
    the chest and its contents go with it — same as anything else in your inventory. Place it
    somewhere safe rather than tossing it around.
