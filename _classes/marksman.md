---
title: Marksman
slug: marksman
category: Assault
role: Assault
description: 'A master of the headshot, the Marksman picks off targets with surgical precision.

  '
traits:
- name: Freeze
  note: '[[card:icy-precision]] Card unlocks at Level 16'
passive:
  name: Penetrating Shots
  description: Precision shots penetrate through targets.
active:
  name: X-Ray
  description: See and shoot enemies through walls with ballistic weapons while active.
  duration: 15s
  cooldown: 400s
ultimate:
  name: X-Ray
  description: See and shoot enemies through walls with ballistic weapons while active.
  duration: 15s
  cooldown: 400s
weapons:
- name: Markza Mk 1 Marksman Rifle
  slug: markza
- name: Longshot Sniper Rifle
  slug: longshot
- name: Boltok Pistol
  slug: boltok
# right=N1, left=N2, down=Pistol, up=Grenade - confirmed from
# ref/Class Menus/Class Menu - Marksman.jpg: Markza on-screen left (N1),
# Longshot on-screen right (N2), Boltok in the pistol slot, no grenade
# shown.
weapon_slots:
  right:
    name: Markza Mk 1 Marksman Rifle
    slug: markza
  left:
    name: Longshot Sniper Rifle
    slug: longshot
  down:
    name: Boltok Pistol
    slug: boltok
perks:
  up:
    name: Critical Damage
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  right:
    name: Feedback Boost
    description: Damage dealt is converted to Ultimate Cooldown reduction.
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  down:
    name: Precision Weapons Damage
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  left:
    name: Ammo Capacity
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
- name: Ambush
  slug: ambush
  rarity: Common
  unlock_level: 2
  description: +{X} critical damage to targets above 90% health.
  levels:
  - X: '20%'
  - X: '40%'
  - X: '60%'
  - X: '80%'
  - X: '90%'
  - X: '100%'
- name: Counter Snipe
  slug: counter-snipe
  rarity: Common
  unlock_level: 3
  description: '{X} resistance to precision damage.'
  levels:
  - X: '20%'
  - X: '24%'
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Steady Hand
  slug: steady-hand
  rarity: Common
  unlock_level: 4
  description: '{X} reduced camera shake and stun.'
  levels:
  - X: '40%'
  - X: '50%'
  - X: '60%'
  - X: '65%'
  - X: '70%'
  - X: '75%'
- name: Exploit Weakness
  slug: exploit-weakness
  rarity: Rare
  unlock_level: 5
  description: '{X} increased critical damage.'
  levels:
  - X: '20%'
  - X: '30%'
  - X: '40%'
  - X: '45%'
  - X: '50%'
  - X: '55%'
- name: Master Marksman
  slug: master-marksman
  rarity: Common
  unlock_level: 6
  description: '{X} larger active reload bar.'
  levels:
  - X: '50%'
  - X: '100%'
  - X: '150%'
  - X: '175%'
  - X: '200%'
  - X: '220%'
- name: Modified Longshot
  slug: modified-longshot
  rarity: Rare
  unlock_level: 7
  description: '{X} increased damage and active effects.'
  levels:
  - X: '5%'
  - X: '10%'
  - X: '15%'
  - X: '20%'
  - X: '25%'
  - X: '30%'
- name: EMBAR Ammo Capacity
  slug: embar-ammo-capacity
  rarity: Common
  unlock_level: 8
  description: '{X} increased EMBAR ammo capacity.'
  levels:
  - X: '10%'
  - X: '15%'
  - X: '20%'
  - X: '25%'
  - X: '30%'
  - X: '35%'
- name: Patience
  slug: patience
  rarity: Rare
  unlock_level: 9
  description: X-Ray recharges {X} faster while safe.
  levels:
  - X: '100%'
  - X: '130%'
  - X: '160%'
  - X: '190%'
  - X: '200%'
  - X: '210%'
- name: Critical Parade
  slug: critical-parade
  rarity: Epic
  unlock_level: 10
  art_fit: contain
  description: Critical kills during X-Ray extend its duration by {X}.
  levels:
  - X: '10%'
  - X: 14%
  - X: 18%
  - X: '19%'
  - X: '22%'
  - X: '25%'
- name: Modified EMBAR
  slug: modified-embar
  rarity: Rare
  unlock_level: 11
  description: Increases damage and active effects by {X} when firing the EMBAR.
  levels:
  - X: '5%'
  - X: 10%
  - X: '15%'
  - X: '20%'
  - X: '25%'
  - X: '30%'
- name: Longshot Handling
  slug: longshot-handling
  rarity: Epic
  unlock_level: 12
  description: '{X} automatic reload chance on critical kills.'
  levels:
  - X: '50%'
  - X: '60%'
  - X: '70%'
  - X: '80%'
  - X: '90%'
  - X: '100%'
- name: Explosive Critical Hit
  slug: explosive-critical-hit
  rarity: Rare
  unlock_level: 13
  description: Critical kills cause {X} splash damage.
  levels:
  - X: '50%'
  - X: '60%'
  - X: '70%'
  - X: '75%'
  - X: '80%'
  - X: '85%'
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
- name: Icy Precision
  slug: icy-precision
  rarity: Legendary
  unlock_level: 16
  description: '{X} freezing damage per active headshot with precision weapons.'
  levels:
  - X: '13%'
  - X: '15%'
  - X: '17%'
  - X: '20%'
  - X: '25%'
  - X: '34%'
- name: Heroic Venom Longshot
  slug: heroic-venom-longshot
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Longshot Sniper Rifle}.'
---
