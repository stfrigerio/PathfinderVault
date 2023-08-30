---


Level: 1
Type:
- Grippli
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
source: "B2"
name: "Grippli Scout"
level: "Creature 1"
alignment: "N"
size: "Small"
trait_03: "Grippli"
trait_04: "Humanoid"
modifier: 8
perception:
  - name: "Perception"
    desc: "Perception +8; __darkvision__;"
languages: "Common, Grippli; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +7 (1d20+7); __Athletics__: +4 (1d20+4); __Nature__: +6 (1d20+6); __Stealth__: +7 (1d20+7), (Stealth: +9 (1d20+9) in forests); __Survival__: +6 (1d20+6); "
abilityMods: [1, 4, 2, 0, 3, -1]

abilities_bot:
  - name: "Hurl Net"
    desc: "⬻ __Requirements__ The grippli is wielding a net in two hands  __Effect__  The grippli makes a ranged [[Strike]] (with a +9 modifier) against a Medium or smaller creature within 20 feet. On a hit, the target is [[flat-footed|flat-footed]] and takes a –10-foot circumstance penalty to its Speeds. On a critical hit, the creature is [[restrained|restrained]] instead. The DC to [[Escape]] the net is 16. A creature adjacent to the target can [[Interact]] with the net to remove it."
  - name: "Jungle Stride"
    desc: "  Gripplis ignore [[terrain|difficult terrain]] in forests and jungles."
abilities_top:
  - name: Items
    desc: "dart (5), leather armor, net, sickle;"

speed: 25 feet, climb 20 feet; jungle stride;

ac: 18
armorclass:
  - name: AC
    desc: "18; __Fort__: +7 (1d20+7); __Ref__: +9 (1d20+9); __Will__: +6 (1d20+6);"
hp: 20
health:
  - name: HP
    desc: "20; "


attacks:
  - name: Melee
    desc: "⬻ sickle +9 ([[agile]], [[finesse]], [[trip]]); __Damage__ 1d4+1 (1d4+1) slashing"
  - name: Ranged
    desc: "⬻ dart +9 ([[agile]], [[thrown|thrown 20 feet]]); __Damage__ 1d4+1 (1d4+1) piercing"

sourcebook: "_Bestiary 2_, page 139."
```

```encounter-table
name: Grippli Scout
creatures:
  - 1: Grippli Scout
```

````


