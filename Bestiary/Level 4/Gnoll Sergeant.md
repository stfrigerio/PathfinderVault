---

Level: 4
Type:
- Gnoll
- Humanoid
Alignment: Chaotic Evil
Size: Medium

tag: 👹

---

> [!infobox]+
> #  `= this.file.name`
> ![[Gnoll.jpg]]
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
source: "B1"
name: "Gnoll Sergeant"
level: "Creature 4"
alignment: "CE"
size: "Medium"
trait_03: "Gnoll"
trait_04: "Humanoid"
modifier: 10
perception:
  - name: "Perception"
    desc: "Perception +10; __darkvision__;"
languages: "Common, Gnoll; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +13 (1d20+13); __Intimidation__: +9 (1d20+9); __Stealth__: +11 (1d20+11); __Survival__: +10 (1d20+10); "
abilityMods: [4, 2, 2, 0, 1, 0]

abilities_mid:
  - name: "Attack of Opportunity"
    desc: "⬲ "
abilities_top:
  - name: Items
    desc: "composite shortbow (20 arrows), hide armor, scimitar;"
abilities_bot:
  - name: "Bark Orders"
    desc: "⬻ ([[auditory]], [[linguistic]]);  The gnoll sergeant commands its allies to reposition. Any allies who hear and understand this order can use a reaction to [[Step]]."
  - name: "Pack Attack"
    desc: "  A gnoll hunter deals 1d4 (1d4) extra damage to any creature that's within reach of at least two of the gnoll hunter's allies."
  - name: "Rugged Travel"
    desc: "  A gnoll ignores the first square of [[terrain|difficult terrain]] it moves into each time it [[Step|Steps]] or [[Stride|Strides]]."

speed: 25 feet

ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__: +12 (1d20+12); __Ref__: +10 (1d20+10); __Will__: +8 (1d20+8);"
hp: 60
health:
  - name: HP
    desc: "60; "


attacks:
  - name: Melee
    desc: "⬻ scimitar +14 ([[forceful]], [[sweep]]); __Damage__ 1d6+7 (1d6+7) slashing"
  - name: Melee
    desc: "⬻ jaws +14 ([[agile]]); __Damage__ 1d6+7 (1d6+7) piercing"
  - name: Ranged
    desc: "⬻ composite shortbow +12 ([[deadly|deadly 1d10]], [[propulsive]], [[range increment|range increment 60 feet]], [[reload|reload 0]]); __Damage__ 1d6+4 (1d6+4) piercing"

sourcebook: "_Bestiary_, page 179."
```

```encounter-table
name: Gnoll Sergeant
creatures:
  - 1: Gnoll Sergeant
```

````


