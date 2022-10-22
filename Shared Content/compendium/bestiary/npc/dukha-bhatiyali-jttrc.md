---
cssclass: json5e-monster
tags:
- compendium/src/jttrc
- monster/size/medium
- monster/type/humanoid/human
- monster/type/humanoid/shapechanger
- monster/environment/grassland
- monster/environment/forest
- monster/environment/desert
aliases: ["Dukha Bhatiyali"]
statblock: true
"name": "Dukha Bhatiyali"
"size": "Medium"
"type": "humanoid"
"subtype": "human, shapechanger"
"alignment": "Neutral"
"ac": !!int "12"
"hp": !!int "120"
"hit_dice": "16d8 + 48"
"stats":
- !!int "17"
- !!int "15"
- !!int "16"
- !!int "10"
- !!int "13"
- !!int "11"
"speed": "walk 30 ft. (40 ft. in tiger form)"
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "5"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common (can't speak in tiger form)"
"cr": "4"
"traits":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Dukha can use its action to polymorph into a tiger-humanoid hybrid or into\
    \ a tiger, or back into its true form, which is humanoid. Its statistics, other\
    \ than its size, are the same in each form. Any equipment it is wearing or carrying\
    \ isn't transformed. It reverts to its true form if it dies."
  "name": "Shapechanger"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Dukha has advantage on Wisdom ([Perception](/rules/skills.md#Perception))\
    \ checks that rely on hearing or smell."
  "name": "Keen Hearing and Smell"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "If Dukha moves at least 15 feet straight toward a creature and then hits\
    \ it with a claw attack on the same turn, that target must succeed on a DC 14\
    \ Strength saving throw or be knocked [prone](/rules/conditions.md#prone). If\
    \ the target is [prone](/rules/conditions.md#prone), Dukha can make one bite attack\
    \ against it as a bonus action."
  "name": "Pounce (Tiger or Hybrid Form Only)"
"actions":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "In humanoid form, Dukha makes two scimitar attacks or two longbow attacks.\
    \ In hybrid form, it can attack like a humanoid or make two claw attacks."
  "name": "Multiattack (Humanoid or Hybrid Form Only)"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (1d10\
    \ + 3) piercing damage. If the target is a humanoid, it must succeed on a DC 13\
    \ Constitution saving throw or be cursed with weretiger lycanthropy."
  "name": "Bite (Tiger or Hybrid Form Only)"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage."
  "name": "Claw (Tiger or Hybrid Form Only)"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar (Humanoid or Hybrid Form Only)"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage."
  "name": "Longbow (Humanoid or Hybrid Form Only)"
"source":
- "JttRC"
name: Dukha Bhatiyali
image: "[[Dukha Bhatiyali.png]]"
---

# Dukha Bhatiyali

```statblock
"name": "Dukha Bhatiyali"
"size": "Medium"
"type": "humanoid"
"subtype": "human, shapechanger"
"alignment": "Neutral"
"ac": !!int "12"
"hp": !!int "120"
"hit_dice": "16d8 + 48"
"stats":
- !!int "17"
- !!int "15"
- !!int "16"
- !!int "10"
- !!int "13"
- !!int "11"
"speed": "walk 30 ft. (40 ft. in tiger form)"
"skillsaves":
  "Stealth": !!int "4"
  "Perception": !!int "5"
"damage_immunities": "bludgeoning, piercing, slashing from nonmagical attacks that\
  \ aren't silvered"
"senses": "darkvision 60 ft., passive Perception 15"
"languages": "Common (can't speak in tiger form)"
"cr": "4"
"traits":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Dukha can use its action to polymorph into a tiger-humanoid hybrid or into\
    \ a tiger, or back into its true form, which is humanoid. Its statistics, other\
    \ than its size, are the same in each form. Any equipment it is wearing or carrying\
    \ isn't transformed. It reverts to its true form if it dies."
  "name": "Shapechanger"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Dukha has advantage on Wisdom ([Perception](/rules/skills.md#Perception))\
    \ checks that rely on hearing or smell."
  "name": "Keen Hearing and Smell"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "If Dukha moves at least 15 feet straight toward a creature and then hits\
    \ it with a claw attack on the same turn, that target must succeed on a DC 14\
    \ Strength saving throw or be knocked [prone](/rules/conditions.md#prone). If\
    \ the target is [prone](/rules/conditions.md#prone), Dukha can make one bite attack\
    \ against it as a bonus action."
  "name": "Pounce (Tiger or Hybrid Form Only)"
"actions":
- !!dev.ebullient.json5e.qute.Trait
  "desc": "In humanoid form, Dukha makes two scimitar attacks or two longbow attacks.\
    \ In hybrid form, it can attack like a humanoid or make two claw attacks."
  "name": "Multiattack (Humanoid or Hybrid Form Only)"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 8 (1d10\
    \ + 3) piercing damage. If the target is a humanoid, it must succeed on a DC 13\
    \ Constitution saving throw or be cursed with weretiger lycanthropy."
  "name": "Bite (Tiger or Hybrid Form Only)"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 7 (1d8\
    \ + 3) slashing damage."
  "name": "Claw (Tiger or Hybrid Form Only)"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Melee Weapon Attack: +5 to hit, reach 5 ft., one target. Hit: 6 (1d6\
    \ + 3) slashing damage."
  "name": "Scimitar (Humanoid or Hybrid Form Only)"
- !!dev.ebullient.json5e.qute.Trait
  "desc": "Ranged Weapon Attack: +4 to hit, range 150/600 ft., one target. Hit:\
    \ 6 (1d8 + 2) piercing damage."
  "name": "Longbow (Humanoid or Hybrid Form Only)"
"source":
- "JttRC"
"image": "[[Dukha Bhatiyali.png]]"
```
^statblock

*Source: Journeys through the Radiant Citadel p. 210*

## Environment

grassland, forest, desert