---

Level: 3
Type: Human, Humanoid
Alignment: Neutral
Size: Medium

tag: 👹

---

> [!infobox]+
> #  `= this.file.name`
> ![[image.png|cover hsmall]]
> ##### Stats
> Type | Stat |
> :---:|:---:|
> **Level** | `= this.Level` |
> **Type** | `= this.Type` |
> **Alignment** | `= this.Alignment` |
> **Size** | `= this.Size` |



````ad-info
title: Statblock

```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "GMG"
name: "Smith"
level: "Creature 3"
alignment: "N"
size: "Medium"
trait_03: "Human"
trait_04: "Humanoid"
modifier: 5
perception:
  - name: "Perception"
    desc: "Perception +5;"
languages: "Common; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +8 (1d20+8); __Crafting__: +15 (1d20+15); __Diplomacy__: +5 (1d20+5); __Society__: +8 (1d20+8); __Smithy lore__: +15 (1d20+15); "
abilityMods: [3, 1, 2, 3, 0, 0]

abilities_bot:
  - name: "Smith's Fury"
    desc: "  The smith deals an additional 1d6 (1d6) damage when they hit with a weapon they created."
abilities_top:
  - name: Items
    desc: "artisan's tools, leather apron (functions as padded armor), light hammer;"

speed: 25 feet

ac: 17
armorclass:
  - name: AC
    desc: "17; __Fort__: +9 (1d20+9); __Ref__: +8 (1d20+8); __Will__: +5 (1d20+5);"
hp: 50
health:
  - name: HP
    desc: "50; "


attacks:
  - name: Melee
    desc: "⬻ light hammer +10 ([[agile]]); __Damage__ 1d6+3 (1d6+3) bludgeoning plus smith's fury"
  - name: Ranged
    desc: "⬻ light hammer +8 ([[agile]], [[thrown|thrown 20 feet]]); __Damage__ 1d6+3 (1d6+3) bludgeoning plus smith's fury"

sourcebook: "_Gamemastery Guide_, page 245."
```

```encounter-table
name: Smith
creatures:
  - 1: Smith
```

````


