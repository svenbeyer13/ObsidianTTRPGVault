---
cssclass: json5e-monster
tags:
- compendium/src/tftyp
- monster/size/medium
- monster/type/humanoid/elf
- monster/environment/arctic
- monster/environment/desert
- monster/environment/coastal
- monster/environment/grassland
- monster/environment/hill
- monster/environment/urban
- monster/environment/forest
aliases: ["Ashdra"]
statblock: true
"name": "Ashdra"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Chaotic Evil"
"ac": !!int "10"
"hp": !!int "4"
"hit_dice": "1d8"
"stats":
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
"speed": "walk 30 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "any one language (usually Common), Elvish"
"cr": "0"
"traits":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The ashdra's innate spellcasting ability is Charisma (spell save DC 10).\
    \ The ashdra can innately cast the following spells, requiring no material components:\n\
    \nAt will: [dancing lights](/compendium/spells/dancing-lights.md)\n\n1/day\
    \ each: [darkness](/compendium/spells/darkness.md), [faerie fire](/compendium/spells/faerie-fire.md)"
  "name": "innate"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The ashdra has advantage on saving throws against being charmed, and magic\
    \ can't put the ashdra to sleep."
  "name": "Fey Ancestry"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "While in sunlight, the ashdra has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](/rules/skills.md#Perception)) checks that rely on\
    \ sight."
  "name": "Sunlight Sensitivity"
"actions":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ bludgeoning damage."
  "name": "Club"
"source":
- "TftYP"
name: Ashdra
image: "[[Ashdra.png]]"
---

# Ashdra

```statblock
"name": "Ashdra"
"size": "Medium"
"type": "humanoid"
"subtype": "elf"
"alignment": "Chaotic Evil"
"ac": !!int "10"
"hp": !!int "4"
"hit_dice": "1d8"
"stats":
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
- !!int "10"
"speed": "walk 30 ft."
"skillsaves":
  "Perception": !!int "2"
"senses": "darkvision 120 ft., passive Perception 10"
"languages": "any one language (usually Common), Elvish"
"cr": "0"
"traits":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The ashdra's innate spellcasting ability is Charisma (spell save DC 10).\
    \ The ashdra can innately cast the following spells, requiring no material components:\n\
    \nAt will: [dancing lights](/compendium/spells/dancing-lights.md)\n\n1/day\
    \ each: [darkness](/compendium/spells/darkness.md), [faerie fire](/compendium/spells/faerie-fire.md)"
  "name": "innate"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "The ashdra has advantage on saving throws against being charmed, and magic\
    \ can't put the ashdra to sleep."
  "name": "Fey Ancestry"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "While in sunlight, the ashdra has disadvantage on attack rolls, as well\
    \ as on Wisdom ([Perception](/rules/skills.md#Perception)) checks that rely on\
    \ sight."
  "name": "Sunlight Sensitivity"
"actions":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +2 to hit, reach 5 ft., one target. Hit: 2 (1d4)\
    \ bludgeoning damage."
  "name": "Club"
"source":
- "TftYP"
"image": "[[Ashdra.png]]"
```
^statblock

*Source: Tales from the Yawning Portal p. 158*

## Environment

arctic, desert, coastal, grassland, hill, urban, forest