---

Level: 4
Type: Animal
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
name: "Giant Pangolin"
level: "Creature 4"
alignment: "N"
size: "Large"
trait_03: "Animal"
modifier: 12
perception:
  - name: "Perception"
    desc: "Perception +12; __imprecise scent 30__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +13 (1d20+13); __Stealth__: +8 (1d20+8); __Survival__: +10 (1d20+10); "
abilityMods: [5, 0, 3, -4, 2, 0]

abilities_bot:
  - name: "Devourer of Swarms"
    desc: "  The giant pangolin ignores the resistances of swarms, and its tongue [[Strike]] deals an additional 2d6 (2d6) damage against swarms."
  - name: "Emit Musk"
    desc: "⬻ ([[olfactory]]);  The giant pangolin releases a disorienting and repulsive musk within a 5-foot emanation. Each creature in the area must attempt a DC 20 Fortitude save. The pangolin can't Emit Musk again for 1d4 (1d4) rounds.\n__Critical Success__ The creature becomes temporarily immune to pangolin musk for 1 minute.\n__Success__ The creature is unaffected.\n__Failure__ The creature is [[sickened|sickened 1]].\n__Critical Failure__ The creature becomes [[sickened|sickened 1]] and is [[flat-footed|flat-footed]] until no longer [[sickened|sickened]]."
  - name: "Roll Up"
    desc: "⬻ ([[move]]);  The giant pangolin falls [[prone|prone]] and rolls up into a ball. While rolled up, the only actions the giant pangolin can perform are Emit Musk and [[Stand]], and it also becomes [[blinded|blinded]] and gains resistance 10 to physical damage. An adjacent creature that hits a rolled-up giant pangolin with a melee [[Strike]] takes 1d6 (1d6) slashing damage. These effects end once the giant pangolin Stands."

speed: 30 feet, burrow 20 feet, climb 20 feet

ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__: +11 (1d20+11); __Ref__: +8 (1d20+8); __Will__: +10 (1d20+10);"
hp: 63
health:
  - name: HP
    desc: "63; "


attacks:
  - name: Melee
    desc: "⬻ claw +13 ([[agile]]); __Damage__ 1d10+7 (1d10+7) piercing damage"
  - name: Melee
    desc: "⬻ tongue +13 __Damage__ 1d6+7 (1d6+7) bludgeoning damage plus [[Grab]]"

sourcebook: "_Bestiary 3_, page 199."
```

```encounter-table
name: Giant Pangolin
creatures:
  - 1: Giant Pangolin
```

````


