---




Level: 2
Type: Animal
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
source: "B3"
name: "Giant Flying Squirrel"
level: "Creature 2"
alignment: "N"
size: "Small"
trait_03: "Animal"
modifier: 8
perception:
  - name: "Perception"
    desc: "Perception +8; __low-light vision__, __imprecise scent 30__;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +8 (1d20+8); __Athletics__: +6 (1d20+6); __Stealth__: +8 (1d20+8); "
abilityMods: [2, 4, 3, -4, 2, 0]

abilities_bot:
  - name: "Glide"
    desc: "⬻  The giant flying squirrel glides through the air. It moves up to 40 feet horizontally and descends an equal distance. If it's still in the air and takes an action other than Gliding or ends its turn, it falls."

speed: 25 feet, climb 25 feet

ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__: +7 (1d20+7); __Ref__: +10 (1d20+10); __Will__: +6 (1d20+6);"
hp: 30
health:
  - name: HP
    desc: "30; "


attacks:
  - name: Melee
    desc: "⬻ jaws +11 __Damage__ 1d8+4 (1d8+4) piercing"
  - name: Melee
    desc: "⬻ claw +11 ([[agile]], [[finesse]]); __Damage__ 1d6+4 (1d6+4) slashing"

sourcebook: "_Bestiary 3_, page 257."
```

```encounter-table
name: Giant Flying Squirrel
creatures:
  - 1: Giant Flying Squirrel
```

````


