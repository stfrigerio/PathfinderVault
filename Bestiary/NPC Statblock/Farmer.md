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
name: "Farmer"
level: "Creature 0"
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
    desc: "__Athletics__: +5 (1d20+5); __Nature__: +4 (1d20+4); __Survival__: +4 (1d20+4); __Farming lore__: +4 (1d20+4); "
abilityMods: [3, 1, 3, 0, 2, 0]

abilities_bot:
  - name: "Pitch Bale"
    desc: "⬻ __Requirements__ The farmer's last action was a successful pitchfork [[Strike]]  __Effect__  The farmer moves the creature they hit with their pitchfork up to 5 feet, and the target falls [[prone|prone]]. The target can attempt a DC 13 Reflex save to avoid falling [[prone|prone]], and avoids being moved altogether on a critical success."
abilities_top:
  - name: Items
    desc: "apple (4), leather armor, pitchfork;"

speed: 25 feet

ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__: +7 (1d20+7); __Ref__: +5 (1d20+5); __Will__: +4 (1d20+4);"
hp: 20
health:
  - name: HP
    desc: "20; "


attacks:
  - name: Melee
    desc: "⬻ pitchfork +6 ([[reach|reach 10 feet]]); __Damage__ 1d6+3 (1d6+3) piercing"
  - name: Ranged
    desc: "⬻ apple +5 ([[agile]], [[nonlethal]], [[thrown|thrown 20 feet]]); __Damage__ 1d4+3 (1d4+3) bludgeoning"

sourcebook: "_Gamemastery Guide_, page 224."
```

```encounter-table
name: Farmer
creatures:
  - 1: Farmer
```

````


