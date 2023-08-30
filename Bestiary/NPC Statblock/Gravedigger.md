---

Level: 1
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
name: "Gravedigger"
level: "Creature 1"
alignment: "N"
size: "Medium"
trait_03: "Human"
trait_04: "Humanoid"
modifier: 6
perception:
  - name: "Perception"
    desc: "Perception +6;"
languages: "Common; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +7 (1d20+7); __Religion__: +4 (1d20+4); __Stealth__: +4 (1d20+4); __Graveyard lore__: +4 (1d20+4); "
abilityMods: [4, 1, 3, 0, 2, 0]

abilities_bot:
  - name: "Light in the Dark"
    desc: "⬺ ([[concentrate]], [[divine]], [[manipulate]]); __Requirements__ The gravedigger holds a bull's-eye lantern in one hand and their religious symbol in the other, and the lantern contains oil  __Effect__  The gravedigger recites a brief chant to ignite their lantern with positive energy. Each undead creature in a 15-foot line takes 3d6 (3d6) positive damage (DC 14 basic Fortitude save). This action uses all remaining oil in the bull's-eye lantern."

speed: 25 feet

ac: 15
armorclass:
  - name: AC
    desc: "15; __Fort__: +8 (1d20+8); __Ref__: +4 (1d20+4); __Will__: +7 (1d20+7);"
hp: 22
health:
  - name: HP
    desc: "22; "


attacks:
  - name: Melee
    desc: "⬻ shovel +9 __Damage__ 1d4+4 (1d4+4) bludgeoning"

sourcebook: "_Gamemastery Guide_, page 224."
```

```encounter-table
name: Gravedigger
creatures:
  - 1: Gravedigger
```

````


