---

Level: 3
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
name: "Bosun"
level: "Creature 3"
alignment: "N"
size: "Medium"
trait_03: "Human"
trait_04: "Humanoid"
modifier: 8
perception:
  - name: "Perception"
    desc: "Perception +8;"
languages: "Common; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +9 (1d20+9); __Athletics__: +9 (1d20+9); __Intimidation__: +9 (1d20+9); __Sailing lore__: +11 (1d20+11); "
abilityMods: [2, 4, 1, 0, 1, 2]

abilities_bot:
  - name: "Bosun's Command"
    desc: "⬻ ([[auditory]], [[concentrate]], [[emotion]], [[linguistic]], [[mental]]); __Frequency__ once per round  __Effect__  The bosun orders an ally to attack or to get in position. Until the end of the ally's next turn, they gain the bosun's choice of a +2 status bonus to attack rolls or a +10-foot status bonus to their Speeds."
  - name: "Pike and Strike"
    desc: "⬺  The bosun [[Strike|Strikes]] with their naval pike. If this [[Strike]] hits, the bosun can either move the target 5 feet within the pike's reach or make a fist [[Strike]] against the target without increasing their multiple attack penalty until after the fist [[Strike]]."
abilities_top:
  - name: Items
    desc: "dagger, naval pike (functions as spear);"

speed: 25 feet

ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__: +6 (1d20+6); __Ref__: +11 (1d20+11); __Will__: +8 (1d20+8);"
hp: 45
health:
  - name: HP
    desc: "45; "


attacks:
  - name: Melee
    desc: "⬻ fist +13 ([[agile]], [[nonlethal]]); __Damage__ 1d6+5 (1d6+5) bludgeoning"
  - name: Melee
    desc: "⬻ naval pike +11 __Damage__ 1d6+5 (1d6+5) piercing"
  - name: Melee
    desc: "⬻ dagger +13 ([[agile]], [[versatile|versatile s]]); __Damage__ 1d4+5 (1d4+5) piercing"
  - name: Ranged
    desc: "⬻ naval pike +13 ([[thrown|thrown 20 feet]]); __Damage__ 1d6+5 (1d6+5) piercing"

sourcebook: "_Gamemastery Guide_, page 243."
```

```encounter-table
name: Bosun
creatures:
  - 1: Bosun
```

````


