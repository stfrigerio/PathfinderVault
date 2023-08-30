---

Level: 4
Type:
- Mindless
- Troop
- Undead
- Zombie
Alignment: Neutral Evil
Size: Gargantuan

tag: 👹

---

> [!infobox]+
> #  `= this.file.name`
> ![[Zombie_laborer.jpg]]
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
name: "Shambler Troop"
level: "Creature 4"
alignment: "NE"
size: "Gargantuan"
trait_03: "Mindless"
trait_04: "Troop"
trait_05: "Undead"
trait_06: "Zombie"
modifier: 7
perception:
  - name: "Perception"
    desc: "Perception +7; __darkvision__;"
skills:
  - name: "Skills"
    desc: ""
abilityMods: [5, 0, 3, -5, 1, -2]

abilities_top:
  - name: "Slow"
    desc: "  A shambler troop is permanently [[slowed|slowed 1]] and can't use reactions."
abilities_mid:
  - name: "Troop Defenses"
    desc: " ([[page 306]]); "
abilities_bot:
  - name: "Shambling Onslaught"
    desc: "⬻ to ⬺ __Frequency__ once per round  __Effect__  The shamblers lash out at any enemies in their squares or within 5 feet (DC 18 basic Reflex save). The damage depends on the number of actions. ⬻ 2d6+5 (2d6+5) bludgeoning damage ⬺ 2d6+9 (2d6+9) bludgeoning damage."
  - name: "Grave Tide"
    desc: "  The shambler troop is less organized than most troops. It can move into other creatures' spaces, and other creatures can move into its spaces. Its spaces are [[terrain|difficult terrain]] to other creatures."
  - name: "Form Up"
    desc: "⬻ "
  - name: "Troop Movement"
    desc: "  Whenever a troop [[Stride|Strides]], it first Forms Up as a free action to condense into a 20-foot-by –20-foot area (minus any missing squares), then moves up to its Speed. This works just like a Gargantuan creature moving; for instance, if any square of the troop enters [[terrain|difficult terrain]], the extra movement cost applies to the whole troop."

speed: 20 feet; troop movement;

ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__: +11 (1d20+11); __Ref__: +8 (1d20+8); __Will__: +9 (1d20+9);"
hp: 90
health:
  - name: HP
    desc: "90;  __Weaknesses__ area ;"


attacks:

sourcebook: "_Bestiary 3_, page 302."
```

```encounter-table
name: Shambler Troop
creatures:
  - 1: Shambler Troop
```

````


