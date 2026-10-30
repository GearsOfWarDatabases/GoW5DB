---
title: Mechanic
slug: mechanic
category: Support
role: Support
engineer: true
description: 'The Mechanic is an engineer class that can construct a solid defense with speed and efficiency.

  '
traits:
- name: Repairing
  note: 'Built into [[weapon:repair-tool]]'
- name: Bleeding
  note: '[[card:shredder-rounds]] Card unlocks at Level 19'
- name: Summon
  note: 'Built into $ultimate'
- name: Stim
  note: '[[card:healing-repair]] Card unlocks at Level 16'
passive:
  name: Builder
  description: Build new fortifications at a 15% discount, and carry fortifications faster.
active:
  name: Turret
  description: Summon a powerful mounted turret.
  duration: 20s
  cooldown: 200s
ultimate:
  name: Turret
  description: Summon a powerful mounted turret.
  duration: 20s
  cooldown: 200s
weapons:
- name: Enforcer Submachine Gun
  slug: enforcer
- name: Overkill Shotgun
  slug: overkill
- name: Repair Tool
  slug: repair-tool
# right=N1, left=N2, down=Pistol, up=Grenade - see weapon-slot.html's own
# comment for why these are fixed ability-slot names, not physical
# left/right (PC and console mirror the N1/N2 side). Confirmed from
# ref/Class Menus/Class Menu - Mechanic.jpg (+ _2.jpg): Enforcer in the
# game's own slot 1 (PC-left/console-right = N1), Overkill in slot 2
# (PC-right/console-left = N2), Repair Tool in the pistol slot (Mechanic
# has no real sidearm), no grenade shown in either screenshot.
weapon_slots:
  right:
    name: Enforcer Submachine Gun
    slug: enforcer
  left:
    name: Overkill Shotgun
    slug: overkill
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
  max_level: 6
  description: '{X} increased team score in Horde and {X} time bonus in Escape.'
  levels:
  - X: 5%
  - X: 7%
  - X: 9%
  - X: 12%
  - X: '15%'
  - X: 18%
- name: Ingenuity
  slug: ingenuity
  unlock_level: 2
  description: Repair speed increased by {X} while repair cost is reduced by {Y}.
  levels:
  - X: '20%'
    Y: '10%'
  - X: 30%
    Y: 15%
  - X: 40%
    Y: 20%
  - X: 50%
    Y: 25%
  - X: 55%
    Y: 27%
  - X: 60%
    Y: 30%
  rarity: Common
- name: Rootkit
  slug: rootkit
  unlock_level: 3
  description: Repairing fortifications speeds up the Ultimate cooldown by {X} for each second of repair.
  levels:
  - X: '1s'
  - X: '1.25s'
  - X: 1.5s
  - X: 1.75s
  - X: 2s
  - X: 2.25s
  rarity: Common
- name: Reinforced Fabrication
  slug: reinforced-fabrication
  unlock_level: 4
  description: '{X} increased health on fortifications you build.'
  levels:
  - X: '50%'
  - X: '75%'
  - X: '100%'
  - X: '125%'
  - X: '150%'
  - X: 175%
  rarity: Common
- name: Armor Plating
  slug: armor-plating
  unlock_level: 5
  description: Fortifications with over 50% health take {X} less damage.
  levels:
  - X: '20%'
  - X: '24%'
  - X: '26%'
  - X: '28%'
  - X: 30%
  - X: 32%
  rarity: Rare
- name: Robotic Porting
  slug: robotic-porting
  unlock_level: 6
  description: '{X} reduced recoil on DeeBee weapons.'
  levels:
  - X: '50%'
  - X: 60%
  - X: '70%'
  - X: '80%'
  - X: '90%'
  - X: '95%'
  rarity: Common
- name: Overclocked Locker
  slug: overclocked-locker
  rarity: Rare
  unlock_level: 7
  description: Weapons Lockers you build reload {X} faster.
  levels:
  - X: '10%'
  - X: '15%'
  - X: 20%
  - X: 23%
  - X: 25%
  - X: 27%
- name: Flow
  slug: flow
  rarity: Common
  unlock_level: 8
  description: All damage reduced by {X} when repairing.
  levels:
  - X: '20%'
  - X: '24%'
  - X: 26%
  - X: 28%
  - X: '30%'
  - X: '32%'
- name: Efficient Sentry
  slug: efficient-sentry
  rarity: Rare
  unlock_level: 9
  description: The cost to refill sentry ammo is reduced by {X}.
  levels:
  - X: '20%'
  - X: '30%'
  - X: 40%
  - X: 45%
  - X: 50%
  - X: '55%'
- name: Efficient Fabrication
  slug: efficient-fabrication
  rarity: Epic
  unlock_level: 10
  description: '{X} reduced fortification cost.'
  levels:
  - X: '15%'
  - X: '20%'
  - X: '25%'
  - X: '28%'
  - X: '30%'
  - X: 32%
- name: Custom Robotics
  slug: custom-robotics
  rarity: Rare
  unlock_level: 11
  description: '{X} increased damage and {Y} active effects on DeeBee weapons.'
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
- name: Overload
  slug: overload
  rarity: Epic
  unlock_level: 12
  art_fit: contain
  description: Fortifications over 50% health do {X} more damage.
  levels:
  - X: '15%'
  - X: 20%
  - X: 25%
  - X: 30%
  - X: 35%
  - X: '40%'
- name: Long Range Resistance
  slug: long-range-resistance
  rarity: Rare
  unlock_level: 13
  description: Take {X} less damage from precision weapons.
  levels:
  - X: '20%'
  - X: 24%
  - X: 26%
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Best Friends
  slug: best-friends
  rarity: Epic
  unlock_level: 14
  description: 'When within 10m of Jack, repair speed is increased by {X} while repair cost is reduced by {Y}.'
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
- name: Epic Score Boost
  slug: epic-score-boost
  rarity: Epic
  unlock_level: 15
  description: '{X} increased team score in Horde and {X} time bonus in Escape.'
  levels:
  - X: 10%
  - X: 15%
  - X: 20%
  - X: 25%
  - X: 30%
  - X: '35%'
- name: Healing Repair
  slug: healing-repair
  rarity: Legendary
  unlock_level: 16
  description: Repairing provides {X} Stim.
  levels:
  - X: '2%'
  - X: '2.4%'
  - X: 2.5%
  - X: 2.6%
  - X: '3%'
  - X: '3.4%'
- name: Personal Defense
  slug: personal-defense
  rarity: Epic
  unlock_level: 18
  description: Consecutive hits with the Enforcer increases damage {X} up to 100%.
  levels:
  - X: 1%
  - X: 2%
  - X: 3%
  - X: 4%
  - X: '5%'
  - X: '6%'
- name: Shredder Rounds
  slug: shredder-rounds
  rarity: Legendary
  unlock_level: 19
  description: Anyone using the turret deals {X} bleeding damage.
  levels:
  - X: 5%
  - X: 10%
  - X: 15%
  - X: '20%'
  - X: '25%'
  - X: '30%'
- name: Heroic Venom Enforcer
  slug: heroic-venom-enforcer
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Enforcer Submachine Gun}.'
---
