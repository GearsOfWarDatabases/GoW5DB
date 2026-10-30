---
title: Infiltrator
slug: infiltrator
category: Assault
role: Assault
description: 'The tip of the spear, the Infiltrator stays close to the enemy and wreaks havoc with shotguns and stealth.

  '
traits:
- name: Bleeding
  note: '[[card:laceration]] Card unlocks at Level 5'
- name: Invisibility
  note: 'Built into $ultimate'
- name: Stim
  note: '[[card:reaper]] Card unlocks at Level 4'
passive:
  name: Cloak Ambush
  description: Exiting Cloak by firing a weapon deals 10x damage for that shot.
active:
  name: Camouflage
  description: Become invisible to enemies. Can execute nearby drones while cloaked.
  duration: 15s
  cooldown: 300s
ultimate:
  name: Camouflage
  description: Become invisible to enemies. Can execute nearby drones while cloaked.
  duration: 15s
  cooldown: 300s
weapons:
- name: Retro Lancer
  slug: retro-lancer
- name: Gnasher Shotgun
  slug: gnasher
- name: Talon Autopistol
  slug: talon
- name: Flashbang
  slug: flashbang
# right=N1, left=N2, down=Pistol, up=Grenade - confirmed from
# ref/Class Menus/Class Menu - Infiltrator.jpg: Retro Lancer on-screen
# left (N1), Gnasher on-screen right (N2), Talon in the pistol slot,
# Flashbang in the grenade slot.
weapon_slots:
  right:
    name: Retro Lancer
    slug: retro-lancer
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
    name: Health
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  right:
    name: Movement Speed
    values: ['10%', '13%', '16%', '19%', '22%', '25%', '27%', '28%', '29%', '30%']
  down:
    name: Shotgun Damage
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  left:
    name: Health Regeneration
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
- name: Long Reach
  slug: long-reach
  rarity: Common
  unlock_level: 2
  description: '{X} increased power pickup distance.'
  levels:
  - X: '100%'
  - X: '200%'
  - X: '300%'
  - X: '400%'
  - X: '500%'
  - X: '600%'
- name: Driven
  slug: driven
  rarity: Common
  unlock_level: 3
  description: '{X} damage resistance from explosives.'
  levels:
  - X: '20%'
  - X: 24%
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Reaper
  slug: reaper
  rarity: Common
  unlock_level: 4
  description: Shotgun kills give {X} Stim.
  levels:
  - X: 15%
  - X: 25%
  - X: 35%
  - X: 40%
  - X: 45%
  - X: 50%
- name: Laceration
  slug: laceration
  rarity: Rare
  unlock_level: 5
  description: Shotgun damage within 5 meters causes enemies to bleed for {X} of damage dealt.
  levels:
  - X: '30%'
  - X: '50%'
  - X: 70%
  - X: 90%
  - X: 100%
  - X: 110%
- name: Overkill Stock
  slug: overkill-stock
  rarity: Common
  unlock_level: 6
  description: '{X} reduced recoil.'
  levels:
  - X: '30%'
  - X: '40%'
  - X: '50%'
  - X: '70%'
  - X: '90%'
  - X: '95%'
- name: Cloak Batteries
  slug: cloak-batteries
  rarity: Rare
  unlock_level: 7
  description: Cloak duration increased by {X}.
  levels:
  - X: '10%'
  - X: '20%'
  - X: '30%'
  - X: '40%'
  - X: '50%'
  - X: '60%'
- name: Shotgun Speed Loaders
  slug: shotgun-speed-loaders
  rarity: Common
  unlock_level: 8
  description: '{X} larger active reload window with the Shotguns.'
  levels:
  - X: '50%'
  - X: '100%'
  - X: 150%
  - X: 175%
  - X: '200%'
  - X: '225%'
- name: Enhanced Stim
  slug: enhanced-stim
  rarity: Rare
  unlock_level: 9
  description: Damage from all sources reduced by {X} while Stimmed.
  levels:
  - X: '20%'
  - X: '30%'
  - X: 40%
  - X: 50%
  - X: 55%
  - X: 60%
- name: Blood Resonance
  slug: blood-resonance
  rarity: Epic
  unlock_level: 10
  description: Bleeding enemies take {X} more shotgun damage.
  levels:
  - X: '50%'
  - X: '80%'
  - X: 110%
  - X: 140%
  - X: '150%'
  - X: '160%'
- name: Custom Gnasher
  slug: custom-gnasher
  rarity: Rare
  unlock_level: 11
  description: '{X} increased damage and active effects.'
  levels:
  - X: '5%'
  - X: 10%
  - X: '15%'
  - X: '20%'
  - X: '25%'
  - X: '30%'
- name: Stim Batteries
  slug: stim-batteries
  rarity: Epic
  unlock_level: 12
  description: '{X} increased Stim capacity.'
  levels:
  - X: '20%'
  - X: 90%
  - X: 130%
  - X: 170%
  - X: 200%
  - X: '220%'
- name: Overkill Ammo Capacity
  slug: overkill-ammo-capacity
  rarity: Rare
  unlock_level: 13
  description: Overkill ammo capacity increased by {X}.
  levels:
  - X: '10%'
  - X: 15%
  - X: 20%
  - X: 25%
  - X: '30%'
  - X: '35%'
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
- name: Healing Jolt
  slug: healing-jolt
  rarity: Epic
  unlock_level: 15
  description: Picking up energy heals for {X}.
  levels:
  - X: '30%'
  - X: '45%'
  - X: '60%'
  - X: '75%'
  - X: 90%
  - X: '100%'
- name: Chain
  slug: chain
  rarity: Legendary
  unlock_level: 16
  description: Executing enemies while the Cloak ability is active extends the duration of the ability by {X}.
  levels:
  - X: '2s'
  - X: 3s
  - X: 3.5s
  - X: 4s
  - X: '4.5s'
  - X: '5s'
- name: Heroic Venom Gnasher
  slug: heroic-venom-gnasher
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Gnasher Shotgun}.'
---
