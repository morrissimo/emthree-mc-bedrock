# Energized Iron

Energized iron gates the `advanced_chip` and many mid-game machines. It does **not** spawn as a world ore — you have to make it first, then grow it.

## Getting Your First Batch

Neither the [Infuser](infuser.md) nor the generators that power it require energized iron to build — only `basic_chip` and `machine_case`. So the bootstrap path is:

1. Steel → `chip` → `basic_chip` (UC Workbench, no energized iron needed)
2. Build a `basic_furnator` (or any basic generator) for power
3. Build an `infuser`
4. Run the infuser: `redstone` (catalyst) + `iron_ingot` → `energized_iron_ingot` × 4 cycles per run
5. After two runs you have 8 ingots — enough to craft an energized iron sapling

Once the sapling is planted, the ore tree becomes your renewable supply and you rarely need to run the infuser for raw ingots again.

## Ongoing Sources

### Bountiful Trees (renewable)

The [energized iron ore tree](../addons/bountiful_trees.md) is the main long-term source.

- Grow an energized iron sapling on appropriate soil
- Chop the logs with an axe → drops **1–2 raw_energized_iron** per log (plus 1 oak_log)
- Smelt `raw_energized_iron` in furnace or blast furnace → `energized_iron_ingot`

Bone meal speeds growth (20% chance per application). A mature tree yields several logs per harvest.

### Infuser (automation)

A powered [Infuser](infuser.md) can also produce energized iron directly, useful for bulk dust production or if you don't have trees yet.

| Catalyst | Input | Output | Cycles |
|----------|-------|--------|--------|
| redstone | iron_ingot | energized_iron_ingot | 4 |
| redstone | iron_dust | energized_iron_dust | 4 |

## Uses

- `advanced_chip` recipe (4× energized_iron_ingot per chip)
- `energized_iron_dust` — infuser chip automation, advanced generator plates
- `energized_iron_plate` — tiered generator and machine upgrades (via Electro Press)
