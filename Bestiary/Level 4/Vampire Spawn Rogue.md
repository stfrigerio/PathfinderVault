---

Level: 4
Type:
- Undead
- Vampire
Alignment: Chaotic Evil
Size: Medium

tag: 👹

---

> [!infobox]+
> #  `= this.file.name`
> ![[Bloodbound_clean_cover.jpg]]
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
name: "Vampire Spawn Rogue"
level: "Creature 4"
alignment: "CE"
size: "Medium"
trait_03: "Undead"
trait_04: "Vampire"
modifier: 12
perception:
  - name: "Perception"
    desc: "Perception +12; __darkvision__;"
languages: "Common;  plus one regional language;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +11 (1d20+11); __Athletics__: +9 (1d20+9); __Intimidation__: +8 (1d20+8); __Society__: +5 (1d20+5); __Stealth__: +12 (1d20+12); "
abilityMods: [3, 5, 1, -1, 3, 2]

abilities_bot:
  - name: "Drink Blood"
    desc: "⬻ ([[divine]], [[necromancy]]);  When Drinking Blood, the spawn regains 5 HP."
  - name: "Sneak Attack"
    desc: "  The vampire spawn deals 1d6 (1d6) extra precision damage to [[flat-footed|flat-footed]] creatures."

speed: 25 feet, climb 25 feet

ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__: +9 (1d20+9); __Ref__: +13 (1d20+13); __Will__: +11 (1d20+11);"
hp: 40
health:
  - name: HP
    desc: "40; coffin restoration, fast healing 5, negative healing; __Immunities__ poison, death effects, disease, paralyze, sleep; __Weaknesses__ vampire weaknesses ;"


attacks:
  - name: Melee
    desc: "⬻ claw +14 ([[agile]]); __Damage__ 1d8+6 (1d8+6) slashing plus Grab"

sourcebook: "_Bestiary_, page 320."
```

```encounter-table
name: Vampire Spawn Rogue
creatures:
  - 1: Vampire Spawn Rogue
```

````


