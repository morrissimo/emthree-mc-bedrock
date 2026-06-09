# Energized Iron

Energized iron gates the `advanced_chip` and many mid-game machines. It does **not** spawn as a world ore — there are no world generation features for it.

## Sources

### Primary — Bountiful Trees (early-game renewable)

The [energized iron ore tree](../addons/bountiful_trees.md) is the main source before you have power infrastructure.

- Grow an energized iron sapling on appropriate soil
- Chop the logs with an axe → drops **1–2 raw_energized_iron** per log (plus 1 oak_log)
- Smelt `raw_energized_iron` in furnace or blast furnace → `energized_iron_ingot`

Bone meal speeds growth (20% chance per application). A mature tree yields several logs per harvest.

### Secondary — Infuser (mid-game automation)

Once you have a powered [Infuser](infuser.md):

| Catalyst | Input | Output | Cycles |
|----------|-------|--------|--------|
| redstone | iron_ingot | energized_iron_ingot | 4 |
| redstone | iron_dust | energized_iron_dust | 4 |

## Uses

- `advanced_chip` recipe (4× energized_iron_ingot per chip)
- `energized_iron_dust` — infuser chip automation, advanced generator plates
- `energized_iron_plate` — tiered generator and machine upgrades (via Electro Press)

## Notes

The `raw_energized_iron` item and block are defined in the UC pack, but no feature or feature_rule JSON exists for world gen. Bountiful Trees provides the only renewable surface source.
