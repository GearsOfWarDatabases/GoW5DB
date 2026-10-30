---
title: Striker
slug: striker
category: Promotional
role: Promotional
description: 'The Striker is a melee class focused on crowd control.

  '
traits:
- name: Repairing
  note: 'Built into [[weapon:repair-tool]]'
- name: Bleeding
  note: '[[card:blunt-instrument]] Card unlocks at Level 6'
- name: Melee
  note: 'Built into $ultimate'
- name: Stim
  note: '[[card:stim-siphon]] Card unlocks at Level 2'
passive:
  name: Reactive Speed
  description: When hit, move 50% faster for 4 seconds.
active:
  name: Enhanced Melee
  description: Melee hits will knock back enemies and deal +50% damage.
  duration: 20s
  cooldown: 200s
ultimate:
  name: Enhanced Melee
  description: Melee hits will knock back enemies and deal +50% damage.
  duration: 20s
  cooldown: 200s
weapons:
- name: EMBAR Railgun
  slug: embar
- name: Enforcer Submachine Gun
  slug: enforcer
- name: Repair Tool
  slug: repair-tool
- name: Flashbang
  slug: flashbang
# right=N1, left=N2, down=Pistol, up=Grenade - confirmed from
# ref/Class Menus/Class Menu - Striker.jpg: EMBAR on-screen left (N1),
# Enforcer on-screen right (N2), Repair Tool in the pistol slot,
# Flashbang in the grenade slot.
weapon_slots:
  right:
    name: EMBAR Railgun
    slug: embar
  left:
    name: Enforcer Submachine Gun
    slug: enforcer
  down:
    name: Repair Tool
    slug: repair-tool
  up:
    name: Flashbang
    slug: flashbang
perks:
  up:
    name: Health
  right:
    name: Feedback Boost
    description: Damage dealt is converted to Ultimate Cooldown reduction.
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  down:
    name: Movement Speed
  left:
    name: Health Regeneration
    values: ['10%', '20%', '30%', '40%', '50%', '60%', '70%', '80%', '90%', '100%']
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
- name: Stim Siphon
  slug: stim-siphon
  rarity: Common
  unlock_level: 2
  description: Melee hits grant {X} stim.
  levels:
  - X: 20HP
  - X: '45'
  - X: '70'
  - X: '95'
  - X: '120'
  - X: '145'
- name: Melee Rush
  slug: melee-rush
  rarity: Rare
  unlock_level: 4
  description: Melee kills cooldown ultimate by {X}.
  levels:
  - X: 20s
  - X: '23s'
  - X: '26s'
  - X: '29s'
  - X: '32s'
  - X: '35s'
- name: Blunt Instrument
  slug: blunt-instrument
  rarity: Common
  unlock_level: 6
  description: Breaker Mace deals {X} bleeding damage.
  levels:
  - X: 50%
  - X: '75%'
  - X: '90%'
  - X: '110%'
  - X: '120%'
  - X: '130%'
- name: First Strike
  slug: first-strike
  rarity: Epic
  unlock_level: 8
  description: Deal +{X} damage to undamaged enemies.
  levels:
  - X: 50%
  - X: '60%'
  - X: '70%'
  - X: '80%'
  - X: '90%'
  - X: '100%'
- name: Melee Armor
  slug: melee-armor
  rarity: Rare
  unlock_level: 9
  description: Resist {X} melee damage.
  levels:
  - X: 10%
  - X: '24%'
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
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
- name: GSD
  slug: gsd
  rarity: Legendary
  unlock_level: 16
  description: Enemies killed by melee explode for {X} damage.
  levels:
  - X: 50%
  - X: '60%'
  - X: '70%'
  - X: '75%'
  - X: '80%'
  - X: '85%'
- name: Heroic Venom Breaker Mace
  slug: heroic-venom-breaker-mace
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Breaker Mace}.'
---
