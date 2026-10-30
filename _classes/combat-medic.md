---
title: Combat Medic
slug: combat-medic
category: Support
role: Support
description: 'The Combat Medic is a solid rifle class that you can depend on to bring the team back from the brink.

  '
traits:
- name: Stim
  note: '[[card:helpful-headshots]] Card unlocks at Level 9 + [[card:get-up]] Card unlocks at Level 16'
passive:
  name: Field Medic
  description: +50% health regeneration speed for you and your allies within 10 meters. Deal +30% rifle damage.
active:
  name: Team Revive
  description: Instantly revive all downed allies.
  duration: N/A
  cooldown: 250s
ultimate:
  name: Team Revive
  description: Instantly revive all downed allies.
  duration: N/A
  cooldown: 250s
weapons:
- name: Lancer
  slug: lancer
- name: Gnasher Shotgun
  slug: gnasher
- name: Snub Pistol
  slug: snub-pistol
# right=N1, left=N2, down=Pistol, up=Grenade - confirmed from
# ref/Class Menus/Class Menu - Combat Medic.jpg: Lancer on-screen left
# (N1), Gnasher on-screen right (N2), Snub Pistol in the pistol slot, no
# grenade shown.
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
perks:
  up:
    name: Health
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  right:
    name: Critical Damage
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  down:
    name: Assault Rifle Damage
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  left:
    name: Ultimate Cooldown
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
- name: Healing Bounty
  slug: healing-bounty
  rarity: Common
  unlock_level: 2
  description: Anyone who kills your mark heals {X}.
  levels:
  - X: '800 HP'
  - X: "1,000 HP"
  - X: "1,200 HP"
  - X: "1,300 HP"
  - X: "1,400 HP"
  - X: "1,500 HP"
- name: Razor's Edge
  slug: razors-edge
  rarity: Common
  unlock_level: 3
  description: '{X} damage resistance when under 50% health.'
  levels:
  - X: '20%'
  - X: '24%'
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Perfect Condition
  slug: perfect-condition
  rarity: Common
  unlock_level: 4
  description: '{X} damage resistance when over 50% health.'
  levels:
  - X: '20%'
  - X: '24%'
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Suppressive Recharge
  slug: suppressive-recharge
  rarity: Rare
  unlock_level: 5
  description: Grenade kills recharge Team Revive by {X}.
  levels:
  - X: '90s'
  - X: '120s'
  - X: '140s'
  - X: '160s'
  - X: '170s'
  - X: '180s'
- name: Custom Lancer
  slug: custom-lancer
  rarity: Common
  unlock_level: 6
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
- name: Modified Snub
  slug: modified-snub
  rarity: Common
  unlock_level: 7
  description: '{X} increased damage and {Y} active effects when firing the Snub.'
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
- name: Dodge
  slug: dodge
  rarity: Rare
  unlock_level: 8
  description: '{X} ballistic damage resistance beyond 5m.'
  levels:
  - X: '20%'
  - X: '24%'
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Helpful Headshots
  slug: helpful-headshots
  rarity: Rare
  unlock_level: 9
  description: Headshot hits provide {X} Stim to self and nearby allies.
  levels:
  - X: '5 HP'
  - X: '10 HP'
  - X: '15 HP'
  - X: '20 HP'
  - X: '25 HP'
  - X: '30HP'
- name: Overdoing It
  slug: overdoing-it
  rarity: Epic
  unlock_level: 10
  description: Team Revive heals revived friendlies for {X}.
  levels:
  - X: '20%'
  - X: '24%'
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Grenade Pouch
  slug: grenade-pouch
  rarity: Common
  unlock_level: 11
  description: Grenade capacity increased by {X}.
  levels:
  - X: '1'
  - X: '2'
  - X: '3'
  - X: '4'
  - X: '5'
  - X: '6'
- name: Team Repair
  slug: team-repair
  rarity: Rare
  unlock_level: 12
  art_fit: contain
  description: Team Revive repairs fortifications by {X}.
  levels:
  - X: '20%'
  - X: '30%'
  - X: '35%'
  - X: '40%'
  - X: '45%'
  - X: '50%'
- name: Intervention
  slug: intervention
  rarity: Legendary
  unlock_level: 13
  description: Kills revive teammates within {X} of the kill.
  levels:
  - X: '10m'
  - X: '12m'
  - X: '14m'
  - X: '16m'
  - X: '18m'
  - X: '20m'
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
- name: Get Up
  slug: get-up
  rarity: Legendary
  unlock_level: 16
  description: Team Revive gives you and teammate {X} Stim.
  levels:
  - X: '30%'
  - X: '40%'
  - X: '50%'
  - X: '60%'
  - X: '70%'
  - X: '80%'
- name: Heroic Venom Lancer
  slug: heroic-venom-lancer
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Lancer}.'
---
