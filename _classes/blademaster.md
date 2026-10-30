---
title: Blademaster
slug: blademaster
category: Assault
role: Assault
description: 'The Blademaster is a melee class that cuts through enemies with shocking speed and aggression.

  '
traits:
- name: Bleeding
  note: 'Melee Bleed Damage Perk (▼ Down Slot) + [[card:venom-blade]] Card unlocks at Level 15'
- name: Melee
  note: 'Built into $passive'
- name: Stim
  note: '[[card:shock-shield]] Card unlocks at Level 7 + [[card:energy-surge]] Card unlocks at Level 18'
passive:
  name: Melee Lifesteal
  description: Kills with melee or bleed damage heal half of your max HP. Resist 30% melee damage.
active:
  name: Electroblade
  description: While active, any enemies struck with melee will be shocked and stunned.
  duration: 15s
  cooldown: 300s
ultimate:
  name: Electroblade
  description: While active, any enemies struck with melee will be shocked and stunned.
  duration: 15s
  cooldown: 300s
weapons:
- name: Claw Light Machine Gun
  slug: claw-lmg
- name: Gnasher Shotgun
  slug: gnasher
- name: Talon Autopistol
  slug: talon
- name: Flashbang
  slug: flashbang
# right=N1, left=N2, down=Pistol, up=Grenade - confirmed from
# ref/Class Menus/Class Menu - Blademaster.jpg: Claw LMG on-screen left
# (N1), Gnasher on-screen right (N2), Talon in the pistol slot, Flashbang
# in the grenade slot.
weapon_slots:
  right:
    name: Claw Light Machine Gun
    slug: claw-lmg
  left:
    name: Gnasher Shotgun
    slug: gnasher
  down:
    name: Talon Autopistol
    slug: talon
  up:
    name: Flashbang
    slug: flashbang
perks:
  up:
    name: Health Regeneration
    values: ['10%', '20%', '30%', '40%', '50%', '60%', '70%', '80%', '90%', '100%']
  right:
    name: Damage Resistance
    values: ['10%', '14%', '18%', '22%', '24%', '26%', '27%', '28%', '29%', '30%']
  down:
    name: Melee Bleed Damage
    values: ['15%', '30%', '45%', '60%', '75%', '90%', '105%', '120%', '135%', '150%']
  left:
    name: Movement Speed
    values: ['10%', '13%', '16%', '19%', '22%', '25%', '27%', '28%', '29%', '30%']
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
- name: Short Range Deflection
  slug: short-range-deflection
  rarity: Common
  unlock_level: 2
  description: '{X} ballistic damage resistance within 5m.'
  levels:
  - X: '20%'
  - X: '24%'
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Brawler
  slug: brawler
  rarity: Common
  unlock_level: 3
  description: '{X} increased melee damage.'
  levels:
  - X: '20%'
  - X: '50%'
  - X: '60%'
  - X: '70%'
  - X: '100%'
  - X: '130%'
- name: Shock Chain
  slug: shock-chain
  rarity: Rare
  unlock_level: 5
  description: Electroblade affects {X} nearby enemies.
  levels:
  - X: '1'
  - X: '2'
  - X: '3'
  - X: '4'
  - X: '5'
  - X: '6'
- name: Efficient Executioner
  slug: efficient-executioner
  unlock_level: 6
  description: 'Every {X} execution drops an ammo crate ({Y}).'
  rarity: Common
  levels:
  - X: '5th'
    Y: 'Ammo Pilfer'
  - X: '4th'
    Y: 'Ammo Pilfer'
  - X: '3rd'
    Y: 'Ammo Pilfer'
  - X: '2nd'
    Y: 'Ammo Pilfer'
  - X: '1st'
    Y: 'Ammo Pilfer'
  - X: '1st'
    Y: 'Ammo Pouch'
- name: Shock Shield
  slug: shock-shield
  rarity: Rare
  unlock_level: 7
  description: Using Electroblade gives {X} Stim.
  levels:
  - X: '100 HP'
  - X: '130 HP'
  - X: '160 HP'
  - X: '190 HP'
  - X: '220 HP'
  - X: '250 HP'
- name: Banana Clip
  slug: banana-clip
  rarity: Common
  unlock_level: 8
  description: '{X} extended Talon Autopistol magazine.'
  levels:
  - X: '40%'
  - X: '55%'
  - X: '70%'
  - X: '85%'
  - X: '100%'
  - X: '115%'
- name: Deep Pockets
  slug: deep-pockets
  rarity: Rare
  unlock_level: 9
  description: '{X} increased pistol capacity.'
  levels:
  - X: '40%'
  - X: '55%'
  - X: '70%'
  - X: '85%'
  - X: '100%'
  - X: '115%'
- name: Thrill of the Hunt
  slug: thrill-of-the-hunt
  rarity: Epic
  unlock_level: 10
  description: '{X} resistance and {Y} forced healing within 2.5m of bleeding enemies.'
  levels:
  - X: '20%'
    Y: '50 HP'
  - X: '24%'
    Y: '60 HP'
  - X: '26%'
    Y: '50 HP'
  - X: '28%'
    Y: '70 HP'
  - X: '30%'
    Y: '75 HP'
  - X: '32%'
    Y: '80 HP'
- name: Nimble
  slug: nimble
  rarity: Rare
  unlock_level: 11
  description: Slide into cover {X} faster and further away.
  levels:
  - X: '20%'
  - X: '30%'
  - X: 40%
  - X: 45%
  - X: '50%'
  - X: '55%'
- name: Venom Resistance
  slug: venom-resistance
  rarity: Rare
  unlock_level: 11
  description: '{X} damage resistance while in Venom.'
  levels:
  - X: '20%'
  - X: '24%'
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: On the Flank
  slug: on-the-flank
  unlock_level: 12
  description: '{X} additional ballistic damage when attacking from the side or behind.'
  levels:
  - X: '50%'
  - X: 70%
  - X: 85%
  - X: '95%'
  - X: '105%'
  - X: '115%'
  rarity: Epic
- name: Gnasher Mastery
  slug: gnasher-mastery
  unlock_level: 12
  description: '{X} extra damage and {Y} active effects with the Gnasher.'
  levels:
  - X: '10%'
    Y: '5%'
  - X: 20%
    Y: 10%
  - X: 30%
    Y: 15%
  - X: '40%'
    Y: '20%'
  - X: '50%'
    Y: '25%'
  - X: '60%'
    Y: '30%'
  rarity: Epic
- name: Mid Range Deflection
  slug: mid-range-deflection
  rarity: Rare
  unlock_level: 13
  description: '{X} ballistic damage resistance between 5-10m.'
  levels:
  - X: '20%'
  - X: '24%'
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Epic Score Boost
  slug: epic-score-boost
  rarity: Epic
  unlock_level: 14
  description: '{X} increased team score in Horde and {X} time bonus in Escape.'
  levels:
  - X: 10%
  - X: 15%
  - X: 20%
  - X: 25%
  - X: 30%
  - X: '35%'
- name: Venom Blade
  slug: venom-blade
  rarity: Epic
  unlock_level: 15
  description: Melee damage in Venom causes bleeding for {X} of damage.
  levels:
  - X: '130%'
  - X: '140%'
  - X: '145%'
  - X: '150%'
  - X: '155%'
  - X: '160%'
- name: Ambush
  slug: ambush
  rarity: Legendary
  unlock_level: 16
  description: Kills from behind reduce ultimate cooldown by {X}.
  levels:
  - X: '15s'
  - X: '18s'
  - X: '21s'
  - X: '24s'
  - X: '27s'
  - X: '30s'
- name: Brutal Claw
  slug: brutal-claw
  rarity: Epic
  unlock_level: 17
  description: '{X} extra damage and {Y} active effects with the Claw.'
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
- name: Energy Surge
  slug: energy-surge
  rarity: Epic
  unlock_level: 18
  description: Gain 1 Stim per 0.5s near Energy Taps.
- name: Blade Dancer
  slug: blade-dancer
  rarity: Legendary
  unlock_level: 19
  description: Each melee or bleed kill gives +{X} melee damage for 15s.
  levels:
  - X: '25%'
  - X: '30%'
  - X: '35%'
  - X: '40%'
  - X: '45%'
  - X: '50%'
- name: Heroic Venom Claw
  slug: heroic-venom-claw
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Claw Light Machine Gun}.'
---
