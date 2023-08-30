---

Level: 0
Type:
- Animal
- Aquatic
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
name: "Vampire Squid"
level: "Creature 0"
alignment: "N"
size: "Small"
trait_03: "Animal"
trait_04: "Aquatic"
modifier: 7
perception:
  - name: "Perception"
    desc: "Perception +7; __darkvision__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +4 (1d20+4); __Stealth__: +7 (1d20+7); "
abilityMods: [0, 3, 0, -4, 3, -2]

abilities_bot:
  - name: "Glowing Mucus"
    desc: "⬻ __Requirements__ The vampire squid is in water __Frequency__ once per day  __Effect__  The vampire squid ejects a cloud of bioluminescent mucus in a 15-foot cone. Non-squid creatures within the cloud must attempt a DC 16 Fortitude save or become [[sickened|sickened 1]]. The glowing mucus remains in the area for 1 minute, and any creature that ends its turn in the area must succeed at a DC 13 Fortitude save or become [[sickened|sickened 1]]."

speed: swim 25 feet

ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__: +4 (1d20+4); __Ref__: +8 (1d20+8); __Will__: +6 (1d20+6);"
hp: 15
health:
  - name: HP
    desc: "15; "


attacks:
  - name: Melee
    desc: "⬻ beak +7 ([[finesse]]); __Damage__ 1d8 (1d8) piercing"
  - name: Melee
    desc: "⬻ tentacles +7 ([[agile]], [[finesse]]); __Damage__ 1d6 (1d6) bludgeoning"

sourcebook: "_Bestiary 2_, page 254."
```

```encounter-table
name: Vampire Squid
creatures:
  - 1: Vampire Squid
```

````


