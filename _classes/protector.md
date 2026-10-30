---
title: Protector
slug: protector
category: Promotional
role: Promotional
description: 'The Protector is a melee class that can turn the fight in their favor by placing a powerful dome shield.

  '
traits:
- name: Bleeding
  note: '[[card:bloody-blade]] Card unlocks at Level 4'
- name: Shield
  note: 'Built into $ultimate'
- name: Melee
  note: 'Built into $passive'
- name: Stim
  note: '[[card:regenerative-field]] Card unlocks at Level 16'
passive:
  name: Bleed Lifesteal
  description: Heal for 50% of bleed damage dealt. Resist 30% melee damage.
active:
  name: Drop Shield
  description: Activates a protective Drop Shield that prevents any projectiles from passing through.
  duration: 15s
  cooldown: 200s
ultimate:
  name: Drop Shield
  description: Activates a protective Drop Shield that prevents any projectiles from passing through.
  duration: 15s
  cooldown: 200s
weapons:
- name: Markza Mk 1 Marksman Rifle
  slug: markza
- name: Gnasher Shotgun
  slug: gnasher
- name: Talon Autopistol
  slug: talon
# right=N1, left=N2, down=Pistol, up=Grenade - confirmed from
# ref/Class Menus/Class Menu - Protector.jpg: Markza on-screen left (N1),
# Gnasher on-screen right (N2), Talon in the pistol slot, no grenade
# shown (X).
weapon_slots:
  right:
    name: Markza Mk 1 Marksman Rifle
    slug: markza
  left:
    name: Gnasher Shotgun
    slug: gnasher
  down:
    name: Talon Autopistol
    slug: talon
# Perks verified in-game (ref/Class Perks/Protector - Perks - 01/02):
# Ultimate Cooldown +5% @1; Movement Speed +13% @2, +16% @3; Damage
# Resistance +10% @1; Damage +5% @1, +10% @2. Values marked '~' are
# extrapolated from the per-rank step; '?' has no data yet. (The previous
# wiki-sourced set - Health / Critical Damage / Ammo Capacity - was wrong.)
perks:
  up:
    name: Ultimate Cooldown
    description: '+{value} Cooldown Speed'
    values: ['5%', '~10%', '~15%', '~20%', '~25%', '~30%', '~35%', '~40%', '~45%', '~50%']
  right:
    name: Damage Resistance
    description: '+{value} Damage Resistance'
    values: ['10%', '?', '?', '?', '?', '?', '?', '?', '?', '?']
  down:
    name: Damage
    description: '+{value} Damage'
    values: ['5%', '10%', '~15%', '~20%', '~25%', '~30%', '~35%', '~40%', '~45%', '~50%']
  left:
    name: Movement Speed
    description: '+{value} Movement Speed'
    values: ['~10%', '13%', '16%', '~19%', '~22%', '~25%', '~28%', '~31%', '~34%', '~37%']
cards:
- name: Score Boost
  slug: score-boost
  rarity: Common
  unlock_level: 1
  description: '{X} increased team score in Horde and {X} time bonus in Escape.'
  levels:
  - X: 5%
  - X: 7%
  - X: 9%
  - X: 12%
  - X: '15%'
  - X: 18%
- name: Big Knife
  slug: big-knife
  rarity: Common
  unlock_level: 2
  description: '{X} increased melee damage.'
  levels:
  - X: 20%
  - X: '50%'
  - X: '60%'
  - X: '70%'
  - X: '100%'
  - X: '130%'
- name: Bloody Blade
  slug: bloody-blade
  rarity: Rare
  unlock_level: 4
  description: Melee hits cause bleeding for {X} of damage.
  levels:
  - X: 50%
  - X: '70%'
  - X: '90%'
  - X: '110%'
  - X: '120%'
  - X: '130%'
- name: Gnasher M45 Mod
  slug: gnasher-m45-mod
  rarity: Common
  unlock_level: 6
  description: '{X} extra damage and {Y} active effects with the Gnasher.'
  levels:
  - X: '10%'
    Y: '5%'
  - X: '20%'
    Y: '10%'
  - X: '30%'
    Y: '15%'
  - X: '40%'
    Y: '20%'
  - X: '50%'
    Y: '25%'
  - X: '60%'
    Y: '30%'
- name: Close Range Recharge
  slug: close-range-recharge
  rarity: Epic
  unlock_level: 8
  description: Kills within 5m recharge Drop Shield by {X}.
  levels:
  - X: 15s
  - X: '17s'
  - X: '20s'
  - X: '22s'
  - X: '25s'
  - X: '28s'
- name: Drop Shield Duration
  slug: drop-shield-duration
  rarity: Rare
  unlock_level: 9
  description: '{X} increased Drop Shield duration.'
  levels:
  - X: 50%
  - X: '60%'
  - X: '70%'
  - X: '80%'
  - X: '90%'
  - X: '100%'
- name: Epic Score Boost
  slug: epic-score-boost
  rarity: Epic
  unlock_level: 10
  description: '{X} increased team score in Horde and {X} time bonus in Escape.'
  levels:
  - X: 10%
  - X: 15%
  - X: 20%
  - X: 25%
  - X: 30%
  - X: '35%'
- name: Regenerative Field
  slug: regenerative-field
  rarity: Legendary
  unlock_level: 16
  description: Regenerate {X} stim per second while avoiding damage.
  levels:
  - X: '2'
  - X: '4 stim'
  - X: '6 stim'
  - X: '8 stim'
  - X: '10 stim'
  - X: '12 stim'
- name: Heroic Venom Talon
  slug: heroic-venom-talon
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Talon Autopistol}.'
---
