---
cssclass: json5e-monster
tags:
- compendium/src/rmbre
- monster/size/large
- monster/type/monstrosity/shapechanger
- monster/environment/underdark
- monster/environment/urban
aliases: ["Large Mimic"]
statblock: true
"name": "Large Mimic"
"size": "Large"
"type": "monstrosity"
"subtype": "shapechanger"
"alignment": "Neutral"
"ac": !!int "12"
"hp": !!int "75"
"hit_dice": "9d8 + 18"
"stats":
- !!int "17"
- !!int "12"
- !!int "15"
- !!int "5"
- !!int "13"
- !!int "8"
"speed": "walk 0 ft."
"skillsaves":
  "Stealth": !!int "5"
"damage_immunities": "acid"
"condition_immunities": "prone"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": ""
"cr": "3"
"traits":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The mimic can use its action to polymorph into an object or back into its\
    \ true, amorphous form. Its statistics are the same in each form. Any equipment\
    \ it is wearing or carrying isn't transformed. It reverts to its true form if\
    \ it dies."
  "name": "Shapechanger"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The mimic adheres to anything that touches it. A Huge or smaller creature\
    \ adhered to the mimic is also [grappled](/rules/conditions.md#grappled) by it\
    \ (escape DC 13). Ability checks made to escape this grapple have disadvantage."
  "name": "Adhesive (Object Form Only)"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "While the mimic remains motionless, it is indistinguishable from an ordinary\
    \ object."
  "name": "False Appearance (Object Form Only)"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The mimic has advantage on attack rolls against any creature [grappled](/rules/conditions.md#grappled)\
    \ by it."
  "name": "Grappler"
"actions":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The mimic makes three attacks: two with its pseudopods and one with its\
    \ bite."
  "name": "Multiattack"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) bludgeoning damage. If the mimic is in object form, the target is subjected\
    \ to its Adhesive trait."
  "name": "Pseudopod"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage plus 4 (1d8) acid damage."
  "name": "Bite"
"source":
- "RMBRE"
name: Large Mimic
image: "[[Large Mimic.png]]"
---

# Large Mimic

```statblock
"name": "Large Mimic"
"size": "Large"
"type": "monstrosity"
"subtype": "shapechanger"
"alignment": "Neutral"
"ac": !!int "12"
"hp": !!int "75"
"hit_dice": "9d8 + 18"
"stats":
- !!int "17"
- !!int "12"
- !!int "15"
- !!int "5"
- !!int "13"
- !!int "8"
"speed": "walk 0 ft."
"skillsaves":
  "Stealth": !!int "5"
"damage_immunities": "acid"
"condition_immunities": "prone"
"senses": "darkvision 60 ft., passive Perception 11"
"languages": ""
"cr": "3"
"traits":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The mimic can use its action to polymorph into an object or back into its\
    \ true, amorphous form. Its statistics are the same in each form. Any equipment\
    \ it is wearing or carrying isn't transformed. It reverts to its true form if\
    \ it dies."
  "name": "Shapechanger"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The mimic adheres to anything that touches it. A Huge or smaller creature\
    \ adhered to the mimic is also [grappled](/rules/conditions.md#grappled) by it\
    \ (escape DC 13). Ability checks made to escape this grapple have disadvantage."
  "name": "Adhesive (Object Form Only)"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "While the mimic remains motionless, it is indistinguishable from an ordinary\
    \ object."
  "name": "False Appearance (Object Form Only)"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The mimic has advantage on attack rolls against any creature [grappled](/rules/conditions.md#grappled)\
    \ by it."
  "name": "Grappler"
"actions":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The mimic makes three attacks: two with its pseudopods and one with its\
    \ bite."
  "name": "Multiattack"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) bludgeoning damage. If the mimic is in object form, the target is subjected\
    \ to its Adhesive trait."
  "name": "Pseudopod"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) piercing damage plus 4 (1d8) acid damage."
  "name": "Bite"
"source":
- "RMBRE"
"image": "[[Large Mimic.png]]"
```
^statblock

*Source: The Lost Dungeon of Rickedness: Big Rick Energy p. 122*

## Environment

underdark, urban