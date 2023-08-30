---

Level: 4
Type: Animal
Alignment: Neutral
Size: Large

tag: 👹

---

> [!infobox]+
> #  `= this.file.name`
> ![[Chapel_beetle.jpg]]
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
name: "Giant Stag Beetle"
level: "Creature 4"
alignment: "N"
size: "Large"
trait_03: "Animal"
modifier: 10
perception:
  - name: "Perception"
    desc: "Perception +10; __darkvision__;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +9 (1d20+9); __Athletics__: +13 (1d20+13); "
abilityMods: [5, 1, 5, -5, 2, -1]

abilities_bot:
  - name: "Trample"
    desc: "⬽  Medium or smaller, foot, DC 21."

speed: 20 feet, fly 20 feet

ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__: +13 (1d20+13); __Ref__: +9 (1d20+9); __Will__: +8 (1d20+8);"
hp: 55
health:
  - name: HP
    desc: "55; "


attacks:
  - name: Melee
    desc: "⬻ mandibles +13 __Damage__ 2d8+5 (2d8+5) piercing"
  - name: Melee
    desc: "⬻ foot +11 __Damage__ 1d10+5 (1d10+5) bludgeoning"

sourcebook: "_Bestiary_, page 41."
```

```encounter-table
name: Giant Stag Beetle
creatures:
  - 1: Giant Stag Beetle
```

````


