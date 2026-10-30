---
title: Pilot
slug: pilot
category: Tank
role: Tank
description: 'The Pilot uses the powerful Silverback exosuit to survive tough situations and deal devastating damage to the enemy.

  '
traits:
- name: Bleeding
  note: '[[card:bleeding-mulcher]] Card unlocks at Level 10'
- name: Freeze
  note: '[[card:quick-ice-cannon]] Card unlocks at Level 2 + [[card:cold-finish]] Card unlocks at Level 14'
- name: Summon
  note: 'Built into $ultimate'
- name: Stim
  note: '[[card:aggressive-armor]] Card unlocks at Level 7'
passive:
  name: Ultimate Recharge
  description: Damage you take slowly recharges your ultimate.
active:
  name: Summon Silverback
  description: Summon and pilot a Silverback on the battlefield.
  duration: 35s
  cooldown: 400s
ultimate:
  name: Summon Silverback
  description: Summon and pilot a Silverback on the battlefield.
  duration: 35s
  cooldown: 400s
weapons:
- name: Enforcer Submachine Gun
  slug: enforcer
- name: Dropshot Munitions Launcher
  slug: dropshot
- name: Talon Autopistol
  slug: talon
# right=N1, left=N2, down=Pistol, up=Grenade - confirmed from
# ref/Class Menus/Class Menu - Pilot.jpg: Enforcer on-screen left (N1),
# Dropshot on-screen right (N2), Talon in the pistol slot, no grenade
# shown (X).
weapon_slots:
  right:
    name: Enforcer Submachine Gun
    slug: enforcer
  left:
    name: Dropshot Munitions Launcher
    slug: dropshot
  down:
    name: Talon Autopistol
    slug: talon
perks:
  up:
    name: Health
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  right:
    name: Ammo Capacity
    values: ['10%', '20%', '30%', '40%', '50%', '60%', '70%', '80%', '90%', '100%']
  down:
    name: Damage
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
- name: Quick Ice Cannon
  slug: quick-ice-cannon
  rarity: Common
  unlock_level: 2
  description: Equip an Ice Cannon with {X} increased freezing speed.
  levels:
  - X: 10%
  - X: '20%'
  - X: '30%'
  - X: '40%'
  - X: '45%'
  - X: '50%'
- name: Rear Armor
  slug: rear-armor
  rarity: Common
  unlock_level: 3
  description: '{X} damage resistance from behind.'
  levels:
  - X: 30%
  - X: '40%'
  - X: '50%'
  - X: '54%'
  - X: '58%'
  - X: '60%'
- name: Explosive Munitions
  slug: explosive-munitions
  rarity: Common
  unlock_level: 4
  description: Silverback kills while in Defense Mode do {X} splash damage.
  levels:
  - X: 50%
  - X: '60%'
  - X: '70%'
  - X: '75%'
  - X: '80%'
  - X: '85%'
- name: Deep Pockets
  slug: deep-pockets
  rarity: Rare
  unlock_level: 5
  description: '{X} increased pistol capacity.'
  levels:
  - X: 40%
  - X: '55%'
  - X: '70%'
  - X: '85%'
  - X: '100%'
  - X: '115%'
- name: Enforcer Expert
  slug: enforcer-expert
  rarity: Common
  unlock_level: 5
  description: '{X} extra damage and {Y} active effects when firing the Enforcer.'
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
- name: Exploding Buzzkill
  slug: exploding-buzzkill
  rarity: Common
  unlock_level: 6
  description: Equip a Buzzkill with {X} splash damage on kills.
  levels:
  - X: 50%
  - X: '60%'
  - X: '70%'
  - X: '75%'
  - X: '80%'
  - X: '85%'
- name: Aggressive Armor
  slug: aggressive-armor
  rarity: Rare
  unlock_level: 7
  description: Dealing damage grants {X} Stim.
  levels:
  - X: 1HP
  - X: '2 HP'
  - X: '3 HP'
  - X: '4 HP'
  - X: '5 HP'
  - X: '6 HP'
- name: Healing Munitions
  slug: healing-munitions
  rarity: Common
  unlock_level: 8
  description: Explosive damage heals the Silverback for {X} of damage dealt.
  levels:
  - X: 20%
  - X: '50%'
  - X: '70%'
  - X: '90%'
  - X: '100%'
  - X: '110%'
- name: Initiator
  slug: initiator
  rarity: Rare
  unlock_level: 9
  description: Damaging a full health enemy taunts it for {X}.
  levels:
  - X: 2s
  - X: '2.25s'
  - X: '2.75s'
  - X: '3s'
  - X: '3.5s'
  - X: '4s'
- name: Bleeding Mulcher
  slug: bleeding-mulcher
  rarity: Epic
  unlock_level: 10
  description: Equip a Mulcher that causes bleeding for {X} of damage dealt.
  levels:
  - X: 20%
  - X: '30%'
  - X: '40%'
  - X: '45%'
  - X: '50%'
  - X: '55%'
- name: Healing Explosives
  slug: healing-explosives
  rarity: Rare
  unlock_level: 11
  description: Explosive damage heals for {X} of the damage dealt.
  levels:
  - X: 20%
  - X: '50%'
  - X: '70%'
  - X: '90%'
  - X: '100%'
  - X: '110%'
- name: Healing Trishot
  slug: healing-trishot
  rarity: Epic
  unlock_level: 12
  description: Equip a Trishot which heals the Silverback for {X} of damage dealt.
  levels:
  - X: 50%
  - X: '60%'
  - X: '70%'
  - X: '75%'
  - X: '80%'
  - X: '85%'
- name: Wingman
  slug: wingman
  rarity: Rare
  unlock_level: 13
  description: Ultimate recharges at {X} when 2 or less teammates remain.
  levels:
  - X: 150%
  - X: '170%'
  - X: '190%'
  - X: '195%'
  - X: '200%'
  - X: '205%'
- name: Cold Finish
  slug: cold-finish
  rarity: Epic
  unlock_level: 14
  description: Damaging an enemy with Low Health freezes it for {X}.
  levels:
  - X: 20%
  - X: '30%'
  - X: '40%'
  - X: '50%'
  - X: '60%'
  - X: '70%'
- name: The Hammer
  slug: the-hammer
  rarity: Legendary
  unlock_level: 14
  description: 'Dropshot deals {X} extra damage and stuns the enemy for {Y}.'
  levels:
  - X: '30%'
    Y: '1.5s'
  - X: '40%'
    Y: '2s'
  - X: '50%'
    Y: '2.5s'
  - X: '60%'
    Y: '3s'
  - X: '70%'
    Y: '3.5s'
  - X: '80%'
    Y: '4s'
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
- name: Silverback Salvo
  slug: silverback-salvo
  rarity: Legendary
  unlock_level: 16
  description: Silverback Salvo hits increase Silverback duration by {X}.
  levels:
  - X: 0.3s
  - X: '0.6s'
  - X: '0.9s'
  - X: '1.05s'
  - X: '1.2s'
  - X: '1.35s'
- name: Silverback Scorcher
  slug: silverback-scorcher
  rarity: Epic
  unlock_level: 18
  description: Equip a Scorcher that deals +{X} damage.
  levels:
  - X: 20%
  - X: '40%'
  - X: '60%'
  - X: '80%'
  - X: '100%'
  - X: '120%'
- name: Heroic Venom Dropshot
  slug: heroic-venom-dropshot
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Dropshot Munitions Launcher}.'
---
