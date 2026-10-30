---
title: Anchor
slug: anchor
category: Tank
role: Tank
description: 'The Anchor is a pistol specialist that uses an invincible barrier to outsmart the enemy.

  '
traits:
- name: Ammo Regeneration
  note: 'Ammo Regeneration Perk (◄ Left Slot)'
- name: Bleeding
  note: '[[card:bloody-shot]] Card unlocks at Level 3'
- name: Shield
  note: 'Built into $ultimate'
- name: Stim
  note: '[[card:harness-energy]] Card unlocks at Level 18'
passive:
  name: Pistol Mastery & Barrier Bonus
  description: Anyone who fires through your Barrier deals +50% damage. Deal +30% pistol damage.
active:
  name: Barrier
  description: Deploy an invulnerable shield that moves with you, blocking all incoming fire. Allies can fire through it for a damage bonus.
  cooldown: 150s
ultimate:
  name: Barrier
  description: Deploy an invulnerable shield that moves with you.
  duration: 20s
  cooldown: 150s
weapons:
- name: Retro Lancer
  slug: retro-lancer
- name: Markza Mk 1 Marksman Rifle
  slug: markza
- name: Boltok Pistol
  slug: boltok
# right=N1, left=N2, down=Pistol, up=Grenade - confirmed from
# ref/Class Menus/Class Menu - Anchor.jpg: Retro Lancer on-screen left
# (N1), Markza on-screen right (N2), Boltok in the pistol slot, no
# grenade shown.
weapon_slots:
  right:
    name: Retro Lancer
    slug: retro-lancer
  left:
    name: Markza Mk 1 Marksman Rifle
    slug: markza
  down:
    name: Boltok Pistol
    slug: boltok
perks:
  up:
    name: Critical Damage
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  right:
    name: Damage Resistance
    values: ['10%', '14%', '18%', '22%', '24%', '26%', '27%', '28%', '29%', '30%']
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
- name: Boltok Bandolier
  slug: boltok-bandolier
  rarity: Common
  unlock_level: 2
  description: '{X} increased Boltok capacity.'
  levels:
  - X: '40%'
  - X: '55%'
  - X: '70%'
  - X: '85%'
  - X: '100%'
  - X: '115%'
- name: Bloody Shot
  slug: bloody-shot
  rarity: Common
  unlock_level: 3
  description: Active pistol bullets cause bleeding for {X} of damage.
  levels:
  - X: 30%
  - X: 50%
  - X: '50%'
  - X: '60%'
  - X: '70%'
  - X: '80%'
- name: Crazy Tough
  slug: crazy-tough
  rarity: Common
  unlock_level: 4
  description: '{X} increased health.'
  levels:
  - X: '10%'
  - X: '20%'
  - X: 30%
  - X: 40%
  - X: 50%
  - X: '60%'
- name: Barrier Battery
  slug: barrier-battery
  rarity: Rare
  unlock_level: 5
  description: Barrier duration increased by {X}.
  levels:
  - X: '10%'
  - X: 20%
  - X: 30%
  - X: '40%'
  - X: '50%'
  - X: '60%'
- name: Barrier Boost
  slug: barrier-boost
  rarity: Common
  unlock_level: 6
  description: '{X} increased Barrier size.'
  levels:
  - X: '30%'
  - X: '40%'
  - X: '50%'
  - X: '60%'
  - X: '70%'
  - X: '150%'
- name: Lethal Barrier
  slug: lethal-barrier
  rarity: Rare
  unlock_level: 7
  description: Barrier does {X} increased damage to enemies.
  levels:
  - X: '100%'
  - X: 50%
  - X: 100%
  - X: '210%'
  - X: '220%'
  - X: '230%'
- name: Heads Up
  slug: heads-up
  rarity: Common
  unlock_level: 8
  description: '{X} resistance to friendly fire.'
  levels:
  - X: '50%'
  - X: '60%'
  - X: '70%'
  - X: '80%'
  - X: '99%'
  - X: '100%'
- name: Dodge
  slug: dodge
  rarity: Rare
  unlock_level: 9
  description: '{X} resistance to marksman weapons.'
  levels:
  - X: 20%
  - X: 24%
  - X: '26%'
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Adrenaline Junkie
  slug: adrenaline-junkie
  rarity: Epic
  unlock_level: 10
  description: '{X} increased damage in Venom.'
  levels:
  - X: '30%'
  - X: '40%'
  - X: '50%'
  - X: '60%'
  - X: '70%'
  - X: '80%'
- name: In Your Face
  slug: in-your-face
  rarity: Rare
  unlock_level: 11
  description: Headshots taunt enemies for {X}.
  levels:
  - X: '2s'
  - X: '3s'
  - X: '4s'
  - X: '5s'
  - X: '6s'
  - X: '7s'
- name: Venom Resistance
  slug: venom-resistance
  rarity: Rare
  unlock_level: 12
  description: '{X} damage resistance while in Venom.'
  levels:
  - X: 20%
  - X: 24%
  - X: 26%
  - X: '28%'
  - X: '30%'
  - X: '32%'
- name: Venom Recharge
  slug: venom-recharge
  rarity: Epic
  unlock_level: 13
  description: Kills in Venom recharge Barrier by {X}.
  levels:
  - X: '20s'
  - X: '23%'
  - X: '26%'
  - X: '29%'
  - X: '32%'
  - X: '35%'
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
- name: Barrier Feedback
  slug: barrier-feedback
  rarity: Legendary
  unlock_level: 16
  description: Kills during Barrier extend it by {X}.
  levels:
  - X: 2s
  - X: 2.2s
  - X: 2.4s
  - X: 2.6s
  - X: '2.8s'
  - X: '3s'
- name: Harness Energy
  slug: harness-energy
  rarity: Epic
  unlock_level: 18
  description: Each Barrier hit gives {X} Stim to the team.
  levels:
  - X: '1'
  - X: '2'
  - X: '3'
  - X: '4'
  - X: '5'
  - X: '6'
- name: Bullet Chain
  slug: bullet-chain
  rarity: Legendary
  unlock_level: 19
  description: Each headshot kill gives +{X} damage for 15s.
  levels:
  - X: '25%'
  - X: '30%'
  - X: '35%'
  - X: '40%'
  - X: '45%'
  - X: '50%'
- name: Heroic Venom Boltok
  slug: heroic-venom-boltok
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Boltok Pistol}.'
---
