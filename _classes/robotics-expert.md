---
title: Robotics Expert
slug: robotics-expert
category: Support
role: Support
engineer: true
description: 'The Robotics Expert is a master of machines, capable of building defenses that are extremely difficult to break.

  '
traits:
- name: Repairing
  note: 'Built into [[weapon:repair-tool]]'
- name: Bleeding
  note: '[[card:bloody-support]] Card unlocks at Level 10 + [[card:bloody-dr-1]] Card unlocks at Level 16'
- name: Summon
  note: 'Built into $ultimate'
passive:
  name: Builder
  description: Build new fortifications at a 15% discount, and carry fortifications faster.
active:
  name: Reinforce DR1
  description: Summons a DR-1 that targets enemies. This DR-1 is always armed with a Tri-Shot and will prioritize any enemy marked by the player.
  duration: 40s
  cooldown: 300s
ultimate:
  name: Reinforce DR1
  description: Summons a DR-1 that targets enemies. This DR-1 is always armed with a Tri-Shot and will prioritize any enemy marked by the player.
  duration: 40s
  cooldown: 300s
weapons:
- name: EMBAR Railgun
  slug: embar
- name: Overkill Shotgun
  slug: overkill
- name: Repair Tool
  slug: repair-tool
# right=N1, left=N2, down=Pistol, up=Grenade - confirmed from
# ref/Class Menus/Class Menu - Robotics Expert.jpg: EMBAR on-screen left
# (N1), Overkill on-screen right (N2), Repair Tool in the pistol slot,
# no grenade shown (X).
weapon_slots:
  right:
    name: EMBAR Railgun
    slug: embar
  left:
    name: Overkill Shotgun
    slug: overkill
  down:
    name: Repair Tool
    slug: repair-tool
perks:
  up:
    name: Critical Damage
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  right:
    name: Fortification Health
    values: ['10%', '20%', '30%', '40%', '50%', '60%', '70%', '80%', '90%', '100%']
  down:
    name: Repair Cost Reduction
    values: ['5%', '9%', '13%', '17%', '20%', '22%', '24%', '26%', '28%', '30%']
  left:
    name: Fortification Damage
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
- name: Enforcer Porting
  slug: enforcer-porting
  rarity: Common
  unlock_level: 2
  description: '{X} reduced recoil on the Enforcer.'
  levels:
  - X: '20%'
  - X: 40%
  - X: 60%
  - X: '80%'
  - X: '90%'
  - X: '95%'
- name: Inspired Sniping
  slug: inspired-sniping
  rarity: Common
  unlock_level: 3
  description: Sniper hits reduce ultimate cooldown in multiples of {X}.
  levels:
  - X: '0.7s'
  - X: 0.9s
  - X: 1.2s
  - X: 1.4s
  - X: 1.5s
  - X: 1.6s
- name: Combat Engineer
  slug: combat-engineer
  rarity: Common
  unlock_level: 4
  description: Repair {X} faster for long repairs.
  levels:
  - X: '100%'
  - X: 200%
  - X: 250%
  - X: 270%
  - X: 300%
  - X: '330%'
- name: Explosive Killshot
  slug: explosive-killshot
  rarity: Rare
  unlock_level: 5
  description: Killing DBNO enemies deals {X} damage to surrounding enemies.
  levels:
  - X: '20%'
  - X: 30%
  - X: 40%
  - X: 45%
  - X: '50%'
  - X: '55%'
- name: Global Sentry Upgrade
  slug: global-sentry-upgrade
  rarity: Common
  unlock_level: 6
  description: All MG Sentries do {X} more damage.
  levels:
  - X: '10%'
  - X: 15%
  - X: 20%
  - X: 25%
  - X: '30%'
  - X: '35%'
- name: Melee Resistance
  slug: melee-resistance
  rarity: Rare
  unlock_level: 7
  description: '{X} melee damage resistance.'
  levels:
  - X: '20%'
  - X: 24%
  - X: 26%
  - X: 28%
  - X: '30%'
  - X: '32%'
- name: Heavy Resistance
  slug: heavy-resistance
  rarity: Common
  unlock_level: 8
  description: '{X} damage resistance to heavy weapon damage.'
  levels:
  - X: '20%'
  - X: 24%
  - X: 26%
  - X: 28%
  - X: '30%'
  - X: '32%'
- name: Nerves of Steel
  slug: nerves-of-steel
  rarity: Rare
  unlock_level: 9
  description: Repair {X} faster when enemies are nearby.
  levels:
  - X: '50%'
  - X: 100%
  - X: 150%
  - X: 180%
  - X: 200%
  - X: '220%'
- name: Bloody Support
  slug: bloody-support
  rarity: Epic
  unlock_level: 10
  description: Precision damage causes {X} bleed damage when Reinforce DR-1 is ready.
  levels:
  - X: '10%'
  - X: 15%
  - X: 20%
  - X: 25%
  - X: 30%
  - X: '35%'
- name: Precision Repairs
  slug: precision-repairs
  rarity: Rare
  unlock_level: 11
  description: Precision kills heal all fortifications for {X}.
  levels:
  - X: 700HP
  - X: "1,000HP"
  - X: "1,200HP"
  - X: "1,400HP"
  - X: "1,500HP"
  - X: "1,600HP"
- name: Experimental Weapons
  slug: experimental-weapons
  rarity: Epic
  unlock_level: 12
  description: '{X} increased DeeBee weapon damage to heavily wounded enemies.'
  levels:
  - X: 50%
  - X: 60%
  - X: 70%
  - X: 80%
  - X: '90%'
  - X: '100%'
- name: Parting Gift
  slug: parting-gift
  rarity: Rare
  unlock_level: 13
  description: '{X} increased damage with Grenade tags.'
  levels:
  - X: 20%
  - X: 40%
  - X: 60%
  - X: 80%
  - X: 90%
  - X: '100%'
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
- name: Global Overclock
  slug: global-overclock
  rarity: Epic
  unlock_level: 15
  description: All weapon lockers reload {X} faster.
  levels:
  - X: 20%
  - X: 30%
  - X: 40%
  - X: 45%
  - X: '50%'
  - X: '55%'
- name: Bloody DR-1
  slug: bloody-dr-1
  rarity: Legendary
  unlock_level: 16
  description: Summoned DR-1s cause {X} bleeding damage.
  levels:
  - X: 20%
  - X: 40%
  - X: 60%
  - X: 80%
  - X: 100%
  - X: '110%'
- name: Homebody
  slug: homebody
  rarity: Epic
  unlock_level: 18
  description: '{X} damage resistance near Energy Taps.'
  levels:
  - X: 20%
  - X: 24%
  - X: 26%
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Heroic Venom EMBAR
  slug: heroic-venom-embar
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {EMBAR Railgun}.'
---
