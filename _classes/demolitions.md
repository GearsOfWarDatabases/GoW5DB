---
title: Demolitions
slug: demolitions
category: Assault
role: Assault
description: 'Raining death from above, the Demolitions class strikes down priority targets with powerful explosive weaponry.

  '
traits:
- name: Ammo Regeneration
  note: 'Ammo Regeneration Perk (► Right Slot)'
- name: Bleeding
  note: '[[card:razor-hail]] Card unlocks at Level 12'
- name: Marking
  note: 'Target Painter passive marks up to 5 targets for $ultimate'
passive:
  name: Target Painter
  description: Mark up to 5 targets and marks last twice as long.
active:
  name: Artillery Strike
  description: Drops five artillery rounds onto each enemy you have marked.
  duration: N/A
  cooldown: 600s
ultimate:
  name: Artillery Strike
  description: Drops five artillery rounds onto each enemy you have marked.
  duration: N/A
  cooldown: 600s
weapons:
- name: Lancer
  slug: lancer
- name: Boomshot Grenade Launcher
  slug: boomshot
- name: Snub Pistol
  slug: snub-pistol
# right=N1, left=N2, down=Pistol, up=Grenade - confirmed from
# ref/Class Menus/Class Menu - Demolitions.jpg: Lancer on-screen left
# (N1), Boomshot on-screen right (N2), Snub Pistol in the pistol slot,
# no grenade shown.
weapon_slots:
  right:
    name: Lancer
    slug: lancer
  left:
    name: Boomshot Grenade Launcher
    slug: boomshot
  down:
    name: Snub Pistol
    slug: snub-pistol
perks:
  up:
    name: Ultimate Cooldown
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  right:
    name: Ammo Regeneration
    values: ['10%', '20%', '30%', '40%', '50%', '60%', '70%', '80%', '95%', '100%']
  down:
    name: Assault Rifle Damage
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  left:
    name: Critical Damage
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
- name: Officer's Prerogative
  slug: officers-prerogative
  rarity: Common
  unlock_level: 2
  description: Artillery fires {X} additional rounds.
  levels:
  - X: '1'
  - X: '2'
  - X: '3'
  - X: '4'
  - X: '5'
  - X: '6'
- name: Lancer GL Mastery
  slug: lancer-gl-mastery
  rarity: Common
  unlock_level: 3
  description: '{X} less recoil and {Y} increased headshot damage.'
  levels:
  - X: '30%'
    Y: '2%'
  - X: '45%'
    Y: '4%'
  - X: '60%'
    Y: '6%'
  - X: '75%'
    Y: '8%'
  - X: '90%'
    Y: '10%'
  - X: '95%'
    Y: '13%'
- name: Inspired
  slug: inspired
  rarity: Common
  unlock_level: 4
  description: '{X} damage resistance near Veteran class.'
  levels:
  - X: '20%'
  - X: '24%'
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Concussive Strike
  slug: concussive-strike
  rarity: Rare
  unlock_level: 5
  description: Artillery stuns enemies for {X}.
  levels:
  - X: '6s'
  - X: '7s'
  - X: '8.5s'
  - X: '9s'
  - X: '10s'
  - X: '10.5s'
- name: Launcher Mastery
  slug: launcher-mastery
  rarity: Common
  unlock_level: 6
  description: '{X} larger active reload bar.'
  levels:
  - X: '50%'
  - X: '100%'
  - X: '150%'
  - X: '175%'
  - X: '200%'
  - X: '225%'
- name: Custom Lancer GL
  slug: custom-lancer-gl
  rarity: Rare
  unlock_level: 7
  description: '{X} increased damage and {Y} active effects with the Lancer GL.'
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
- name: Good Kill
  slug: good-kill
  rarity: Common
  unlock_level: 8
  description: 'Kills within 5m of allies have {X} chance to drop an ammo crate ({Y}).'
  levels:
  - X: '20%'
    Y: 'Ammo Pilfer'
  - X: '40%'
    Y: 'Ammo Pilfer'
  - X: '60%'
    Y: 'Ammo Pilfer'
  - X: '80%'
    Y: 'Ammo Pilfer'
  - X: '100%'
    Y: 'Ammo Pilfer'
  - X: '100%'
    Y: 'Ammo Pouch'
- name: Custom Boomshot
  slug: custom-boomshot
  rarity: Rare
  unlock_level: 9
  description: '{X} increased damage and {Y} active effects with the Boomshot.'
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
- name: Spotter Support
  slug: spotter-support
  rarity: Epic
  unlock_level: 10
  art_fit: contain
  description: Artillery drops {X} rounds on ally marked targets.
  levels:
  - X: '2'
  - X: '3'
  - X: '4'
  - X: '5'
  - X: '6'
  - X: '7'
- name: Grenade Satchel
  slug: grenade-satchel
  rarity: Rare
  unlock_level: 11
  description: Grenade capacity increased by {X}.
  levels:
  - X: '1'
  - X: '2'
  - X: '3'
  - X: '4'
  - X: '5'
  - X: '6'
- name: Razor Hail
  slug: razor-hail
  rarity: Epic
  unlock_level: 12
  description: Explosive hits cause bleeding for {X} of damage.
  levels:
  - X: '15%'
  - X: '18%'
  - X: '21%'
  - X: '24%'
  - X: '27%'
  - X: '30%'
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
- name: Confirmed Kill
  slug: confirmed-kill
  rarity: Legendary
  unlock_level: 16
  description: Kills with Artillery recharge Artillery by {X}.
  levels:
  - X: '15s'
  - X: '17s'
  - X: '19s'
  - X: '21s'
  - X: '23s'
  - X: '25s'
- name: Gambit
  slug: gambit
  rarity: Rare
  unlock_level: 18
  description: Plant {X} extra grenade trap.
  levels:
  - X: '1'
  - X: '2'
  - X: '3'
  - X: '4'
  - X: '5'
  - X: '6'
- name: Bullet Boost
  slug: bullet-boost
  rarity: Legendary
  unlock_level: 19
  description: Explosive or bleed kills give +{X} ballistic damage for 15s.
  levels:
  - X: '25%'
  - X: '30%'
  - X: '35%'
  - X: '40%'
  - X: '45%'
  - X: '50%'
- name: Heroic Venom Lancer GL
  slug: heroic-venom-lancer-gl
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Lancer GL}.'
---
