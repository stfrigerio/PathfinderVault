---

Level: 6
Type: Animal
Alignment: Neutral
Size: Large

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
source: "B2"
name: "Woolly Rhinoceros"
level: "Creature 6"
alignment: "N"
size: "Large"
trait_03: "Animal"
modifier: 11
perception:
  - name: "Perception"
    desc: "Perception +11; __imprecise scent 30__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +16 (1d20+16); __Survival__: +13 (1d20+13); "
abilityMods: [6, 1, 5, -4, 3, -1]

abilities_mid:
  - name: "Cold Adaptation"
    desc: "  The woolly rhinoceros treats environmental [[cold]] effects as if they were one step less extreme."
  - name: "Ferocity"
    desc: "⬲ "
abilities_bot:
  - name: "Rhinoceros Charge"
    desc: "⬺  As rhinoceros, except 3d12+6 (3d12+6) damage and DC 24."
  - name: "Trample"
    desc: "⬽  Medium or smaller, foot, DC 21."

speed: 35 feet

ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__: +17 (1d20+17); __Ref__: +11 (1d20+11); __Will__: +15 (1d20+15);"
hp: 100
health:
  - name: HP
    desc: "100; "


attacks:
  - name: Melee
    desc: "⬻ horn +16 ([[reach|reach 10 feet]]); __Damage__ 2d12+6 (2d12+6) piercing"
  - name: Melee
    desc: "⬻ foot +16 __Damage__ 2d8+6 (2d8+6) bludgeoning"

sourcebook: "_Bestiary 2_, page 228."
```

```encounter-table
name: Woolly Rhinoceros
creatures:
  - 1: Woolly Rhinoceros
```

````


