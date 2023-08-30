---

Level: 4
Type:
- Earth
- Elemental
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
source: "B2"
name: "Earthen Destrier"
level: "Creature 4"
alignment: "N"
size: "Large"
trait_03: "Earth"
trait_04: "Elemental"
modifier: 10
perception:
  - name: "Perception"
    desc: "Perception +10; __darkvision__, __imprecise [[tremorsense]] 60__;"
languages: "Terran; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +12 (1d20+12); "
abilityMods: [4, 1, 4, -1, 3, 0]

abilities_bot:
  - name: "Earth Glide"
    desc: "  An earthen destrier can [[Burrow]] through earthen matter, including rock. When it does so, it moves at its full burrow Speed, leaving no tunnels or signs of its passing."
  - name: "Lancing Charge"
    desc: "  If the destrier moved at least 10 feet directly before its lance arm [[Strike]], it gains a +2 circumstance bonus to its damage roll."
  - name: "Tilting Strike"
    desc: "⬲ __Trigger__ The earthen destrier tramples a creature __Effect__  The earthen destrier makes a lance arm [[Strike]] against the creature it's trampling at a –5 penalty."
  - name: "Trample"
    desc: "⬽  Medium or smaller, hoof, DC 20."

speed: 50 feet, burrow 30 feet; earth glide;

ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__: +14 (1d20+14); __Ref__: +9 (1d20+9); __Will__: +10 (1d20+10);"
hp: 72
health:
  - name: HP
    desc: "72; "


attacks:
  - name: Melee
    desc: "⬻ lance arm +14 ([[deadly|deadly d8]], [[reach|reach 10 feet]]); __Damage__ 2d8+6 (2d8+6) piercing and lancing charge"
  - name: Melee
    desc: "⬻ hoof +14 __Damage__ 2d6+6 (2d6+6) bludgeoning"

sourcebook: "_Bestiary 2_, page 108."
```

```encounter-table
name: Earthen Destrier
creatures:
  - 1: Earthen Destrier
```

````


