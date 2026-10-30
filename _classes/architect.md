---
title: Architect
slug: architect
category: Promotional
role: Promotional
engineer: true
description: 'The Architect is an engineer class that uses deception to manipulate the enemy.

  '
traits:
- name: Repairing
  note: 'Built into [[weapon:repair-tool]]'
- name: Stim
  note: '[[card:regenerative-field]] Card unlocks at Level 16'
passive:
  name: Discount Builder
  description: Build new fortifications at a 15% discount, and carry fortifications faster.
active:
  name: Hologram
  description: Deploys a holographic decoy that moves directly forward, drawing enemy fire.
  duration: 7s
  cooldown: 150s
ultimate:
  name: Hologram
  description: Deploys a holographic decoy that moves directly forward, drawing enemy fire.
  duration: 7s
  cooldown: 150s
weapons:
- name: EMBAR Railgun
  slug: embar
- name: Enforcer Submachine Gun
  slug: enforcer
- name: Repair Tool
  slug: repair-tool
# right=N1, left=N2, down=Pistol, up=Grenade - confirmed from
# ref/Class Menus/Class Menu - Architect.jpg: EMBAR on-screen left (N1),
# Enforcer on-screen right (N2), Repair Tool in the pistol slot (no real
# sidearm), no grenade shown.
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
perks:
  up:
    name: Fortification Damage
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  right:
    name: Repair Cost Reduction
    values: ['5%', '9%', '13%', '17%', '20%', '22%', '24%', '26%', '28%', '30%']
  down:
    name: Repair Speed
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  left:
    name: Fortification Health
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
- name: Flow
  slug: flow
  rarity: Common
  unlock_level: 2
  description: '{X} damage resistance while repairing.'
  levels:
  - X: 20%
  - X: ~22.5%
  - X: ~25%
  - X: ~27.5%
  - X: 30%
  - X: 32%
- name: Deception
  slug: deception
  rarity: Common
  unlock_level: 3
  description: '{X} extra damage when flanking.'
  levels:
  - X: 100%
  - X: '120%'
  - X: '140%'
  - X: '160%'
  - X: '180%'
  - X: 200%
- name: Top of the Line
  slug: top-of-the-line
  rarity: Rare
  unlock_level: 4
  description: Fortifications over 50% health do {X} more damage.
  levels:
  - X: 15%
  - X: '20%'
  - X: '25%'
  - X: 30%
  - X: 35%
  - X: '40%'
- name: Repair Efficiency
  slug: repair-efficiency
  rarity: Common
  unlock_level: 6
  description: 'Repair speed increased by {X} while repair cost is reduced by {Y}.'
  levels:
  - X: '20%'
    Y: '10%'
  - X: '30%'
    Y: '15%'
  - X: '40%'
    Y: '20%'
  - X: '50%'
    Y: '25%'
  - X: '55%'
    Y: '27%'
  - X: '60%'
    Y: '30%'
- name: Stim Capacity
  slug: stim-capacity
  rarity: Rare
  unlock_level: 7
  description: Stim Capacity is increased {X}.
  levels:
  - X: 20%
  - X: ~40%
  - X: ~60%
  - X: ~80%
  - X: 100%
  - X: 110%
- name: Rootkit
  slug: rootkit
  rarity: Epic
  unlock_level: 8
  description: 1s of repairing reduces cooldown by {X}.
  levels:
  - X: 1s
  - X: '1.25s'
  - X: 1.5s
  - X: 1.75s
  - X: '2s'
  - X: '2.25s'
- name: Hologram Lifetime
  slug: hologram-lifetime
  rarity: Rare
  unlock_level: 9
  description: '{X} longer Hologram duration.'
  levels:
  - X: 40%
  - X: '70%'
  - X: '100%'
  - X: 130%
  - X: 150%
  - X: '170%'
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
- name: Hologram Extend
  slug: hologram-extend
  rarity: Epic
  unlock_level: 12
  description: Ballistic hits extend Hologram by {X}.
  levels:
  - X: 50%
  - X: 60%
  - X: 70%
  - X: '80%'
  - X: '90%'
  - X: '100%'
- name: Regenerative Field
  slug: regenerative-field
  rarity: Legendary
  unlock_level: 16
  art_fit: contain
  description: Regenerate {X} stim per second while avoiding damage.
  levels:
  - X: '2'
  - X: '4'
  - X: '6'
  - X: '8'
  - X: '10'
  - X: '12'
- name: Heroic Venom Snub
  slug: heroic-venom-snub
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Snub}.'
---
