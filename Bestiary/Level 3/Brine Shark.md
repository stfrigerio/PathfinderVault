---

Level: 3
Type:
- Aquatic
- Elemental
- Water
Alignment: Neutral
Size: Medium

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
name: "Brine Shark"
level: "Creature 3"
alignment: "N"
size: "Medium"
trait_03: "Aquatic"
trait_04: "Elemental"
trait_05: "Water"
modifier: 8
perception:
  - name: "Perception"
    desc: "Perception +8; __darkvision__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +10 (1d20+10); __Stealth__: +11 (1d20+11); __Survival__: +8 (1d20+8); "
abilityMods: [3, 2, 2, -4, 1, 0]

abilities_bot:
  - name: "Deep Plunge"
    desc: "⬻  The brine shark dives straight down into the water, moving up to twice its swim Speed in a straight vertical line. It can use this ability while grabbing a creature."

speed: 15 feet, swim 50 feet

ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__: +9 (1d20+9); __Ref__: +11 (1d20+11); __Will__: +6 (1d20+6);"
hp: 45
health:
  - name: HP
    desc: "45;  __Immunities__ bleed, poison, paralyzed, sleep;"


attacks:
  - name: Melee
    desc: "⬻ jaws +11 __Damage__ 1d12+7 (1d12+7) piercing plus Grab"

sourcebook: "_Bestiary_, page 152."
```

```encounter-table
name: Brine Shark
creatures:
  - 1: Brine Shark
```

````


