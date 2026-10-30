---
title: Nomad
slug: nomad
category: Assault
role: Assault
description: 'The eye of the storm, the Nomad is a deadly mobile sniper class that uses Fear to create space for the team.

  '
traits:
- name: Bleeding
  note: '[[card:armored-shot]] Card unlocks at Level 14'
- name: Stim
  note: '[[card:lifeline]] Card unlocks at Level 12 + [[card:execution-shield]] Card unlocks at Level 13'
passive:
  name: Fear Amplifier
  description: Deal double damage to enemies under Fear.
active:
  name: Fear
  description: Put nearby enemies into a state of fear. Enemies under Fear cannot attack and will retreat. Does not affect bosses.
  duration: 7s
  cooldown: 200s
ultimate:
  name: Fear
  description: Put nearby enemies into a state of fear. Enemies under Fear cannot attack and will retreat. Does not affect bosses.
  duration: 7s
  cooldown: 200s
weapons:
- name: Markza Mk 1 Marksman Rifle
  slug: markza
- name: Gnasher Shotgun
  slug: gnasher
- name: Boltok Pistol
  slug: boltok
# right=N1, left=N2, down=Pistol, up=Grenade - confirmed from
# ref/Class Menus/Class Menu - Nomad.jpg: Markza on-screen left (N1),
# Gnasher on-screen right (N2), Boltok in the pistol slot, no grenade
# shown (X).
weapon_slots:
  right:
    name: Markza Mk 1 Marksman Rifle
    slug: markza
  left:
    name: Gnasher Shotgun
    slug: gnasher
  down:
    name: Boltok Pistol
    slug: boltok
perks:
  up:
    name: Health
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  right:
    name: Ammo Capacity
    values: ['10%', '20%', '30%', '40%', '50%', '60%', '70%', '80%', '90%', '100%']
  down:
    name: Precision Weapons Damage
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  left:
    name: Critical Damage
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
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
- name: Menace
  slug: menace
  rarity: Rare
  unlock_level: 2
  description: Executions recharge Fear for {X}.
  levels:
  - X: '25s'
  - X: '30s'
  - X: '35s'
  - X: '40s'
  - X: '45s'
  - X: '50s'
- name: Precision Resistance
  slug: precision-resistance
  rarity: Common
  unlock_level: 3
  description: '{X} damage resistance from precision rifles.'
  levels:
  - X: '20%'
  - X: '24%'
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Terror
  slug: terror
  rarity: Common
  unlock_level: 4
  description: Extend fear duration to {X}.
  levels:
  - X: '9s'
  - X: '11s'
  - X: '12s'
  - X: '13s'
  - X: '14s'
  - X: '15s'
- name: Rain Down
  slug: rain-down
  rarity: Rare
  unlock_level: 5
  description: '{X} extra damage when above the enemy.'
  levels:
  - X: '5%'
  - X: '10%'
  - X: '15%'
  - X: '20%'
  - X: '25%'
  - X: '30%'
- name: Fearsome Aura
  slug: fearsome-aura
  rarity: Common
  unlock_level: 6
  description: Increases radius of Fear ability by {X}.
  levels:
  - X: '1m'
  - X: '2m'
  - X: '3m'
  - X: '4m'
  - X: '5m'
  - X: '6m'
- name: Nomad Armor
  slug: nomad-armor
  rarity: Common
  unlock_level: 7
  description: '{X} damage resistance within 15m.'
  levels:
  - X: '20%'
  - X: '24%'
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Gnasher Proficiency
  slug: gnasher-proficiency
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
- name: Faze
  slug: faze
  rarity: Epic
  unlock_level: 8
  description: Executing causes Fear for {X} to nearby enemies.
  levels:
  - X: '7s'
  - X: '8s'
  - X: '9s'
  - X: '10s'
  - X: '11s'
  - X: '12s'
- name: Concussive Rounds
  slug: concussive-rounds
  rarity: Rare
  unlock_level: 9
  description: Boltok headshots on Drones stuns for {X}.
  levels:
  - X: '1.5s'
  - X: '2s'
  - X: '2.5s'
  - X: '3s'
  - X: '3.5s'
  - X: '4s'
- name: Acceleration
  slug: acceleration
  rarity: Rare
  unlock_level: 10
  description: '{X} extra damage at long range.'
  levels:
  - X: '5%'
  - X: '10%'
  - X: '15%'
  - X: '20%'
  - X: '25%'
  - X: '30%'
- name: Markza Mastery
  slug: markza-mastery
  rarity: Epic
  unlock_level: 11
  description: '{X} extra damage and {Y} active effects with the Markza.'
  levels:
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
  - X: '70%'
    Y: '35%'
- name: Powered Sprint
  slug: powered-sprint
  rarity: Epic
  unlock_level: 12
  description: Picking up energy heals for {X}.
  levels:
  - X: '30%'
  - X: '45%'
  - X: '60%'
  - X: '75%'
  - X: '90%'
  - X: '100%'
- name: Lifeline
  slug: lifeline
  rarity: Epic
  unlock_level: 12
  description: Anyone who kills an enemy in Fear heals and gains {X} Stim.
  levels:
  - X: '10%'
  - X: '15%'
  - X: '20%'
  - X: '25%'
  - X: '33%'
  - X: '50%'
- name: Execution Shield
  slug: execution-shield
  rarity: Epic
  unlock_level: 13
  description: 'Take {X} less damage while executing, and gain {Y} Stim after the kill.'
  levels:
  - X: '50%'
    Y: '40%'
  - X: '60%'
    Y: '55%'
  - X: '70%'
    Y: '65%'
  - X: '80%'
    Y: '80%'
  - X: '90%'
    Y: '90%'
  - X: '100%'
    Y: '100%'
- name: Armored Shot
  slug: armored-shot
  rarity: Legendary
  unlock_level: 14
  description: '{X} bleeding damage while you have stim.'
  levels:
  - X: '35%'
  - X: '40%'
  - X: '45%'
  - X: '50%'
  - X: '55%'
  - X: '60%'
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
- name: Consecutive Shot
  slug: consecutive-shot
  rarity: Epic
  unlock_level: 15
  description: Consecutive critical hits increase damage {X} each hit up to +200%.
  levels:
  - X: '5%'
  - X: '10%'
  - X: '15%'
  - X: '20%'
  - X: '25%'
  - X: '33%'
- name: Intimidation
  slug: intimidation
  rarity: Legendary
  unlock_level: 16
  description: '{X} of Fear to enemies within 5m of a critical kill.'
  levels:
  - X: '7s'
  - X: '8s'
  - X: '9s'
  - X: '10s'
  - X: '11s'
  - X: '12s'
- name: Heroic Venom Markza
  slug: heroic-venom-markza
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Markza Mk 1 Marksman Rifle}.'
---
