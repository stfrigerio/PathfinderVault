---

Level: 6
Type: Plant
Alignment: Chaotic Evil
Size: Huge

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
name: "Scythe Tree"
level: "Creature 6"
alignment: "CE"
size: "Huge"
trait_03: "Plant"
modifier: 14
perception:
  - name: "Perception"
    desc: "Perception +14; __lifesense 30__, __low-light vision__;"
languages: "Aklo, Arboreal, Sylvan; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +15 (1d20+15); __Stealth__: +12 (1d20+12); "
abilityMods: [7, 2, 4, 0, 2, 0]

abilities_mid:
  - name: "Axe Vulnerability"
    desc: "  A scythe tree takes 5 additional damage from axes."
  - name: "Ripping Disarm"
    desc: "⬲ __Trigger__ A creature rolls a critical failure on a melee weapon [[Strike]] against the scythe tree __Effect__  The scythe tree attempts to [[Disarm]] the creature."
abilities_bot:
  - name: "Dead Tree"
    desc: "⬻ ([[concentrate]]);  Until the scythe tree acts, it appears to be a dead tree. It has an automatic result of 35 on [[Deception]] checks and DCs to pass as a dead tree."
  - name: "Woodland Ambush"
    desc: "⬻ __Requirements__ The scythe tree is using Dead Tree in forested terrain, and a creature that hasn't detected it is within 30 feet  __Effect__  The scythe tree [[Stride|Strides]] up to 25 feet toward the triggering creature. Once the creature is in reach, the scythe tree makes a scythe branch [[Strike]] against it. The creature is [[flat-footed|flat-footed]] against this [[Strike]]."

speed: 15 feet

ac: 24
armorclass:
  - name: AC
    desc: "24; __Fort__: +17 (1d20+17); __Ref__: +8 (1d20+8); __Will__: +9 (1d20+9);"
hp: 105
health:
  - name: HP
    desc: "105;  __Resistances__ bludgeoning 5, piercing 5"


attacks:
  - name: Melee
    desc: "⬻ scythe branch +18 ([[backswing]], [[deadly|deadly d10]], [[reach|reach 15 feet]]); __Damage__ 2d10+9 (2d10+9) slashing"

sourcebook: "_Bestiary 2_, page 235."
```

```encounter-table
name: Scythe Tree
creatures:
  - 1: Scythe Tree
```

````


