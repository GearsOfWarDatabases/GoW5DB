---
title: Brawler
slug: brawler
category: Tank
role: Tank
description: 'A force of nature, the Brawler brings their own powerful melee moves to the table and uses fire to decimate enemies.

  '
traits:
- name: Ammo Regeneration
  note: 'Ammo Regeneration Perk (◄ Left Slot)'
- name: Melee
  note: 'Built into $passive'
- name: Stim
  note: 'Built into $passive + [[card:defensive-tackle]] Card unlocks at Level 9'
passive:
  name: Brawler Melee
  description: Can punch to stun enemies and melee while roadie running to tackle. Killing enemies using the tackle gives Stim.
active:
  name: The Train
  description: Leave a trail of fire while moving. Staggers and ignites nearby enemies.
  duration: 7s
  cooldown: 240s
ultimate:
  name: The Train
  description: Leave a trail of fire while moving. Stagger and ignite nearby enemies.
  duration: 7s
  cooldown: 240s
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
# ref/Class Menus/Class Menu - Brawler.jpg: Lancer on-screen left (N1),
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
perks:
  up:
    name: Health
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  right:
    name: Feedback Boost
    description: Damage dealt is converted to Ultimate Cooldown reduction.
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  down:
    name: Damage
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  left:
    name: Ammo Regeneration
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
- name: Haymaker
  slug: haymaker
  rarity: Common
  unlock_level: 2
  description: '{X} damage on melee hits and drones are stunned for longer.'
  levels:
  - X: 150%
  - X: 160%
  - X: 170%
  - X: '185%'
  - X: '200%'
  - X: '215%'
- name: Glow and Slow
  slug: glow-and-slow
  rarity: Common
  unlock_level: 3
  description: '{X} speed reduction on burning enemies.'
  levels:
  - X: '25%'
  - X: '30%'
  - X: '35%'
  - X: '40%'
  - X: '50%'
  - X: '60%'
- name: Damage Dash
  slug: damage-dash
  rarity: Common
  unlock_level: 4
  description: '{X} damage resistance while sprinting.'
  levels:
  - X: 15%
  - X: 20%
  - X: 25%
  - X: '30%'
  - X: '35%'
  - X: '40%'
- name: Play With Fire
  slug: play-with-fire
  rarity: Rare
  unlock_level: 5
  description: '{X} burn chance on active rounds.'
  levels:
  - X: 5%
  - X: 10%
  - X: 15%
  - X: '20%'
  - X: '25%'
  - X: '30%'
- name: Thrashball Pro
  slug: thrashball-pro
  rarity: Common
  unlock_level: 6
  description: '{X} less damage from melee attacks.'
  levels:
  - X: 10%
  - X: 20%
  - X: 30%
  - X: '40%'
  - X: '50%'
  - X: '60%'
- name: Torch Tackle
  slug: torch-tackle
  rarity: Rare
  unlock_level: 7
  description: Tackle burns and deals {X} damage to burning enemies.
  levels:
  - X: 150%
  - X: 175%
  - X: 200%
  - X: '225%'
  - X: '250%'
  - X: '275%'
- name: Steam Engine
  slug: steam-engine
  rarity: Common
  unlock_level: 8
  description: '{X} burn radius during ultimate.'
  levels:
  - X: '50%'
  - X: '60%'
  - X: '70%'
  - X: '85%'
  - X: '100%'
  - X: '115%'
- name: Pyromaniac
  slug: pyromaniac
  rarity: Rare
  unlock_level: 9
  description: Deal {X} extra burn damage.
  levels:
  - X: 25%
  - X: 40%
  - X: 60%
  - X: 80%
  - X: '90%'
  - X: '100%'
- name: Defensive Tackle
  slug: defensive-tackle
  rarity: Common
  unlock_level: 9
  description: +{X} Stim on tackle kill.
  levels:
  - X: 10%
  - X: 20%
  - X: 30%
  - X: '40%'
  - X: '50%'
  - X: '60%'
- name: Burn Boost
  slug: burn-boost
  rarity: Epic
  unlock_level: 10
  description: Active reload with {X} extra damage on melee kill of a burning enemy.
  levels:
  - X: 10%
  - X: '20%'
  - X: '30%'
  - X: '40%'
  - X: '50%'
  - X: '60%'
- name: Perk Up
  slug: perk-up
  rarity: Rare
  unlock_level: 11
  description: '{X} increased max health and regeneration speed.'
  levels:
  - X: '20%'
  - X: '25%'
  - X: '30%'
  - X: '40%'
  - X: '50%'
  - X: '60%'
- name: Burn and Recharge
  slug: burn-and-recharge
  rarity: Epic
  unlock_level: 12
  description: '{X} faster recharge on The Train for each burning enemy.'
  levels:
  - X: 2.5%
  - X: 3%
  - X: '4.5%'
  - X: '5%'
  - X: '6%'
  - X: '7%'
- name: Inner Fire
  slug: inner-fire
  rarity: Rare
  unlock_level: 13
  description: '{X} resistance to damage when The Train is available.'
  levels:
  - X: '10%'
  - X: '15%'
  - X: '20%'
  - X: '25%'
  - X: '30%'
  - X: '35%'
- name: Epic Score Boost
  slug: epic-score-boost
  rarity: Epic
  unlock_level: 13
  description: '{X} increased team score in Horde and {X} time bonus in Escape.'
  levels:
  - X: 10%
  - X: 15%
  - X: 20%
  - X: 25%
  - X: 30%
  - X: '35%'
- name: Killing Time
  slug: killing-time
  rarity: Epic
  unlock_level: 14
  description: Extend The Train by {X} per kill during ultimate.
  levels:
  - X: 1s
  - X: '1.25s'
  - X: '1.5s'
  - X: '1.75s'
  - X: '2s'
  - X: '2.25s'
- name: All the Glory
  slug: all-the-glory
  rarity: Legendary
  unlock_level: 15
  art_fit: contain
  description: Burning enemies explode on kill, dealing {X} HP in damage.
  levels:
  - X: 5%
  - X: '10%'
  - X: '15%'
  - X: '20%'
  - X: '25%'
  - X: '30%'
- name: Soothing Warmth
  slug: soothing-warmth
  rarity: Legendary
  unlock_level: 16
  description: '{X} health regeneration near burning enemies.'
  levels:
  - X: '150%'
  - X: '175%'
  - X: '200%'
  - X: '225%'
  - X: '250%'
  - X: '275%'
- name: Fuel Tanks
  slug: fuel-tanks
  rarity: Rare
  unlock_level: 18
  description: Carry {X} extra Scorcher ammo.
  levels:
  - X: '20%'
  - X: '40%'
  - X: '60%'
  - X: '80%'
  - X: '100%'
  - X: '120%'
- name: Scorcher Mastery
  slug: scorcher-mastery
  rarity: Rare
  unlock_level: 19
  description: '{X} extra Scorcher damage.'
  levels:
  - X: '20%'
  - X: '30%'
  - X: '40%'
  - X: '50%'
  - X: '60%'
  - X: '70%'
- name: Heroic Venom Scorcher
  slug: heroic-venom-scorcher
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Scorcher}.'
---
