---

Level: 0
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
name: "Dockhand"
level: "Creature 0"
alignment: "N"
size: "Medium"
trait_03: "Human"
trait_04: "Humanoid"
modifier: 3
perception:
  - name: "Perception"
    desc: "Perception +3;"
languages: "Common; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +3 (1d20+3); __Athletics__: +5 (1d20+5); __Intimidation__: +3 (1d20+3); __Labor lore__: +4 (1d20+4); "
abilityMods: [3, 1, 3, 0, 1, 1]

abilities_bot:
  - name: "Heft Crate"
    desc: "⬺ ([[manipulate]]); __Requirements__ The dockhand is adjacent to a crate  __Effect__  The dockhand picks up a crate and heaves it up to 15 feet. Upon landing, the crate breaks open in a 5-foot burst. Each creature within the area takes 2d6 (2d6) bludgeoning damage (DC 13 basic Reflex save), and the area becomes [[terrain|difficult terrain]] until cleared."
  - name: "Swig"
    desc: "⬺ ([[manipulate]]);  The dockhand Interacts to either draw a bottle of alcohol or pick up a nearby unattended bottle of alcohol and drink the whole thing. For 1 minute, the dockhand gains a +2 item bonus to melee damage rolls and saving throws against fear, but they become [[clumsy|clumsy 1]]."
abilities_top:
  - name: Items
    desc: "empty bottle (3), leather armor, whiskey (1 bottle);"

speed: 25 feet

ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__: +7 (1d20+7); __Ref__: +5 (1d20+5); __Will__: +3 (1d20+3);"
hp: 20
health:
  - name: HP
    desc: "20; "


attacks:
  - name: Melee
    desc: "⬻ fist +7 ([[agile]], [[nonlethal]]); __Damage__ 1d4+3 (1d4+3) bludgeoning"
  - name: Ranged
    desc: "⬻ bottle +5 ([[agile]], [[thrown|thrown 20 feet]]); __Damage__ 1d6+3 (1d6+3) bludgeoning"

sourcebook: "_Gamemastery Guide_, page 224."
```

```encounter-table
name: Dockhand
creatures:
  - 1: Dockhand
```

````


