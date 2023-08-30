---


Level: 1
Type: Animal
Alignment: Neutral
Size: Medium


tag: 👹

---

> [!infobox]+
> #  `= this.file.name`
> ![[Appleslayer.jpg]]
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
name: "Riding Dog"
level: "Creature 1"
alignment: "N"
size: "Medium"
trait_03: "Animal"
modifier: 7
perception:
  - name: "Perception"
    desc: "Perception +7; __low-light vision__, __imprecise scent 30__;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +5 (1d20+5); __Athletics__: +7 (1d20+7); __Survival__: +5 (1d20+5); "
abilityMods: [2, 2, 2, -4, 2, -1]

abilities_mid:
  - name: "Buck"
    desc: "⬲  DC 17."
abilities_bot:
  - name: "Pack Attack"
    desc: "  The dog's [[Strike|Strikes]] deal 1d4 (1d4) extra damage to creatures within the reach of at least two of the dog's allies."

speed: 35 feet

ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__: +7 (1d20+7); __Ref__: +5 (1d20+5); __Will__: +5 (1d20+5);"
hp: 20
health:
  - name: HP
    desc: "20; "


attacks:

sourcebook: "_Bestiary_, page 102."
```

```encounter-table
name: Riding Dog
creatures:
  - 1: Riding Dog
```

````


