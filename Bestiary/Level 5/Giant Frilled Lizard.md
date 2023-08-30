---

Level: 5
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
source: "B1"
name: "Giant Frilled Lizard"
level: "Creature 5"
alignment: "N"
size: "Large"
trait_03: "Animal"
modifier: 11
perception:
  - name: "Perception"
    desc: "Perception +11; __low-light vision__, __imprecise scent 30__;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +10 (1d20+10); __Athletics__: +14 (1d20+14); __Stealth__: +10 (1d20+10); "
abilityMods: [5, 1, 4, -4, 2, 0]

abilities_bot:
  - name: "Intimidating Display"
    desc: "⬺ ([[auditory]], [[emotion]], [[fear]], [[mental]], [[visual]]);  The giant frilled lizard [[Stride|Strides]]. If it ends that [[Stride]] adjacent to at least one other creature, it suddenly displays its colorful neck frills and issues a frightening hiss. Each adjacent creature must succeed at a DC 21 Will save or become [[frightened|frightened 2]] (or [[frightened|frightened 3]] on a critical failure). The creature is then temporarily immune to Intimidating Display for 1 minute."

speed: 30 feet, climb 30 feet

ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__: +13 (1d20+13); __Ref__: +12 (1d20+12); __Will__: +9 (1d20+9);"
hp: 75
health:
  - name: HP
    desc: "75; "


attacks:
  - name: Melee
    desc: "⬻ jaws +16 ([[reach|reach 10 feet]]); __Damage__ 2d8+7 (2d8+7) piercing"
  - name: Melee
    desc: "⬻ tail +16 ([[agile]], [[reach|reach 10 feet]]); __Damage__ 2d6+7 (2d6+7) bludgeoning"

sourcebook: "_Bestiary_, page 229."
```

```encounter-table
name: Giant Frilled Lizard
creatures:
  - 1: Giant Frilled Lizard
```

````


