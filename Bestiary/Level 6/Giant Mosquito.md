---

Level: 6
Type: Animal
Alignment: Neutral
Size: Medium

tag: 👹

---

> [!infobox]+
> #  `= this.file.name`
> ![[Ghlaunder_holy_symbol.jpg]]
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
name: "Giant Mosquito"
level: "Creature 6"
alignment: "N"
size: "Medium"
trait_03: "Animal"
modifier: 17
perception:
  - name: "Perception"
    desc: "Perception +17; __darkvision__, __imprecise scent 60__;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +13 (1d20+13); __Stealth__: +13 (1d20+13); "
abilityMods: [4, 5, 2, -5, 2, -5]

abilities_bot:
  - name: "Blood Drain"
    desc: "⬻ __Requirements__ The giant mosquito has a creature [[grabbed|grabbed]]  __Effect__  The giant mosquito uses its proboscis to drain blood from the [[grabbed|grabbed]] creature. This deals 3d6 (3d6) damage, and the giant mosquito gains temporary Hit Points equal to the damage dealt. A creature that has its blood [[drained|drained]] by a giant mosquito is [[drained|drained 1]] until it receives healing of any kind or amount."
  - name: "Septic Malaria"
    desc: " ([[disease]]);  __Saving Throw__ DC 24 Fortitude. __Stage 1__ [[sickened|sickened 1]] (1 day) __Stage 2__ [[drained|drained 1]] and [[sickened|sickened 1]] (1 day) __Stage 3__ as stage 2 (1 day) __Stage 4__ [[unconscious|unconscious]]  (1 day)"

speed: 20 feet, fly 50 feet

ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__: +14 (1d20+14); __Ref__: +17 (1d20+17); __Will__: +12 (1d20+12);"
hp: 80
health:
  - name: HP
    desc: "80; "


attacks:
  - name: Melee
    desc: "⬻ proboscis +17 ([[finesse]]); __Damage__ 2d10+7 (2d10+7) piercing plus Grab and septic malaria"

sourcebook: "_Bestiary 2_, page 175."
```

```encounter-table
name: Giant Mosquito
creatures:
  - 1: Giant Mosquito
```

````


