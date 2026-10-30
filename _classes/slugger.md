---
title: Slugger
slug: slugger
category: Promotional
role: Promotional
description: 'The Slugger is a powerful shotgun specialist focused on crowd control and stopping power.

  '
passive:
  name: Explosive Resistance
  description: Resist 50% explosive damage.
active:
  name: Heavy Hitter
  description: All hits with ballistic weapons will knockback enemies and deal +50% damage.
  duration: 20s
  cooldown: 200s
ultimate:
  name: Heavy Hitter
  description: All hits with ballistic weapons will knockback enemies and deal +50% damage.
  duration: 20s
  cooldown: 200s
weapons:
- name: Lancer
  slug: lancer
- name: Gnasher Shotgun
  slug: gnasher
- name: Boltok Pistol
  slug: boltok
- name: Flashbang
  slug: flashbang
# right=N1, left=N2, down=Pistol, up=Grenade - confirmed from
# ref/Class Menus/Class Menu - Slugger.jpg: Lancer on-screen left (N1),
# Gnasher on-screen right (N2), Boltok in the pistol slot, Flashbang in
# the grenade slot.
weapon_slots:
  right:
    name: Lancer
    slug: lancer
  left:
    name: Gnasher Shotgun
    slug: gnasher
  down:
    name: Boltok Pistol
    slug: boltok
  up:
    name: Flashbang
    slug: flashbang
perks:
  up:
    name: Health
  right:
    name: Movement Speed
  down:
    name: Shotgun Damage
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  left:
    name: Feedback Boost
    description: Damage dealt is converted to Ultimate Cooldown reduction.
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
- name: Grenade Capacity
  slug: grenade-capacity
  rarity: Common
  unlock_level: 2
  description: Grenade capacity increased by {X}.
  levels:
  - X: '1'
  - X: '2'
  - X: '3'
  - X: '4'
  - X: '5'
  - X: '6'
- name: Power Shot
  slug: power-shot
  rarity: Rare
  unlock_level: 4
  description: Ballistic rounds penetrate targets and deal +{X} damage.
  levels:
  - X: 10%
  - X: '20%'
  - X: '30%'
  - X: '40%'
  - X: '50%'
  - X: '60%'
- name: Tough Skin
  slug: tough-skin
  rarity: Common
  unlock_level: 6
  description: '{X} ballistic damage resistance within 15m.'
  levels:
  - X: 20%
  - X: '24%'
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Grenade Proficiency
  slug: grenade-proficiency
  rarity: Epic
  unlock_level: 8
  description: '+{X} damage and +{Y} explosive radius with grenades.'
  levels:
  - X: '50%'
    Y: '25%'
  - X: '50%'
    Y: '30%'
  - X: '50%'
    Y: '35%'
  - X: '140%'
    Y: '40%'
  - X: '170%'
    Y: '45%'
  - X: '200%'
    Y: '50%'
- name: Lethal Preparations
  slug: lethal-preparations
  rarity: Rare
  unlock_level: 9
  description: Plant {X} extra grenade trap.
  levels:
  - X: '1'
  - X: '2'
  - X: '3'
  - X: '4'
  - X: '5'
  - X: '6'
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
- name: Impact Receiver
  slug: impact-receiver
  rarity: Legendary
  unlock_level: 16
  description: Active shotgun hits within 10m stun drones for {X}.
  levels:
  - X: 1s
  - X: '1.4s'
  - X: '1.8s'
  - X: '2.2s'
  - X: '2.6s'
  - X: '3.0s'
- name: Heroic Venom Overkill
  slug: heroic-venom-overkill
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Overkill}.'
---
