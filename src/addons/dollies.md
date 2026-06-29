# Dollies

A **dolly** (hand truck) for moving storage. Pick up a **single chest or a barrel** — *with
everything inside it* — carry it wherever you want, and set it back down. No more emptying a
chest into your inventory just to relocate it.

!!! note "Single chests & barrels only"
    The dolly does **not** move **double chests**. Sneak-tapping a double does nothing — break
    it into singles first if you need to move it.

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

- **Pick up:** **sneak + use** (crouch, then tap/right-click) the dolly on a single chest or
  barrel. The block vanishes and your dolly now shows what it's carrying — *Dolly (Chest)* or
  *Dolly (Barrel)*.
- **Set down:** **use** (tap/right-click, no sneak) the loaded dolly on an open spot. The chest/
  barrel reappears with **all of its contents exactly as they were**, and your dolly is empty again.

!!! tip "It won't make a double chest"
    To keep things simple and safe, a dolly won't set a chest down where it would merge into a
    **double** with a chest right beside it — you'll see *"Can't place: would form a double chest."*
    Just pick a spot that isn't flush against another same-facing chest, and your cargo stays put
    on the dolly until it lands somewhere safe.

!!! tip "Why sneak to pick up?"
    A normal tap on a chest just **opens** it (that's true on every device). Sneaking tells the
    game you want to use the *dolly* on it instead of opening it — the same way you sneak to place
    a block against a chest. Setting down doesn't need sneak.

## What it can carry

| Container | Works? |
|---|---|
| Chest (single) | ✅ |
| Barrel | ✅ |
| **Double chest** | ❌ — not supported (sneak-tap does nothing) |
| Furnaces, hoppers, machines, etc. | ❌ — silently ignored |

- **Contents are never lost or changed** — item order, stacks, even enchanted/renamed items come
  back exactly as they went in.
- **Double chests aren't supported.** Sneak-tapping one does nothing; and the dolly won't *create*
  one either (it refuses a placement that would merge with an adjacent chest). Break a double into
  two singles if you need to relocate it.
- **Everything else is ignored on purpose.** Furnaces, hoppers, and modded machines store their
  contents somewhere a dolly can't safely move, so it won't touch them.

!!! warning "Don't lose your loaded dolly"
    A loaded dolly holds its cargo *in the item*. If you destroy the loaded dolly (lava, the void),
    the chest and its contents go with it — same as anything else in your inventory. Place it
    somewhere safe rather than tossing it around.
