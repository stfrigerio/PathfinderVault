---

Level: 3
Type:
- Animal
- Aquatic
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
source: "B3"
name: "Trilobite Swarm"
level: "Creature 3"
alignment: "N"
size: "Large"
trait_03: "Animal"
trait_04: "Aquatic"
trait_05: "Swarm"
modifier: 9
perception:
  - name: "Perception"
    desc: "Perception +9; __darkvision__, __imprecise wavesense 60__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +8 (1d20+8); __Stealth__: +9 (1d20+9); __Survival__: +7 (1d20+7); "
abilityMods: [1, 4, 3, -5, 2, 0]

abilities_bot:
  - name: "Clinging Bites"
    desc: "⬻  The trilobites in the swarm latch onto creatures and gnaw at them. Each enemy in the swarm's space takes 2d6 (2d6) slashing damage (DC 18 basic Reflex save)."

speed: swim 25 feet

ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__: +10 (1d20+10); __Ref__: +9 (1d20+9); __Will__: +7 (1d20+7);"
hp: 30
health:
  - name: HP
    desc: "30;  __Immunities__ precision, swarm mind; __Weaknesses__ area damage 5, splash damage 5;"


attacks:

sourcebook: "_Bestiary 3_, page 275."
```

```encounter-table
name: Trilobite Swarm
creatures:
  - 1: Trilobite Swarm
```

````


