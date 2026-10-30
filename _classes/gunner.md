---
title: Gunner
slug: gunner
category: Tank
role: Tank
description: 'Specializing in heavy weapons, the Gunner is equipped to lay down heavy fire and take hits like no other.

  '
hidden: '$ultimate will fully heal the player on use.'
traits:
- name: Ammo Regeneration
  note: 'Only for Heavy Weapons'
- name: Bleeding
  note: '[[card:reflect-shredder]] Card unlocks at Level 16 + [[card:serrated-edge]] Card unlocks at Level 16'
- name: Freeze
  note: '[[card:flash-freeze]] Card unlocks at Level 4 (with the Cryo Cannon)'
- name: Stim
  note: '[[card:phoenix-armor]] Card unlocks at Level 6'
passive:
  name: Heavy Lifesteal
  description: Heal for 50% of heavy weapon damage dealt.
active:
  name: Reflective Shell
  description: While active, deflect all ballistic damage back to the enemy.
  duration: 6s
  cooldown: 150s
ultimate:
  name: Reflective Shell
  description: While active, deflect all ballistic damage back to the enemy.
  duration: 6s
  cooldown: 150s
weapons:
- name: Retro Lancer
  slug: retro-lancer
- name: Torque Bow
  slug: torque-bow
- name: Snub Pistol
  slug: snub-pistol
# right=N1, left=N2, down=Pistol, up=Grenade - confirmed from
# ref/Class Menus/Class Menu - Gunner.jpg: Retro Lancer on-screen left
# (N1), Torque Bow on-screen right (N2), Snub Pistol in the pistol slot,
# no grenade shown.
weapon_slots:
  right:
    name: Retro Lancer
    slug: retro-lancer
  left:
    name: Torque Bow
    slug: torque-bow
  down:
    name: Snub Pistol
    slug: snub-pistol
perks:
  up:
    name: Health
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  right:
    name: Chaingun Ammo Regeneration
    values: ['10%', '20%', '30%', '40%', '50%', '60%', '70%', '80%', '90%', '100%']
  down:
    name: Damage
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  left:
    name: Ultimate Duration
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
- name: Freeze Resist
  slug: freeze-resist
  rarity: Common
  unlock_level: 2
  description: Time to freeze is {X} slower.
  levels:
  - X: 50%
  - X: 60%
  - X: 70%
  - X: '85%'
  - X: '90%'
  - X: '95%'
- name: Tank Synergy
  slug: tank-synergy
  rarity: Common
  unlock_level: 3
  description: '{X} damage resistance for Gunner and Pilot when near.'
  levels:
  - X: 5%
  - X: 10%
  - X: '15%'
  - X: '20%'
  - X: '25%'
  - X: '30%'
- name: Flash Freeze
  slug: flash-freeze
  rarity: Common
  unlock_level: 4
  description: Freeze enemies with the Cryo Cannon {X} faster.
  levels:
  - X: 50%
  - X: 80%
  - X: '110%'
  - X: '140%'
  - X: '170%'
  - X: '200%'
- name: Heavy Capacity
  slug: heavy-capacity
  rarity: Rare
  unlock_level: 4
  description: Carry {X} more heavy weapon ammo.
  levels:
  - X: 40%
  - X: 55%
  - X: '70%'
  - X: '85%'
  - X: '100%'
  - X: '115%'
- name: Bait Armor
  slug: bait-armor
  rarity: Rare
  unlock_level: 5
  description: Every hit taken adds {X} damage resistance for 5 seconds up to a maximum of 60%.
  levels:
  - X: 5%
  - X: 6%
  - X: 7%
  - X: '8%'
  - X: '9%'
  - X: '10%'
- name: Phoenix Armor
  slug: phoenix-armor
  rarity: Common
  unlock_level: 6
  description: When a teammate revives you from DBNO, you receive {X} Stim.
  levels:
  - X: 5%
  - X: 10%
  - X: 15%
  - X: '20%'
  - X: '25%'
  - X: '30%'
- name: Blast Shield
  slug: blast-shield
  rarity: Common
  unlock_level: 6
  description: Explosive damage reduced by {X} for you and allies within 10 meters.
  levels:
  - X: 20%
  - X: 24%
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Sole Survivor
  slug: sole-survivor
  rarity: Rare
  unlock_level: 7
  description: Reflective Shell Ultimate Ability recharges at {X} if you are the only surviving teammate.
  levels:
  - X: 150%
  - X: 200%
  - X: 250%
  - X: 280%
  - X: '300%'
  - X: '320%'
- name: Grub Magnet
  slug: grub-magnet
  rarity: Common
  unlock_level: 8
  description: Dealing headshot damage to an enemy forces it to attack you for {X}.
  levels:
  - X: 2s
  - X: 3s
  - X: '4s'
  - X: '5s'
  - X: '6s'
  - X: '7s'
- name: Practice Every Day
  slug: practice-every-day
  rarity: Common
  unlock_level: 8
  description: '{X} faster reload speed, {Y} larger active reload window and bypass reload when firing during Reflective Shell.'
  levels:
  - X: 5%
    Y: 10%
  - X: 10%
    Y: 20%
  - X: '15%'
    Y: '30%'
  - X: '20%'
    Y: '40%'
  - X: '25%'
    Y: '50%'
  - X: '30%'
    Y: '60%'
- name: Heavy Shell
  slug: heavy-shell
  unlock_level: 9
  description: Reflective Shell can reflect projectiles for {X}.
  levels:
  - X: 2s
  - X: 3s
  - X: 4s
  - X: '4.5s'
  - X: '5s'
  - X: '6s'
  rarity: Common
- name: Team Resist
  slug: team-resist
  unlock_level: 10
  description: When Reflective Shell Ultimate Ability is activated, all allies receive {X} damage resistance for 6s.
  levels:
  - X: 50%
  - X: 60%
  - X: '70%'
  - X: '85%'
  - X: '90%'
  - X: '95%'
  rarity: Epic
- name: Concussive Explosives
  slug: concussive-explosives
  unlock_level: 11
  description: Enemies hit with explosives under 15 meters away are stunned for {X}.
  levels:
  - X: 1.5s
  - X: 2s
  - X: 2.5s
  - X: '2.8s'
  - X: '3s'
  - X: '3.2s'
  rarity: Rare
- name: Ultimate Battery
  slug: ultimate-battery
  unlock_level: 12
  description: Ultimate cooldown for allies within 10 meters reduced by {X} for each hit you take.
  levels:
  - X: 0.1s
  - X: 0.15s
  - X: '0.2s'
  - X: '0.25s'
  - X: '0.3s'
  - X: '0.35s'
  rarity: Epic
- name: Mulcher Mastery
  slug: mulcher-mastery
  unlock_level: 12
  description: Mulcher deals {X} extra damage.
  levels:
  - X: 30%
  - X: 40%
  - X: '50%'
  - X: '60%'
  - X: '70%'
  - X: '80%'
  rarity: Epic
- name: Heavy Charger
  slug: heavy-charger
  rarity: Rare
  unlock_level: 13
  description: Heavy hits reduce ultimate cooldown in multiples of {X}.
  levels:
  - X: 0.004s
  - X: '.006s'
  - X: '.008s'
  - X: '.010s'
  - X: '.012s'
  - X: '.014s'
- name: Heavy Deflect
  slug: heavy-deflect
  rarity: Rare
  unlock_level: 14
  description: '{X} heavy weapon resistance for you and nearby allies.'
  levels:
  - X: 20%
  - X: 24%
  - X: 26%
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
- name: Grace Period
  slug: grace-period
  rarity: Rare
  unlock_level: 15
  description: '{X} immunity on revival.'
  levels:
  - X: '2s'
  - X: '3s'
  - X: '3.5s'
  - X: '4s'
  - X: '4.5s'
  - X: '5s'
- name: Reflect Shredder
  slug: reflect-shredder
  rarity: Legendary
  unlock_level: 16
  description: Hits reflected by Reflective Shell do {X} bleeding damage.
  levels:
  - X: '20%'
  - X: '30%'
  - X: '40%'
  - X: '45%'
  - X: '50%'
  - X: '55%'
- name: Serrated Edge
  slug: serrated-edge
  rarity: Legendary
  unlock_level: 16
  description: Torque Bow deals {X} bleeding damage.
  levels:
  - X: '15%'
  - X: '20%'
  - X: '25%'
  - X: '30%'
  - X: '35%'
  - X: '40%'
- name: Heroic Venom Torque Bow
  slug: heroic-venom-torque-bow
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Torque Bow}.'
---
