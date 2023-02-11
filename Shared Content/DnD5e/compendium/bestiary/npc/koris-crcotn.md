---
cssclass: json5e-monster
tags:
- compendium/src/crcotn
- monster/size/medium
- monster/type/humanoid/tiefling
- monster/environment/urban
aliases: ["Koris"]
statblock: true
"name": "Koris"
"size": "Medium"
"type": "humanoid"
"subtype": "tiefling"
"alignment": "Lawful Neutral"
"ac": !!int "15"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"stats":
- !!int "11"
- !!int "16"
- !!int "14"
- !!int "13"
- !!int "11"
- !!int "10"
"speed": "walk 30 ft."
"saves":
  "Dexterity": !!int "6"
  "Intelligence": !!int "4"
"skillsaves":
  "Deception": !!int "3"
  "Stealth": !!int "9"
  "Perception": !!int "3"
  "Acrobatics": !!int "6"
"damage_resistances": "poison, fire"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Thieves' cant plus any two languages, Infernal"
"cr": "8"
"traits":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Koris's innate spellcasting ability is Charisma (spell save DC 11). Koris\
    \ can innately cast the following spells, requiring no material components:\n\n\
    At will: [thaumaturgy](/compendium/spells/thaumaturgy.md)\n\n1/day each:\
    \ [darkness](/compendium/spells/darkness.md), [hellish rebuke](/compendium/spells/hellish-rebuke.md)"
  "name": "innate"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "During its first turn, Koris has advantage on attack rolls against any\
    \ creature that hasn't taken a turn. Any hit Koris scores against a surprised\
    \ creature is a critical hit."
  "name": "Assassinate"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "If Koris is subjected to an effect that allows it to make a Dexterity saving\
    \ throw to take only half damage, Koris instead takes no damage if it succeeds\
    \ on the saving throw, and only half damage if it fails."
  "name": "Evasion"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Koris deals an extra 14 (4d6) damage when it hits a target with a weapon\
    \ attack and has advantage on the attack roll, or when the target is within 5\
    \ feet of an ally of Koris that isn't [incapacitated](/rules/conditions.md#incapacitated)\
    \ and Koris doesn't have disadvantage on the attack roll."
  "name": "Sneak Attack (1/Turn)"
"actions":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Koris makes two shortsword attacks."
  "name": "Multiattack"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage, and the target must make a DC 15 Constitution saving throw,\
    \ taking 24 (7d6) poison damage on a failed save, or half as much damage on a\
    \ successful one."
  "name": "Shortsword"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Ranged Weapon Attack: +6 to hit, range 80/320 ft., one target. Hit: 7\
    \ (1d8 + 3) piercing damage, and the target must make a DC 15 Constitution saving\
    \ throw, taking 24 (7d6) poison damage on a failed save, or half as much damage\
    \ on a successful one."
  "name": "Light Crossbow"
"source":
- "CRCotN"
name: Koris
image: "[[Koris.png]]"
---

# Koris

```statblock
"name": "Koris"
"size": "Medium"
"type": "humanoid"
"subtype": "tiefling"
"alignment": "Lawful Neutral"
"ac": !!int "15"
"hp": !!int "78"
"hit_dice": "12d8 + 24"
"stats":
- !!int "11"
- !!int "16"
- !!int "14"
- !!int "13"
- !!int "11"
- !!int "10"
"speed": "walk 30 ft."
"saves":
  "Dexterity": !!int "6"
  "Intelligence": !!int "4"
"skillsaves":
  "Deception": !!int "3"
  "Stealth": !!int "9"
  "Perception": !!int "3"
  "Acrobatics": !!int "6"
"damage_resistances": "poison, fire"
"senses": "darkvision 60 ft., passive Perception 13"
"languages": "Thieves' cant plus any two languages, Infernal"
"cr": "8"
"traits":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Koris's innate spellcasting ability is Charisma (spell save DC 11). Koris\
    \ can innately cast the following spells, requiring no material components:\n\n\
    At will: [thaumaturgy](/compendium/spells/thaumaturgy.md)\n\n1/day each:\
    \ [darkness](/compendium/spells/darkness.md), [hellish rebuke](/compendium/spells/hellish-rebuke.md)"
  "name": "innate"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "During its first turn, Koris has advantage on attack rolls against any\
    \ creature that hasn't taken a turn. Any hit Koris scores against a surprised\
    \ creature is a critical hit."
  "name": "Assassinate"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "If Koris is subjected to an effect that allows it to make a Dexterity saving\
    \ throw to take only half damage, Koris instead takes no damage if it succeeds\
    \ on the saving throw, and only half damage if it fails."
  "name": "Evasion"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Koris deals an extra 14 (4d6) damage when it hits a target with a weapon\
    \ attack and has advantage on the attack roll, or when the target is within 5\
    \ feet of an ally of Koris that isn't [incapacitated](/rules/conditions.md#incapacitated)\
    \ and Koris doesn't have disadvantage on the attack roll."
  "name": "Sneak Attack (1/Turn)"
"actions":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Koris makes two shortsword attacks."
  "name": "Multiattack"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) piercing damage, and the target must make a DC 15 Constitution saving throw,\
    \ taking 24 (7d6) poison damage on a failed save, or half as much damage on a\
    \ successful one."
  "name": "Shortsword"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Ranged Weapon Attack: +6 to hit, range 80/320 ft., one target. Hit: 7\
    \ (1d8 + 3) piercing damage, and the target must make a DC 15 Constitution saving\
    \ throw, taking 24 (7d6) poison damage on a failed save, or half as much damage\
    \ on a successful one."
  "name": "Light Crossbow"
"source":
- "CRCotN"
"image": "[[Koris.png]]"
```
^statblock

*Source: Critical Role: Call of the Netherdeep p. 343*

## Environment

urban