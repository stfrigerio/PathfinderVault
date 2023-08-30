---




Level: 2
Type:
- Gnome
- Humanoid
Alignment: Neutral
Size: Small




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
source: "B1"
name: "Deep Gnome Warrior"
level: "Creature 2"
alignment: "N"
size: "Small"
trait_03: "Gnome"
trait_04: "Humanoid"
modifier: 7
perception:
  - name: "Perception"
    desc: "Perception +7; __darkvision__;"
languages: "Gnomish, Undercommon; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +8 (1d20+8); __Intimidation__: +5 (1d20+5); __Stealth__: +5 (1d20+5); "
abilityMods: [4, 2, 3, 0, 1, -1]

abilities_mid:
  - name: "Attack of Opportunity"
    desc: "⬲ "
  - name: "Shield Block"
    desc: "⬲ "
abilities_top:
  - name: Items
    desc: "heavy crossbow (20 bolts), spear, steel shield (Hardness 5, HP 20, BT 10), studded leather armor;"

speed: 20 feet

ac: 18
armorclass:
  - name: AC
    desc: "18;  (20 with shield raised); __Fort__: +9 (1d20+9); __Ref__: +8 (1d20+8); __Will__: +5 (1d20+5);"
hp: 34
health:
  - name: HP
    desc: "34; "


attacks:
  - name: Melee
    desc: "⬻ spear +10 __Damage__ 1d6+4 (1d6+4) piercing"
  - name: Ranged
    desc: "⬻ heavy crossbow +8 ([[range increment|range increment 120 feet]], [[reload|reload 2]]); __Damage__ 1d10 (1d10) piercing"

spellcasting:
  - name: "Primal Innate Spells"
    desc: "DC 15; __1st__ [[illusory disguise]];"
sourcebook: "_Bestiary_, page 75."
```

```encounter-table
name: Deep Gnome Warrior
creatures:
  - 1: Deep Gnome Warrior
```

````


