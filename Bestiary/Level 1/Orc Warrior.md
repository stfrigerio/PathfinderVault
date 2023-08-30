---


Level: 1
Type:
- Humanoid
- Orc
Alignment: Chaotic Evil
Size: Medium


tag: 👹

---

> [!infobox]+
> #  `= this.file.name`
> ![[Orc_warlord.jpg]]
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
name: "Orc Warrior"
level: "Creature 1"
alignment: "CE"
size: "Medium"
trait_03: "Humanoid"
trait_04: "Orc"
modifier: 6
perception:
  - name: "Perception"
    desc: "Perception +6; __darkvision__;"
languages: "Orc; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +7 (1d20+7); __Intimidation__: +4 (1d20+4); __Survival__: +4 (1d20+4); "
abilityMods: [4, 2, 3, -1, 1, 0]

abilities_mid:
  - name: "Attack of Opportunity"
    desc: "⬲ "
  - name: "Ferocity"
    desc: "⬲ "
abilities_top:
  - name: Items
    desc: "breastplate, javelin (4), orc necksplitter, shortsword (2);"

speed: 25 feet

ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__: +8 (1d20+8); __Ref__: +7 (1d20+7); __Will__: +4 (1d20+4);"
hp: 23
health:
  - name: HP
    desc: "23; "


attacks:
  - name: Melee
    desc: "⬻ orc necksplitter +7 ([[forceful]], [[sweep]]); __Damage__ 1d8+4 (1d8+4) slashing"
  - name: Melee
    desc: "⬻ shortsword +7 ([[agile]], [[versatile|versatile p]]); __Damage__ 1d6+4 (1d6+4) slashing"
  - name: Melee
    desc: "⬻ fist +7 ([[agile]], [[nonlethal]]); __Damage__ 1d4+4 (1d4+4) bludgeoning"
  - name: Ranged
    desc: "⬻ javelin +5 ([[thrown|thrown 30 feet]]); __Damage__ 1d6+4 (1d6+4) piercing"

sourcebook: "_Bestiary_, page 257."
```

```encounter-table
name: Orc Warrior
creatures:
  - 1: Orc Warrior
```

````


