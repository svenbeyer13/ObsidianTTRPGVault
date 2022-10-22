---
cssclass: json5e-monster
tags:
- compendium/src/gos
- monster/size/medium
- monster/type/undead
- monster/environment/underdark
aliases: ["Yalaga Maladwyn"]
statblock: true
"name": "Yalaga Maladwyn"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "16"
"hp": !!int "71"
"hit_dice": "13d8 + 13"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "13"
- !!int "17"
- !!int "18"
"speed": "walk 30 ft."
"saves":
  "Charisma": !!int "7"
  "Wisdom": !!int "6"
  "Constitution": !!int "4"
"skillsaves":
  "Stealth": !!int "5"
  "Religion": !!int "4"
  "Insight": !!int "6"
  "Perception": !!int "6"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Elvish, Undercommon"
"cr": "8"
"traits":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Yalaga's spellcasting ability is Charisma (spell save DC 15). She can innately\
    \ cast the following spells, requiring no material components:\n\nAt will:\
    \ [dancing lights](/compendium/spells/dancing-lights.md)\n\n1/day each: [darkness](/compendium/spells/darkness.md),\
    \ [faerie fire](/compendium/spells/faerie-fire.md), [levitate](/compendium/spells/levitate.md)\
    \ (self only)"
  "name": "innate"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Yalaga is a 10th-level spellcaster. Her spellcasting ability is Wisdom\
    \ (save DC 14, +6 to hit with spell attacks). Yalaga has the following cleric\
    \ spells prepared:\n\nCantrips (at will): [guidance](/compendium/spells/guidance.md),\
    \ [poison spray](/compendium/spells/poison-spray.md), [resistance](/compendium/spells/resistance.md),\
    \ [spare the dying](/compendium/spells/spare-the-dying.md), [thaumaturgy](/compendium/spells/thaumaturgy.md)\n\
    \n1st level (4 1st-level slots): [animal friendship](/compendium/spells/animal-friendship.md),\
    \ [cure wounds](/compendium/spells/cure-wounds.md), [detect poison and disease](/compendium/spells/detect-poison-and-disease.md),\
    \ [ray of sickness](/compendium/spells/ray-of-sickness.md)\n\n2nd level (3 2nd-level\
    \ slots): [lesser restoration](/compendium/spells/lesser-restoration.md), [protection\
    \ from poison](/compendium/spells/protection-from-poison.md), [web](/compendium/spells/web.md)\n\
    \n3rd level (3 3rd-level slots): [conjure animals](/compendium/spells/conjure-animals.md)\
    \ (2 giant spiders), [dispel magic](/compendium/spells/dispel-magic.md)\n\n4th\
    \ level (3 4th-level slots): [divination](/compendium/spells/divination.md),\
    \ [freedom of movement](/compendium/spells/freedom-of-movement.md)\n\n5th level\
    \ (2 5th-level slots): [insect plague](/compendium/spells/insect-plague.md),\
    \ [mass cure wounds](/compendium/spells/mass-cure-wounds.md)"
  "name": "spells"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "While in sunlight, Yalaga has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](/rules/skills.md#Perception)) checks that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Yalaga makes two scourge attacks."
  "name": "Multiattack"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage plus 17 (5d6) poison damage."
  "name": "Scourge"
"source":
- "GoS"
name: Yalaga Maladwyn
image: "[[Yalaga Maladwyn.png]]"
---

# Yalaga Maladwyn

```statblock
"name": "Yalaga Maladwyn"
"size": "Medium"
"type": "undead"
"alignment": "Neutral Evil"
"ac": !!int "16"
"hp": !!int "71"
"hit_dice": "13d8 + 13"
"stats":
- !!int "10"
- !!int "14"
- !!int "12"
- !!int "13"
- !!int "17"
- !!int "18"
"speed": "walk 30 ft."
"saves":
  "Charisma": !!int "7"
  "Wisdom": !!int "6"
  "Constitution": !!int "4"
"skillsaves":
  "Stealth": !!int "5"
  "Religion": !!int "4"
  "Insight": !!int "6"
  "Perception": !!int "6"
"senses": "darkvision 120 ft., passive Perception 16"
"languages": "Elvish, Undercommon"
"cr": "8"
"traits":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Yalaga's spellcasting ability is Charisma (spell save DC 15). She can innately\
    \ cast the following spells, requiring no material components:\n\nAt will:\
    \ [dancing lights](/compendium/spells/dancing-lights.md)\n\n1/day each: [darkness](/compendium/spells/darkness.md),\
    \ [faerie fire](/compendium/spells/faerie-fire.md), [levitate](/compendium/spells/levitate.md)\
    \ (self only)"
  "name": "innate"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Yalaga is a 10th-level spellcaster. Her spellcasting ability is Wisdom\
    \ (save DC 14, +6 to hit with spell attacks). Yalaga has the following cleric\
    \ spells prepared:\n\nCantrips (at will): [guidance](/compendium/spells/guidance.md),\
    \ [poison spray](/compendium/spells/poison-spray.md), [resistance](/compendium/spells/resistance.md),\
    \ [spare the dying](/compendium/spells/spare-the-dying.md), [thaumaturgy](/compendium/spells/thaumaturgy.md)\n\
    \n1st level (4 1st-level slots): [animal friendship](/compendium/spells/animal-friendship.md),\
    \ [cure wounds](/compendium/spells/cure-wounds.md), [detect poison and disease](/compendium/spells/detect-poison-and-disease.md),\
    \ [ray of sickness](/compendium/spells/ray-of-sickness.md)\n\n2nd level (3 2nd-level\
    \ slots): [lesser restoration](/compendium/spells/lesser-restoration.md), [protection\
    \ from poison](/compendium/spells/protection-from-poison.md), [web](/compendium/spells/web.md)\n\
    \n3rd level (3 3rd-level slots): [conjure animals](/compendium/spells/conjure-animals.md)\
    \ (2 giant spiders), [dispel magic](/compendium/spells/dispel-magic.md)\n\n4th\
    \ level (3 4th-level slots): [divination](/compendium/spells/divination.md),\
    \ [freedom of movement](/compendium/spells/freedom-of-movement.md)\n\n5th level\
    \ (2 5th-level slots): [insect plague](/compendium/spells/insect-plague.md),\
    \ [mass cure wounds](/compendium/spells/mass-cure-wounds.md)"
  "name": "spells"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "While in sunlight, Yalaga has disadvantage on attack rolls, as well as\
    \ on Wisdom ([Perception](/rules/skills.md#Perception)) checks that rely on sight."
  "name": "Sunlight Sensitivity"
"actions":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Yalaga makes two scourge attacks."
  "name": "Multiattack"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 5 (1d6\
    \ + 2) piercing damage plus 17 (5d6) poison damage."
  "name": "Scourge"
"source":
- "GoS"
"image": "[[Yalaga Maladwyn.png]]"
```
^statblock

*Source: Ghosts of Saltmarsh p. 226*

## Environment

underdark