---

Level: 8
Type:
- Animal
- Dinosaur
Alignment: Neutral
Size: Huge

tag: 👹

---

> [!infobox]+
> #  `= this.file.name`
> ![[Ceratopsid.jpg]]
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
name: "Triceratops"
level: "Creature 8"
alignment: "N"
size: "Huge"
trait_03: "Animal"
trait_04: "Dinosaur"
modifier: 16
perception:
  - name: "Perception"
    desc: "Perception +16; __low-light vision__, __imprecise scent 30__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +21 (1d20+21); "
abilityMods: [7, 0, 4, -4, 2, -1]

abilities_mid:
  - name: "Frill Defense"
    desc: "⬲ __Trigger__ The rider is targeted with an attack. __Effect__  Requirements A creature must be mounted on the triceratops. The triceratops intercepts the attack with its bony frill. The rider gains a +2 circumstance bonus to its AC against the triggering attack."
abilities_bot:
  - name: "Lumbering Charge"
    desc: "⬻  The triceratops [[Stride|Strides]] up to 10 feet and then makes a [[Strike]]."
  - name: "Trample"
    desc: "⬽  Large or smaller, foot, DC 26."
  - name: "Vicious Gore"
    desc: "  A triceratops deals 2d6 (2d6) extra [[persistent damage|persistent bleed damage]] to [[prone|prone]] targets it hits with its horns."

speed: 30 feet

ac: 26
armorclass:
  - name: AC
    desc: "26; __Fort__: +18 (1d20+18); __Ref__: +12 (1d20+12); __Will__: +14 (1d20+14);"
hp: 140
health:
  - name: HP
    desc: "140; "


attacks:
  - name: Melee
    desc: "⬻ horns +19 ([[reach|reach 15 feet]]); __Damage__ 2d8+9 (2d8+9) piercing plus Knockdown"
  - name: Melee
    desc: "⬻ foot +19 ([[reach|reach 10 feet]]); __Damage__ 2d6+9 (2d6+9) bludgeoning"

sourcebook: "_Bestiary_, page 99."
```

```encounter-table
name: Triceratops
creatures:
  - 1: Triceratops
```

````


