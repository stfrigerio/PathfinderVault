---

Level: 0
Type: Animal
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
source: "B3"
name: "Ringhorn Ram"
level: "Creature 0"
alignment: "N"
size: "Medium"
trait_03: "Animal"
modifier: 6
perception:
  - name: "Perception"
    desc: "Perception +6; __low-light vision__;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +4 (1d20+4); __Athletics__: +5 (1d20+5); __Stealth__: +4 (1d20+4); __Survival__: +6 (1d20+6); "
abilityMods: [3, 2, 2, -5, 2, 0]

abilities_bot:
  - name: "Nimble Stride"
    desc: "  Rams ignore [[terrain|difficult terrain]] caused by narrow ledges."
  - name: "Ram Charge"
    desc: "⬺  The ram [[Stride|Strides]] twice in a straight line and then makes a horn [[Strike]] with a +1 circumstance bonus to its attack roll."

speed: 30 feet; nimble stride;

ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__: +6 (1d20+6); __Ref__: +6 (1d20+6); __Will__: +4 (1d20+4);"
hp: 15
health:
  - name: HP
    desc: "15; "


attacks:
  - name: Melee
    desc: "⬻ hoof +7 __Damage__ 1d6+3 (1d6+3) bludgeoning"
  - name: Melee
    desc: "⬻ horn +7 ([[agile]]); __Damage__ 1d4+3 (1d4+3) piercing"

sourcebook: "_Bestiary 3_, page 212."
```

```encounter-table
name: Ringhorn Ram
creatures:
  - 1: Ringhorn Ram
```

````


