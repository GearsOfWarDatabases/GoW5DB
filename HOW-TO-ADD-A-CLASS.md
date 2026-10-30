# How to add or edit a class

Every class is one file in the `_classes/` folder, e.g. `_classes/anchor.md`.
Copy an existing file, rename it, and edit the fields. The page appears
automatically at `/classes/<filename>/` and on the Classes grid.

## Basic info

```yaml
---
title: Anchor              # display name
slug: anchor               # used for image filenames, keep lowercase-with-dashes
category: Tank             # Assault, Tank, Support or Promotional (grid grouping)
role: Tank                 # small tag shown on the card/page
description: >
  One or two sentences about the class.
```

## Abilities

```yaml
passive:
  name: Pistol Mastery
  description: "Deal +30% pistol damage."

active:
  name: Barrier
  description: "Deploy an invulnerable shield."
  duration: "20s"          # optional
  cooldown: "150s"         # optional

ultimate:
  name: Barrier
  description: "Deploy an invulnerable shield."
  duration: "20s"
  cooldown: "150s"
```

## Weapons

```yaml
weapons:
  - name: Retro Lancer
    slug: retro-lancer     # image: images/weapons/<slug>.png
  - name: Boltok Pistol
    slug: boltok
```

## Cards (with per-level values)

Write the description once, using `{X}` where the number changes per level.
Then list the value for each level (1 to 6), one line per level.
Use `"?"` for values you don't know yet - they show as a dashed box.

```yaml
cards:
  - name: Rootkit
    slug: rootkit          # image: images/cards/<class-slug>-<card-slug>.png
    rarity: Uncommon       # Common, Uncommon, Rare, Epic, Legendary
    unlock_level: 4        # class level that unlocks the card
    display_level: 3       # which level is selected when the page loads (optional)
    description: "Speeds up the $ultimate cooldown by {X} per second of repair."
    levels:
      - X: "1s"            # level 1
      - X: "1.25s"         # level 2
      - X: "1.5s"          # level 3
      - X: "1.75s"         # level 4
      - X: "2s"            # level 5
      - X: "?"             # level 6 (unknown)
```

Two numbers that both change? Use `{X}` and `{Y}`:

```yaml
    description: "Repair speed +{X} and repair cost -{Y}."
    levels:
      - { X: "35%", Y: "15%" }   # level 1
      - { X: "40%", Y: "18%" }   # level 2
      # ...one line per level
```

Extra tricks in any description:
- `$ultimate`, `$active`, `$passive` - inserts that ability's name, highlighted
- `{50%}` (a number in braces, no X/Y) - a fixed value, just highlighted

Readers click the level pips 1-6 on each card to switch values.

## Card upgrade costs

Costs are the same for every card of a rarity, so they live in one file:
`_data/card_costs.yml`. Replace the `"?"` entries with the number of
duplicates needed and every card page shows them automatically.

## Perks

Names only (shown on the d-pad):

```yaml
perks:
  up:    { name: Critical Damage }
  right: { name: Damage Resistance }
  down:  { name: Damage }
  left:  { name: Ammo Regeneration }
```

To show per-level values, add `values` to any perk -
a level table appears below the d-pad:

```yaml
perks:
  up:
    name: Critical Damage
    description: "+{value} critical damage"
    values: ["4%", "8%", "12%", "16%", "20%", "24%", "28%", "32%", "36%", "40%"]
```

Perk costs are universal (same for every perk and class) and come from
`_data/perk_costs.yml`. Numbers with thousands use `'` as the divider and
must be double-quoted in YAML, e.g. `"1,000"`.

## Images (all optional - a placeholder shows if missing)

| What | Path |
|------|------|
| Class icon | `images/classes/icons/<slug>.png` |
| Passive / active / ultimate | `images/abilities/<slug>-passive.png` etc. |
| Weapon | `images/weapons/<weapon-slug>.png` |
| Card art | `images/cards/<class-slug>-<card-slug>.png` |
| Perk icons | `images/perks/<slug>-up.png`, `-right`, `-down`, `-left` |
