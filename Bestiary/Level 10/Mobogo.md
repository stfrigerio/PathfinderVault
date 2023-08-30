
---


Level: 10
Type:
- Amphibious
- beast
- boggard
- Magical
Alignment: Chaotic Evil
Size: Huge
CR: 10
Environment: Temperate swamps


tag: 👹

---

> [!infobox]+
> #  `= this.file.name`
> ![[Mobogo.jpg]]
> ##### Stats
> Type | Stat |
> :---:|:---:|
> **Level** | `= this.Level` |
> **Type** | `= this.Type` |
> **Alignment** | `= this.Alignment` |
> **Size** | `= this.Size` |
> **CR** | `= this.CR` |
> **Environment** | `= this.Environment` |




````ad-info
title: Statblock

```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B3"
name: "Mobogo"
level: "Creature 10"
alignment: "CE"
size: "Huge"
trait_03: "Amphibious"
trait_04: "Beast"
modifier: 21
perception:
  - name: "Perception"
    desc: "Perception +21; __darkvision__;"
languages: "Boggard;  speak with animals;"
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +19 (1d20+19); __Athletics__: +23 (1d20+23); __Nature__: +21 (1d20+21); __Stealth__: +19 (1d20+19), (Stealth: +21 (1d20+21) in swamps); "
abilityMods: [7, 5, 6, -2, 5, 7]

abilities_bot:
  - name: "Song of the Swamp"
    desc: "⬻ ([[auditory]], [[emotion]], [[enchantment]], [[mental]], [[primal]]);  Frequency once per 10 minutes; The mobogo unleashes a booming croak. All boggards and mobogos within 50 feet gain a +2 status bonus to damage rolls and saves against fear for 1 round. Other creatures in the area of effect must attempt a DC 27 Will save.\n__Success__ The creature is unaffected and is temporarily immune for 24 hours.\n__Failure__ The creature is [[slowed|slowed 1]] for 1d4 (1d4) rounds.\n__Critical Failure__ The creature is [[slowed|slowed 2]] for 1d4 (1d4) rounds."
  - name: "Swallow Whole"
    desc: "⬻ ([[attack]]);  Large, 2d12+6 (2d12+6) bludgeoning, Rupture 19"
  - name: "Swamp Stride"
    desc: "  A mobogo ignores [[terrain|difficult terrain]] caused by swamp terrain features."
  - name: "Tongue Grab"
    desc: "  A creature hit by the mobogo's tongue becomes [[grabbed|grabbed]] by the mobogo. The creature isn't [[immobilized|immobilized]], but it can't move beyond the reach of the mobogo's tongue. A creature can sever the tongue with a [[Strike]] against AC 27 that deals at least 10 slashing damage. This deals no damage to the mobogo but prevents it from using its tongue [[Strike]] until it regrows its tongue, which takes 1 round. The mobogo can move without ending the Grab as long as the creature remains within the tongue's reach."
  - name: "Tongue Reposition"
    desc: "⬻  The mobogo attempts to move a creature [[grabbed|grabbed]] by its tongue. The mobogo rolls an [[Athletics]] check against the creature's Fortitude DC. On a success, the mobogo moves the creature into any space within the tongue's reach. If it wishes, the mobogo can transfer the [[grabbed|grabbed]] creature to its jaws."

speed: 25 feet, fly 20 feet, swim 30 feet; swamp stride;

ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__: +22 (1d20+22); __Ref__: +17 (1d20+17); __Will__: +19 (1d20+19);"
hp: 160
health:
  - name: HP
    desc: "160; [[regeneration]] 30 (deactivated by acid, cold, or fire;"


attacks:
  - name: Melee
    desc: "⬻ jaws +23 ([[reach|reach 10 feet]]); __Damage__ 2d12+13 (2d12+13) piercing plus Improved [[Grab]]"
  - name: Melee
    desc: "⬻ tongue +23 ([[agile]], [[reach|reach 30 feet]]); __Damage__ 2d6+13 (2d6+13) bludgeoning plus tongue grab"

spellcasting:
  - name: "Primal Innate Spells"
    desc: "DC 27; __4th__ [[create water]] (at will), [[entangle]], [[obscuring mist]], [[sound burst]] (at will); __5th__ [[control water]]; __Constant__ __(2nd)__ [[pass without trace]], [[speak]];"
sourcebook: "_Bestiary 3_, page 170."
```

```encounter-table
name: Mobogo
creatures:
  - 1: Mobogo
```

````



> **Mobogos** reside in the most primal swamps of [[Golarion]], grotesque eldritch wildernesses unchanged for centuries. The crude religion of [[Boggard|boggard]]-kind says that when the massive goddess [[Gogunta]] deposited her frogspawn in the muddy morass of Golarion's still-forming continents, mobogos were among the first creatures to emerge. Ever since, these Swamp Kings have slept and fed, preying upon the beasts of their fetid meres, growing huge and lethargic, and dreaming inscrutable amphibious dreams of their godly mother's return.









