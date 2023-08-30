---

Level: 4
Type:
- Amphibious
- Animal
- Swarm
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
source: "B2"
name: "Brood Leech Swarm"
level: "Creature 4"
alignment: "N"
size: "Large"
trait_03: "Amphibious"
trait_04: "Animal"
trait_05: "Swarm"
modifier: 9
perception:
  - name: "Perception"
    desc: "Perception +9; __[[tremorsense]] 30__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +8 (1d20+8); __Stealth__: +11 (1d20+11); "
abilityMods: [0, 3, 4, -5, 1, -5]

abilities_bot:
  - name: "Blood Draining Bites"
    desc: "⬻  Each enemy in the swarm's space takes 2d6 (2d6) bleed damage and is exposed to brood leech swarm venom."
  - name: "Brood Leech Swarm Venom"
    desc: " ([[poison]]);  __Saving Throw__ DC 21 Fortitude. __Maximum Duration__ 6 rounds __Stage 1__ [[clumsy|clumsy 1]], [[sickened|sickened 1]], and –5-foot status penalty to Speed (1 round) __Stage 2__ [[clumsy|clumsy 1]], [[sickened|sickened 1]], and –10-foot status penalty to Speed (1 round)"

speed: 5 feet, swim 20 feet

ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__: +12 (1d20+12); __Ref__: +11 (1d20+11); __Will__: +9 (1d20+9);"
hp: 40
health:
  - name: HP
    desc: "40;  __Immunities__ precision, swarm mind; __Weaknesses__ area damage 5, salt 5, splash damage 5;"


attacks:

sourcebook: "_Bestiary 2_, page 156."
```

```encounter-table
name: Brood Leech Swarm
creatures:
  - 1: Brood Leech Swarm
```

````


