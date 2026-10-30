---
title: Veteran
slug: veteran
category: Tank
role: Tank
description: 'A one man army, the Veteran is a powerful rifle class focused on the fundamentals of cover based combat.

  '
traits:
- name: Stim
  note: '[[card:band-of-brothers]] Card unlocks at Level 16'
passive:
  name: Execution Defense
  description: Take no damage during executions.
active:
  name: Living Legend
  description: Automatically fire at the heads of enemies in sight. Any allies in cover with you will do the same.
  duration: 20s
  cooldown: 300s
ultimate:
  name: Living Legend
  description: Automatically fire at the heads of enemies in sight. Any allies in cover with you will do the same.
  duration: 20s
  cooldown: 300s
weapons:
- name: Lancer
  slug: lancer
- name: Gnasher Shotgun
  slug: gnasher
- name: Snub Pistol
  slug: snub-pistol
- name: Smoke Grenade
  slug: smoke-grenade
# right=N1, left=N2, down=Pistol, up=Grenade - confirmed from
# ref/Class Menus/Class Menu - Veteran.jpg: Lancer on-screen left (N1),
# Gnasher on-screen right (N2), Snub Pistol in the pistol slot, Smoke
# Grenade in the grenade slot.
weapon_slots:
  right:
    name: Lancer
    slug: lancer
  left:
    name: Gnasher Shotgun
    slug: gnasher
  down:
    name: Snub Pistol
    slug: snub-pistol
  up:
    name: Smoke Grenade
    slug: smoke-grenade
# Perks verified in-game (ref/Class Perks/Veteran - Perks - 01
# through 09): Health +10%@2, +15%@3, +20%@4; Critical Damage +35%@7, +45%@9,
# +50%@10 (MAX); Assault Rifles +25%@5 through +45%@9; Ultimate Cooldown
# +50%@MAX. All four track the same flat 5%/rank curve. (The previous set -
# Feedback Boost in the right slot, Ammo Regeneration in the left slot with
# 10%-100% values - was wrong; those screenshots show Critical Damage on the
# right and Ultimate Cooldown on the left instead.)
perks:
  up:
    name: Health
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  right:
    name: Critical Damage
    description: '+{value} Damage'
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  down:
    name: Assault Rifle Damage
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  left:
    name: Ultimate Cooldown
    description: '+{value} Cooldown Speed'
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
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
- name: Dug In
  slug: dug-in
  rarity: Common
  unlock_level: 2
  description: '{X} less damage in cover.'
  levels:
  - X: '20%'
  - X: '30%'
  - X: '40%'
  - X: '50%'
  - X: '55%'
  - X: '60%'
- name: Extended Rifle Mag
  slug: extended-rifle-mag
  rarity: Common
  unlock_level: 3
  description: '{X} larger assault rifle magazine.'
  levels:
  - X: '40%'
  - X: '55%'
  - X: '70%'
  - X: '85%'
  - X: '100%'
  - X: '115%'
- name: Explosive Resistance
  slug: explosive-resistance
  rarity: Common
  unlock_level: 4
  description: '{X} damage resistance from explosives.'
  levels:
  - X: '20%'
  - X: '24%'
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Brutal Efficiency
  slug: brutal-efficiency
  rarity: Rare
  unlock_level: 5
  description: Executions recharge Living Legend by {X}.
  levels:
  - X: '15s'
  - X: '20s'
  - X: 25s
  - X: 30s
  - X: 35s
  - X: '40s'
- name: Friendlier Fire
  slug: friendlier-fire
  rarity: Common
  unlock_level: 6
  description: '{X} larger Living Legend radius.'
  levels:
  - X: '10%'
  - X: '20%'
  - X: '30%'
  - X: '40%'
  - X: '50%'
  - X: '60%'
- name: Last Ditch
  slug: last-ditch
  rarity: Rare
  unlock_level: 7
  description: '{X} increased damage when at low health.'
  levels:
  - X: '25%'
  - X: '45%'
  - X: '65%'
  - X: 75%
  - X: 85%
  - X: '90%'
- name: Lancer Stock
  slug: lancer-stock
  rarity: Common
  unlock_level: 8
  description: '{X} reduced Lancer recoil.'
  levels:
  - X: '50%'
  - X: '55%'
  - X: '60%'
  - X: '65%'
  - X: '70%'
  - X: '75%'
- name: Custom Lancer
  slug: custom-lancer
  rarity: Rare
  unlock_level: 9
  description: '{X} increased damage and {Y} active effects when firing any type of Lancer.'
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
- name: Focus
  slug: focus
  rarity: Epic
  unlock_level: 10
  description: Ultimate duration increased by {X}.
  levels:
  - X: '25%'
  - X: '40%'
  - X: '55%'
  - X: '70%'
  - X: '85%'
  - X: '100%'
- name: Flank 'Em
  slug: flank-em
  rarity: Epic
  unlock_level: 11
  description: '{X} extra damage when flanking.'
  levels:
  - X: '50%'
  - X: 70%
  - X: 85%
  - X: 95%
  - X: '105%'
  - X: '115%'
- name: Defensive Stim
  slug: defensive-stim
  rarity: Epic
  unlock_level: 12
  description: Stim Capacity is increased {X}.
  levels:
  - X: '40%'
  - X: 60%
  - X: 80%
  - X: '90%'
  - X: '100%'
  - X: '110%'
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
- name: Headshot Master
  slug: headshot-master
  rarity: Epic
  unlock_level: 15
  description: '{X} extra critical damage.'
  levels:
  - X: 10%
  - X: 20%
  - X: '30%'
  - X: '40%'
  - X: '50%'
  - X: '60%'
- name: Band of Brothers
  slug: band-of-brothers
  rarity: Legendary
  unlock_level: 16
  description: Living Legend generates {X} Stim per second.
  levels:
  - X: '25'
  - X: '50'
  - X: 75
  - X: 100
  - X: 125
  - X: '150'
- name: Heroic Venom Retro Lancer
  slug: heroic-venom-retro-lancer
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Retro Lancer}.'
---
