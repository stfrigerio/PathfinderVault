---


Level: 1
Type:
- Animal
- Aquatic
Alignment: Neutral
Size: Small


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
source: "B1"
name: "Electric Eel"
level: "Creature 1"
alignment: "N"
size: "Small"
trait_03: "Animal"
trait_04: "Aquatic"
modifier: 4
perception:
  - name: "Perception"
    desc: "Perception +4; __low-light vision__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +6 (1d20+6); __Stealth__: +7 (1d20+7); "
abilityMods: [1, 2, 2, -5, 1, -1]

abilities_bot:
  - name: "Stunning Shock"
    desc: " ([[incapacitation]]);  A creature critically hit by the electric eel's tail must attempt a DC 17 Fortitude save.\n__Critical Success__ The creature is unaffected.\n__Success__ The creature is [[stunned|stunned 1]].\n__Failure__ The creature is [[stunned|stunned 2]].\n__Critical Failure__ The creature is [[stunned|stunned 3]]."

speed: 5 feet, swim 30 feet

ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__: +7 (1d20+7); __Ref__: +7 (1d20+7); __Will__: +4 (1d20+4);"
hp: 18
health:
  - name: HP
    desc: "18; "


attacks:
  - name: Melee
    desc: "⬻ jaws +6 __Damage__ 1d6+3 (1d6+3) piercing"
  - name: Melee
    desc: "⬻ tail +6 ([[agile]]); __Damage__ 1d4+1 (1d4+1) bludgeoning plus 1d4 (1d4) electricity and stunning shock"

sourcebook: "_Bestiary_, page 142."
```

```encounter-table
name: Electric Eel
creatures:
  - 1: Electric Eel
```

````


