---

Level: None
Type: Human, Humanoid
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
source: "GMG"
name: "Apothecary"
level: "Creature -1"
alignment: "N"
size: "Medium"
trait_03: "Human"
trait_04: "Humanoid"
modifier: 5
perception:
  - name: "Perception"
    desc: "Perception +5;"
languages: "Common; "
skills:
  - name: "Skills"
    desc: "__Crafting__: +5 (1d20+5), (Crafting: +8 (1d20+8) for alchemy and medication); __Medicine__: +10 (1d20+10); __Nature__: +8 (1d20+8); "
abilityMods: [0, 1, 1, 3, 3, 1]

abilities_top:
  - name: "Medical Wisdom"
    desc: "  The apothecary can identify the effect of any alchemical composition or medical ingredient using only their senses. This typically takes 1 minute."

speed: 25 feet

ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__: +8 (1d20+8); __Ref__: +3 (1d20+3); __Will__: +5 (1d20+5);"
hp: 9
health:
  - name: HP
    desc: "9; "


attacks:
  - name: Melee
    desc: "⬻ stone pestle +4 __Damage__ 1d6 (1d6) bludgeoning"
  - name: Melee
    desc: "⬻ fist +5 ([[agile]], [[nonlethal]]); __Damage__ 1d4 (1d4) bludgeoning"
  - name: Ranged
    desc: "⬻ acid flask +5 ([[range increment|range increment 20 feet]], [[splash]]); __Damage__ 1 acid plus 1d6 (1d6) [[persistent damage|persistent acid]] and 1 splash acid"

sourcebook: "_Gamemastery Guide_, page 221."
```

```encounter-table
name: Apothecary
creatures:
  - 1: Apothecary
```

````


