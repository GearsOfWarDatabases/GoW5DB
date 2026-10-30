---
title: Tactician
slug: tactician
category: Support
role: Support
description: 'The Tactician brings leadership to the team by marking targets and restocking ammo when needed.

  '
traits:
- name: Ammo Regeneration
  note: 'Built into $ultimate'
- name: Explosive Ammo Regeneration
  note: 'Explosive Resupply Perk (▼ Down Slot) + [[card:venom-explosive-resupply]] Card unlocks at Level 11'
- name: Bleeding
  note: '[[card:shredder]] Card unlocks at Level 12'
- name: Marking
  note: 'Leadership passive tracks a marked target + [[card:eagle-eyes]] Card unlocks at Level 3'
passive:
  name: Leadership
  description: Anyone who kills your marked target gains 5 seconds of Ultimate recharge.
active:
  name: Resupply
  description: Regenerates ammo for nearby allies.
  duration: 10s
  cooldown: 300s
ultimate:
  name: Resupply
  description: Regenerates ammo for nearby allies.
  duration: 10s
  cooldown: 300s
weapons:
- name: Hammerburst II
  slug: hammerburst
- name: Boomshot Grenade Launcher
  slug: boomshot
- name: Snub Pistol
  slug: snub-pistol
- name: Flashbang
  slug: flashbang
# right=N1, left=N2, down=Pistol, up=Grenade - confirmed from
# ref/Class Menus/Class Menu - Tactician.jpg: Hammerburst II on-screen
# left (N1), Boomshot on-screen right (N2), Snub Pistol in the pistol
# slot. NOTE: unlike every other 4-weapon class, the grenade slot in
# this screenshot shows the empty "X" placeholder, not Flashbang - left
# as N/A here to match what's actually visible; the flat weapons: list
# above still records Flashbang in case that's just this loadout being
# unequipped rather than the class lacking one.
weapon_slots:
  right:
    name: Hammerburst II
    slug: hammerburst
  left:
    name: Boomshot Grenade Launcher
    slug: boomshot
  down:
    name: Snub Pistol
    slug: snub-pistol
perks:
  up:
    name: Health
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  right:
    name: Ultimate Recharge on Kill
    description: Killing an enemy gives up to 15s Ultimate cooldown reduction.
    values: ['2s', '4s', '6s', '8s', '10s', '11s', '12s', '13s', '14s', '15s']
  down:
    name: Explosive Resupply
    values: ['N/A', '10%', '20%', '30%', '40%', '50%', '60%', '70%', '80%', '90%']
  left:
    name: Assault Rifle Damage
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
- name: Huddle Up
  slug: huddle-up
  rarity: Common
  unlock_level: 2
  description: Each additional teammate within the Resupply radius increases the Resupply rate by {X}.
  levels:
  - X: '5%'
  - X: '7%'
  - X: 10%
  - X: 13%
  - X: '15%'
  - X: '17%'
- name: Eagle Eyes
  slug: eagle-eyes
  rarity: Common
  unlock_level: 3
  description: Mark {X} additional targets.
  levels:
  - X: '2'
  - X: '3'
  - X: '4'
  - X: '5'
  - X: '6'
  - X: '7'
- name: Custom Snub
  slug: custom-snub
  rarity: Common
  unlock_level: 4
  description: Increased damage by {X} and active effects by {Y} when firing the Snub.
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
- name: Resupply Duration
  slug: resupply-duration
  rarity: Rare
  unlock_level: 5
  description: Resupply duration increased by {X}.
  levels:
  - X: '10%'
  - X: '20%'
  - X: 30%
  - X: 40%
  - X: '50%'
  - X: '60%'
- name: Modified Hammerburst
  slug: modified-hammerburst
  rarity: Common
  unlock_level: 6
  description: Increased damage by {X} and active effects by {Y} when firing the Hammerburst.
  levels:
  - X: 10%
    Y: 5%
  - X: 20%
    Y: 10%
  - X: '30%'
    Y: '15%'
  - X: '40%'
    Y: '20%'
  - X: '50%'
    Y: '25%'
  - X: '60%'
    Y: '30%'
- name: Grenade Pouch
  slug: grenade-pouch
  rarity: Common
  unlock_level: 7
  description: Carry {X} more grenades in your inventory.
  levels:
  - X: '1'
  - X: '2'
  - X: '3'
  - X: '4'
  - X: '5'
  - X: '6'
- name: Situational Awareness
  slug: situational-awareness
  rarity: Common
  unlock_level: 8
  description: Aggressive enemies are automatically marked for {X}.
  levels:
  - X: '2s'
  - X: 4s
  - X: 6s
  - X: '8s'
  - X: '10s'
  - X: '12s'
- name: Resupply Speed Loader
  slug: resupply-speed-loader
  rarity: Rare
  unlock_level: 9
  description: '{X} larger active reload window during resupply.'
  levels:
  - X: '10%'
  - X: '20%'
  - X: 30%
  - X: 40%
  - X: 'Auto Reload'
  - X: 'Auto Active Reload'
- name: Resupply Amplifier
  slug: resupply-amplifier
  rarity: Epic
  unlock_level: 10
  description: Resupply radius is increased by {X}.
  levels:
  - X: '50%'
  - X: '80%'
  - X: 90%
  - X: 100%
  - X: '125%'
  - X: '150%'
- name: Battle Hardened
  slug: battle-hardened
  rarity: Rare
  unlock_level: 11
  description: '{X} resistance to explosive damage.'
  levels:
  - X: '20%'
  - X: 24%
  - X: 26%
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Venom Explosive Resupply
  slug: venom-explosive-resupply
  rarity: Rare
  unlock_level: 11
  description: Resupply recharges ammo for explosive weapons while in the Venom cloud or ash, and does it {X} faster.
  levels:
  - X: '100%'
  - X: 10%
  - X: 20%
  - X: '130%'
  - X: '140%'
  - X: '150%'
- name: Shredder
  slug: shredder
  unlock_level: 12
  description: Explosive damage to enemies causes them to bleed for {X} of damage dealt.
  levels:
  - X: 15%
  - X: 18%
  - X: '21%'
  - X: '24%'
  - X: '27%'
  - X: '30%'
  rarity: Epic
- name: Recharge Bounty
  slug: recharge-bounty
  rarity: Rare
  unlock_level: 13
  description: '{X} of additional Ultimate cooldown for anyone who kills your marked target.'
  levels:
  - X: '10s'
  - X: 13s
  - X: 16s
  - X: '19s'
  - X: '22s'
  - X: '25s'
- name: Interrogation
  slug: interrogation
  unlock_level: 13
  description: Taking a meatshield marks all enemies within {X}.
  levels:
  - X: 20 meters
  - X: 30 meters for 12 seconds
  - X: '35m'
  - X: '40m'
  - X: '45m'
  - X: '50m'
  rarity: Epic
- name: Venom Boost
  slug: venom-boost
  rarity: Epic
  unlock_level: 14
  description: Each kill while in the Venom cloud or ash reduces Resupply cooldown by {X}.
  levels:
  - X: '20s'
  - X: 23s
  - X: 26s
  - X: '29s'
  - X: '32s'
  - X: '35s'
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
- name: Resupply Healing Module
  slug: resupply-healing-module
  unlock_level: 16
  description: Resupply instantly heals friendlies {X} faster and reduces damage by {Y}.
  levels:
  - X: 50%
    Y: 20%
  - X: 100%
    Y: 30%
  - X: 150%
    Y: 40%
  - X: '175%'
    Y: '50%'
  - X: '200%'
    Y: '60%'
  - X: '225%'
    Y: '63%'
  rarity: Legendary
- name: Disciplined
  slug: disciplined
  rarity: Epic
  unlock_level: 18
  description: Consecutive hits with ballistic weapons increases damage {X} up to 100%.
  levels:
  - X: 1%
  - X: '2%'
  - X: '3%'
  - X: '4%'
  - X: '5%'
  - X: '6%'
- name: Cooperation
  slug: cooperation
  rarity: Legendary
  unlock_level: 19
  description: Your teammates deal {X} extra damage to your marked target.
  levels:
  - X: 5%
  - X: '10%'
  - X: '15%'
  - X: '20%'
  - X: '25%'
  - X: '30%'
- name: Heroic Venom Boomshot
  slug: heroic-venom-boomshot
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Boomshot Grenade Launcher}.'
---
