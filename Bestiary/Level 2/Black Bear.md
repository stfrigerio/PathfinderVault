---




Level: 2
Type: Animal
Alignment: Neutral
Size: Large




tag: 👹

---

> [!infobox]+
> #  `= this.file.name`
> ![[Mishka_the_bear.png]]
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
name: "Black Bear"
level: "Creature 2"
alignment: "N"
size: "Large"
trait_03: "Animal"
modifier: 8
perception:
  - name: "Perception"
    desc: "Perception +8; __low-light vision__, __imprecise scent 30__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +9 (1d20+9); __Survival__: +7 (1d20+7); "
abilityMods: [3, 2, 3, -4, 1, -2]

abilities_bot:
  - name: "Mauler"
    desc: "  The black bear gains +1 circumstance bonus to damage rolls against creatures it has [[grabbed|grabbed]]."

speed: 35 feet

ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__: +11 (1d20+11); __Ref__: +8 (1d20+8); __Will__: +5 (1d20+5);"
hp: 32
health:
  - name: HP
    desc: "32; "


attacks:
  - name: Melee
    desc: "⬻ jaws +9 __Damage__ 1d8+5 (1d8+5) piercing"
  - name: Melee
    desc: "⬻ claw +9 ([[agile]]); __Damage__ 1d6+5 (1d6+5) slashing plus Grab"

sourcebook: "_Bestiary 2_, page 36."
```

```encounter-table
name: Black Bear
creatures:
  - 1: Black Bear
```

````


