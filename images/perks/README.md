# Perk Images

Place perk icon images here. Four SVGs per class (one per D-pad direction):

Pattern: `{class-slug}-{direction}.svg`

Directions: `up`, `right`, `down`, `left`

Examples:
- `blademaster-up.svg` - Health Regeneration
- `blademaster-right.svg` - Damage Resistance
- `blademaster-down.svg` - Melee Bleed Damage
- `blademaster-left.svg` - Movement Speed
- `demolitions-up.svg` - Ultimate Cooldown
- ... (same pattern for all 19 classes × 4 directions = 76 images)

Many perk names repeat across classes (e.g. "Health" shows up on 11 different
class/direction slots) - they all reuse the same source icon, just copied
under each class's own filename per the pattern above.

Traced from ref/Class Perks screenshots (potrace, alpha-thresholded) rather
than drawn from scratch, so the shapes match the real in-game icons. Filled
white (#f3f3f3) at a fixed color rather than `currentColor`, since these are
referenced via plain `<img src>` - external SVGs loaded that way render in
an isolated context and don't inherit page CSS color.

Currently covered (41 of 76 slots, 5 distinct icons - some perk names share
art): Health, Damage Resistance, Ultimate Cooldown, Movement Speed, Damage,
Assault Rifle Damage, Critical Damage.

Still missing source material for: Ammo Capacity, Ammo Regeneration,
Chaingun Ammo Regeneration, Explosive Resupply, Feedback Boost, Fortification
Damage, Fortification Health, Health Regeneration, Melee Bleed Damage,
Precision Weapons Damage, Repair Cost Reduction, Repair Speed, Shotgun
Damage, Ultimate Duration, Ultimate Recharge on Kill - those slots fall back
to the dashed placeholder box until a screenshot turns up.
