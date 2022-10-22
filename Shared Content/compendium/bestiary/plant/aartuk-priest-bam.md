---
cssclass: json5e-monster
tags:
- compendium/src/bam
- monster/size/medium
- monster/type/plant
aliases: ["Aartuk Priest"]
statblock: true
"name": "Aartuk Priest"
"size": "Medium"
"type": "plant"
"alignment": "Lawful Evil"
"ac": !!int "14"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "12"
- !!int "10"
- !!int "14"
- !!int "13"
- !!int "16"
- !!int "10"
"speed": "walk 20 ft., climb 20 ft."
"skillsaves":
  "Religion": !!int "3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Aartuk"
"cr": "2"
"traits":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The aartuk casts one of the following spells, requiring no spell components\
    \ and using Wisdom as the spellcasting ability:\n\n1/day each: [revivify](/compendium/spells/revivify.md),\
    \ [tongues](/compendium/spells/tongues.md)"
  "name": "spells"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The aartuk can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The aartuk makes two Branch attacks, two Radiant Pellet attacks, or one\
    \ of each."
  "name": "Multiattack"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +3 to hit, reach 10 ft., one target. Hit: 8 (2d6\
    \ + 1) bludgeoning damage."
  "name": "Branch"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Ranged Spell Attack: +2 to hit, range 60 ft., one target. Hit: 7 (3d4)\
    \ radiant damage."
  "name": "Radiant Pellet"
"bonus_actions":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The aartuk magically ends the [charmed](/rules/conditions.md#charmed) and\
    \ [frightened](/rules/conditions.md#frightened) conditions on itself and each\
    \ creature of its choice that it can see within 30 feet of itself."
  "name": "Rally the Troops (1/Day)"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The aartuk tries to use its gooey tongue to snare one Medium or smaller\
    \ creature it can see within 30 feet of itself. The target must make a DC 12 Dexterity\
    \ saving throw. On a failed save, the target is [grappled](/rules/conditions.md#grappled)\
    \ by the tongue (escape DC 11) and pulled up to 25 feet toward the aartuk. The\
    \ tongue can grapple one creature at a time."
  "name": "Tongue (Recharge 6)"
"source":
- "BAM"
- "LoX"
name: Aartuk Priest
image: "[[Aartuk Priest.png]]"
---

# Aartuk Priest

```statblock
"name": "Aartuk Priest"
"size": "Medium"
"type": "plant"
"alignment": "Lawful Evil"
"ac": !!int "14"
"hp": !!int "52"
"hit_dice": "8d8 + 16"
"stats":
- !!int "12"
- !!int "10"
- !!int "14"
- !!int "13"
- !!int "16"
- !!int "10"
"speed": "walk 20 ft., climb 20 ft."
"skillsaves":
  "Religion": !!int "3"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Aartuk"
"cr": "2"
"traits":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The aartuk casts one of the following spells, requiring no spell components\
    \ and using Wisdom as the spellcasting ability:\n\n1/day each: [revivify](/compendium/spells/revivify.md),\
    \ [tongues](/compendium/spells/tongues.md)"
  "name": "spells"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The aartuk can climb difficult surfaces, including upside down on ceilings,\
    \ without needing to make an ability check."
  "name": "Spider Climb"
"actions":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The aartuk makes two Branch attacks, two Radiant Pellet attacks, or one\
    \ of each."
  "name": "Multiattack"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +3 to hit, reach 10 ft., one target. Hit: 8 (2d6\
    \ + 1) bludgeoning damage."
  "name": "Branch"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Ranged Spell Attack: +2 to hit, range 60 ft., one target. Hit: 7 (3d4)\
    \ radiant damage."
  "name": "Radiant Pellet"
"bonus_actions":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The aartuk magically ends the [charmed](/rules/conditions.md#charmed) and\
    \ [frightened](/rules/conditions.md#frightened) conditions on itself and each\
    \ creature of its choice that it can see within 30 feet of itself."
  "name": "Rally the Troops (1/Day)"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The aartuk tries to use its gooey tongue to snare one Medium or smaller\
    \ creature it can see within 30 feet of itself. The target must make a DC 12 Dexterity\
    \ saving throw. On a failed save, the target is [grappled](/rules/conditions.md#grappled)\
    \ by the tongue (escape DC 11) and pulled up to 25 feet toward the aartuk. The\
    \ tongue can grapple one creature at a time."
  "name": "Tongue (Recharge 6)"
"source":
- "BAM"
- "LoX"
"image": "[[Aartuk Priest.png]]"
```
^statblock

*Source: Boo's Astral Menagerie p. 9, Light of Xaryxis*

## Description

Aartuks are intelligent plant creatures that live to wage war. Beholders destroyed their original home world and scattered the survivors across the Material Plane. These survivors formed small nomadic cells.

Aartuk cells can be found throughout Wildspace, including aboard spelljamming ships whose former crews were either murdered or forcibly ejected by a band of aartuks.

An aartuk's body is shaped like a five-pointed star and is covered with thick, flexible bark. The tips of its branch-like extremities end in suction cups that allow the creature to climb on vertical surfaces and along ceilings. Each suction cup houses three retractable pseudopods that are used to manipulate small objects.

The head of an aartuk surmounts a 6-foot-tall stalk that can be extruded from the center of the star. The head contains the aartuk's sensory organs, including a long tongue that the creature uses as a weapon.

An aartuk continues to grow throughout its long life. Aartuk elders can be as large as 12 feet in diameter.

An aartuk's preferred method of attack is to shoot forth its gooey tongue and use it to drag enemies toward the center of its body so that it can batter them with its powerful branches. It can also spit pellets of radiant energy.

Aartuks have no deities of their own, but certain groups have adopted various gods of war and vengeance, including Gruumsh, Hextor, and Sargonnas.

The Aartuk language is made up of rustling sounds, snaps, pops, and hisses. It has no written form.