---

Level: 4
Type:
- Animal
- Dinosaur
Alignment: Neutral
Size: Huge

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
name: "Hadrosaurid"
level: "Creature 4"
alignment: "N"
size: "Huge"
trait_03: "Animal"
trait_04: "Dinosaur"
modifier: 13
perception:
  - name: "Perception"
    desc: "Perception +13; __low-light vision__, __imprecise scent 30__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +12 (1d20+12); __Stealth__: +10 (1d20+10); "
abilityMods: [6, 2, 3, -4, 1, 0]

abilities_bot:
  - name: "Sprint"
    desc: "⬺ __Frequency__ once per minute  __Effect__  The hadrosaurid [[Stride|Strides]] twice. It has a +20-foot circumstance bonus to its Speed during these [[Stride|Strides]]."
  - name: "Trample"
    desc: "⬽  Large or smaller, foot, DC 21."

speed: 30 feet

ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__: +12 (1d20+12); __Ref__: +10 (1d20+10); __Will__: +11 (1d20+11);"
hp: 60
health:
  - name: HP
    desc: "60; "


attacks:

sourcebook: "_Bestiary 2_, page 82."
```

```encounter-table
name: Hadrosaurid
creatures:
  - 1: Hadrosaurid
```

````


