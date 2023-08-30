---




Level: 2
Type:
- Humanoid
- Orc
Alignment: Chaotic Evil
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
source: "TiO"
name: "Orc Commander"
level: "Creature 2"
alignment: "CE"
size: "Medium"
trait_03: "Humanoid"
trait_04: "Orc"
modifier: 11
perception:
  - name: "Perception"
    desc: "Perception +11; __darkvision__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +8 (1d20+8); __Intimidation__: +6 (1d20+6); __Survival__: +5 (1d20+5); "
abilityMods: [4, 2, 1, -1, 1, 2]

abilities_bot:
  - name: "Ferocity"
    desc: "⬲  When the orc is reduced to 0 Hit Points, they can use their reaction to remain conscious with 1 Hit Point, but they gain the [[wounded|wounded 1]] condition (or increases the [[wounded|wounded]] value by 1 if they already have that condition). The orc can't use this ability at [[wounded|wounded 3]]."
  - name: "Stride"
    desc: "⬻  25 feet"
  - name: "Melee Strike"
    desc: "⬻ ([[shove]]);  Damage 1d12+4 (1d12+4) bludgeoning Melee [[Strike]] ⬻ fist +10 (agile, nonlethal), Damage 1d4+4 (1d4+4) bludgeoning"
  - name: "Ranged Strike"
    desc: "⬻ ([[thrown 30 feet]]);  Damage 1d6+4 (1d6+4) piercing"
  - name: "Battle Cry"
    desc: "⬻ ([[concentrate]], [[mental]]);  Bellowing mightily, the commander gives themself and all orc allies within 60 feet who can hear them a +1 status bonus to attack rolls and damage rolls until the start of the orc commander's next turn."
abilities_top:
  - name: Items
    desc: "hide armor, javelin (6), maul;"


ac: 19
armorclass:
  - name: AC
    desc: "19; __Fort__: +7 (1d20+7); __Ref__: +6 (1d20+6); __Will__: +7 (1d20+7);"
hp: 32
health:
  - name: HP
    desc: "32; "


attacks:

sourcebook: "_Troubles In Otari_."
```

```encounter-table
name: Orc Commander
creatures:
  - 1: Orc Commander
```

````


