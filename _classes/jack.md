---
title: Jack
slug: jack
category: Support
role: Support
description: 'Jack is a one of a kind support bot with the ability to cloak, heal, and stun. His versatility makes him invaluable to the team.

  '
hidden: '- [[robotics-expert]]''s [[ultimate:robotics-expert]] can be repaired by [[weapon:repair-beam]] at no Power cost.<br>- [[pilot]]''s [[ultimate:pilot]] can be repaired by [[weapon:repair-beam]] at no Power cost.<br>- [[weapon:repair-beam]] repairs faster than the [[repair-tool]].'
traits:
- name: Repairing
  note: 'Built into [[weapon:repair-beam]]'
- name: Ammo Regeneration
  note: '[[card:portable-supply]] Card unlocks at Level 5'
- name: Bleeding
  note: '[[card:rampage]] Card unlocks at Level 19'
- name: Invisibility
  note: 'Built into [[weapon:cloak]]'
passive:
  name: Stun Target
  description: Teammates deal +50% damage to your Stun Beam target.
active:
  name: Hijack
  description: Take control of an enemy and wreak havoc. Enemies have infinite reserve ammo for the duration. Horde Bosses cannot be Hijacked.
  duration: 20–35s (depends on enemy)
  cooldown: 300s
ultimate:
  name: Hijack
  description: Take control of an enemy and wreak havoc. Enemies have infinite reserve ammo for the duration. Horde Bosses cannot be Hijacked.
  duration: 20–35s (depends on enemy)
  cooldown: 300s
weapons:
- name: Repair Beam
  slug: repair-beam
- name: Stun Beam
  slug: stun-beam
- name: Cloak
  slug: cloak
perks:
  up:
    name: Health
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  right:
    name: Ultimate Cooldown
    values: ['5%', '10%', '15%', '20%', '25%', '30%', '35%', '40%', '45%', '50%']
  down:
    name: Repair Cost Reduction
    values: ['5%', '9%', '13%', '17%', '20%', '22%', '24%', '26%', '28%', '30%']
  left:
    name: Health Regeneration
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
- name: Healing Reach
  slug: healing-reach
  rarity: Common
  unlock_level: 2
  description: '{X} increased healing distance.'
  levels:
  - X: '20%'
  - X: '30%'
  - X: '40%'
  - X: '50%'
  - X: '60%'
  - X: 70%
- name: Zapper Upgrade
  slug: zapper-upgrade
  rarity: Common
  unlock_level: 3
  description: '{X} increased damage.'
  levels:
  - X: '20%'
  - X: '50%'
  - X: '60%'
  - X: '70%'
  - X: '100%'
  - X: 130%
- name: Optimizer
  slug: optimizer
  rarity: Common
  unlock_level: 4
  description: '{X} more power when smelting.'
  levels:
  - X: '50%'
  - X: '70%'
  - X: '90%'
  - X: '110%'
  - X: 130%
  - X: 150%
- name: Portable Resupply
  slug: portable-supply
  rarity: Rare
  unlock_level: 5
  description: +{X} ammo regen on carried weapon.
  hidden: Also keeps Jack invisible while he's carrying something.
  levels:
  - X: '0%'
  - X: '25%'
  - X: '50%'
  - X: '75%'
  - X: 100%
  - X: 125%
- name: Healing Upgrade
  slug: healing-upgrade
  rarity: Common
  unlock_level: 6
  description: '{X} increased healing rate.'
  levels:
  - X: '20%'
  - X: '50%'
  - X: '60%'
  - X: '70%'
  - X: '100%'
  - X: 130%
- name: Repair Speed
  slug: repair-speed
  rarity: Rare
  unlock_level: 8
  description: Repair fortifications {X} faster.
  levels:
  - X: '20%'
  - X: '50%'
  - X: '60%'
  - X: 70%
  - X: 100%
  - X: '130%'
- name: Mind Control Expert
  slug: mind-control-expert
  rarity: Epic
  unlock_level: 10
  description: Increase the health of Hijacked Enemies by {X}.
  levels:
  - X: '20%'
  - X: '50%'
  - X: 60%
  - X: 70%
  - X: '100%'
  - X: '130%'
- name: Explosive Hijack
  slug: explosive-hijack
  rarity: Epic
  unlock_level: 12
  description: Hijacked enemies explode and deal {X} additional damage.
  levels:
  - X: '20%'
  - X: '50%'
  - X: '70%'
  - X: 90%
  - X: '110%'
  - X: '130%'
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
- name: Backstab
  slug: backstab
  rarity: Legendary
  unlock_level: 16
  description: Hijack kills extend Hijack by {X}.
  levels:
  - X: '10%'
  - X: '14%'
  - X: '18%'
  - X: '21%'
  - X: 23%
  - X: '25%'
- name: Sacrifice
  slug: sacrifice
  rarity: Epic
  unlock_level: 18
  description: 'Dying as a hijacked unit revives downed teammates within {X}.'
  levels:
  - X: '5m'
  - X: 10m
  - X: 15m
  - X: '20m'
  - X: '25m'
  - X: '30m'
- name: Rampage
  slug: rampage
  rarity: Legendary
  unlock_level: 19
  description: Deal {X} bleeding damage during hijack.
  levels:
  - X: '20%'
  - X: 30%
  - X: 40%
  - X: '50%'
  - X: '60%'
  - X: '70%'
- name: Heroic Jack
  slug: heroic-jack
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic} skin<br>for: {Jack}.'
- name: Heroic Venom Hammerburst
  slug: heroic-venom-hammerburst
  type: skin
  rarity: Heroic
  unlock_level: 20
  description: 'Unlocks the {Heroic Venom} skin<br>for the: {Hammerburst}.'
---
