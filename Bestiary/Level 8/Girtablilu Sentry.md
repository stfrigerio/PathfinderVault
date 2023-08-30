---

Level: 8
Type: Beast
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
name: "Girtablilu Sentry"
level: "Creature 8"
alignment: "N"
size: "Large"
trait_03: "Beast"
modifier: 18
perception:
  - name: "Perception"
    desc: "Perception +18; __darkvision__, __imprecise [[tremorsense]] 60__;"
languages: "Common, Girtablilu; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +20 (1d20+20); __Intimidation__: +17 (1d20+17); __Religion__: +16 (1d20+16); __Survival__: +18 (1d20+18); "
abilityMods: [6, 4, 6, 3, 4, 3]

abilities_bot:
  - name: "Constrict"
    desc: "⬻  2d8+6 (2d8+6) bludgeoning, DC 24"
  - name: "Desert Stride"
    desc: "  A girtablilu ignores natural [[terrain|difficult terrain]] in the desert."
  - name: "Girtablilu Venom"
    desc: " ([[poison]]);  __Saving Throw__ DC 24 Fortitude. __Maximum Duration__ 6 rounds __Stage 1__ 2d6 (2d6) poison damage and [[enfeebled|enfeebled 1]] (1 round) __Stage 2__ 3d6 (3d6) poison damage and [[enfeebled|enfeebled 1]] (1 round) __Stage 3__ 3d6 (3d6) poison damage and [[enfeebled|enfeebled 2]] (1 round)"
abilities_top:
  - name: Items
    desc: "hide armor, +1 striking longspear;"

speed: 40 feet

ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__: +20 (1d20+20); __Ref__: +16 (1d20+16); __Will__: +12 (1d20+12);"
hp: 160
health:
  - name: HP
    desc: "160; "


attacks:
  - name: Melee
    desc: "⬻ longspear +21 ([[magical]], [[reach|reach 15 feet]]); __Damage__ 2d8+9 (2d8+9) piercing"
  - name: Melee
    desc: "⬻ pincer +20 ([[agile]]); __Damage__ 2d8+9 (2d8+9) bludgeoning plus [[Grab]]"
  - name: Melee
    desc: "⬻ stinger +20 ([[reach|reach 10 feet]]); __Damage__ 2d6+9 (2d6+9) piercing plus girtablilu venom"

sourcebook: "_Bestiary 3_, page 112."
```

```encounter-table
name: Girtablilu Sentry
creatures:
  - 1: Girtablilu Sentry
```

````


