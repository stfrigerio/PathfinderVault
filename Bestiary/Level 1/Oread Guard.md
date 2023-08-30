---


Level: 1
Type:
- Human
- Humanoid
- Oread
Alignment: Lawful Neutral
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
source: "B2"
name: "Oread Guard"
level: "Creature 1"
alignment: "LN"
size: "Medium"
trait_03: "Human"
trait_04: "Humanoid"
trait_05: "Oread"
modifier: 7
perception:
  - name: "Perception"
    desc: "Perception +7;"
languages: "Common, Terran; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +7 (1d20+7); __Crafting__: +3 (1d20+3); __Medicine__: +5 (1d20+5); __Society__: +3 (1d20+3); __Survival__: +5 (1d20+5); "
abilityMods: [4, 1, 2, 0, 2, 0]

abilities_mid:
  - name: "Attack of Opportunity"
    desc: "⬲ "
  - name: "Shield Block"
    desc: "⬲ "
abilities_top:
  - name: Items
    desc: "bastard sword, full plate, light hammer, steel shield (Hardness 5, HP 20, BT 10);"
abilities_bot:
  - name: "Power Attack"
    desc: "⬺ __Frequency__ once per round  __Effect__  The guard makes a melee [[Strike]]. This counts as two attacks when calculating the guard's multiple attack penalty. If this [[Strike]] hits, the guard deals an extra die of weapon damage."

speed: 20 feet

ac: 19
armorclass:
  - name: AC
    desc: "19;  (21 with shield raised); __Fort__: +7 (1d20+7); __Ref__: +6 (1d20+6); __Will__: +5 (1d20+5);"
hp: 20
health:
  - name: HP
    desc: "20; "


attacks:
  - name: Melee
    desc: "⬻ bastard sword +9 ([[two-hand|two-hand d12]]); __Damage__ 1d8+4 (1d8+4) slashing"
  - name: Ranged
    desc: "⬻ light hammer +6 ([[agile]], [[thrown|thrown 20 feet]]); __Damage__ 1d6+4 (1d6+4) bludgeoning"

sourcebook: "_Bestiary 2_, page 201."
```

```encounter-table
name: Oread Guard
creatures:
  - 1: Oread Guard
```

````


