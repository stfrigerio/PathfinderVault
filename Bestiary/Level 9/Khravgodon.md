---

Level: 9
Type: Animal
Alignment: Neutral
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
source: "B3"
name: "Khravgodon"
level: "Creature 9"
alignment: "N"
size: "Huge"
trait_03: "Animal"
modifier: 18
perception:
  - name: "Perception"
    desc: "Perception +18; __low-light vision__, __imprecise scent 30__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +21 (1d20+21); __Stealth__: +18 (1d20+18); __Survival__: +18 (1d20+18); "
abilityMods: [6, 3, 5, -4, 3, 0]

abilities_mid:
  - name: "Feign Death"
    desc: "⬲ __Trigger__ The opossum is reduced below 70 HP __Effect__  The khravgodon collapses. It is [[flat-footed|flat-footed]] and can use actions that require only its mind, but any other action ends the ruse. A successful DC 18 [[Perception]] check to [[Seek]] or [[Medicine]] check to [[Recall Knowledge]] is required to determine that the animal is not, in fact, dead."
  - name: "Revived Retaliation"
    desc: "⬲ __Trigger__ The opossum is attacked or disturbed by a creature within reach while Feigning Death __Effect__  The opossum [[Strike|Strikes]] the triggering creature."
abilities_bot:
  - name: "Crush Chitin"
    desc: "⬻ __Requirements__ The khravgodon has a creature [[grabbed|grabbed]] or [[restrained|restrained]]  __Effect__  The khravgodon bites the creature, dealing 2d12+9 (2d12+9) piercing damage (DC 28 basic Fortitude save) that ignores the first 5 of the target's Hardness or resistance to physical damage. On a failed save, the target also takes a –2 circumstance penalty to AC for 1 round."
  - name: "Grasping Tail"
    desc: "  A khravgodon can drag a Large or smaller creature it has [[grabbed|grabbed]] with its tail along with it when it [[Stride|Strides]]."

speed: 30 feet, burrow 15 feet, climb 15 feet

ac: 27
armorclass:
  - name: AC
    desc: "27; __Fort__: +20 (1d20+20); __Ref__: +18 (1d20+18); __Will__: +16 (1d20+16);"
hp: 160
health:
  - name: HP
    desc: "160;  __Resistances__ acid 10, poison 10"


attacks:
  - name: Melee
    desc: "⬻ jaws +21 ([[deadly|deadly d12]]); __Damage__ 2d12+9 (2d12+9) piercing"
  - name: Melee
    desc: "⬻ claw +21 ([[agile]]); __Damage__ 2d10+9 (2d10+9) slashing"
  - name: Melee
    desc: "⬻ tail +21 ([[reach|reach 20 feet]]); __Damage__ 2d6+9 (2d6+9) bludgeoning plus [[Grab]]"

sourcebook: "_Bestiary 3_, page 192."
```

```encounter-table
name: Khravgodon
creatures:
  - 1: Khravgodon
```

````


