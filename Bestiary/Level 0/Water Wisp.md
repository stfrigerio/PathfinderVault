---

Level: 0
Type:
- Elemental
- Water
Alignment: Neutral
Size: Tiny

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
name: "Water Wisp"
level: "Creature 0"
alignment: "N"
size: "Tiny"
trait_03: "Elemental"
trait_04: "Water"
modifier: 6
perception:
  - name: "Perception"
    desc: "Perception +6; __darkvision__, __mist vision__;"
languages: "Aquan; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +4 (1d20+4); __Medicine__: +6 (1d20+6); __Plane of water lore__: +4 (1d20+4); "
abilityMods: [2, 2, 3, 0, 2, 0]

abilities_top:
  - name: "Mist Vision"
    desc: "  The water wisp ignores the [[concealed|concealed]] condition from mist and fog."
abilities_mid:
  - name: "Resonance"
    desc: " ([[aura]], [[air]]);  30 feet. All wisps vibrate at a frequency attuned to their element, resonating with and empowering all creatures and effects sharing that trait. A creature in the area gains a +1 status bonus to attack and damage rolls for effects with the [[water]] trait; a creature with the [[elemental]] and [[water]] traits gains this bonus to all attack and damage rolls."
  - name: "Accord Essence"
    desc: "⬲ ([[air]]); __Trigger__ An ally within 30 feet that benefited from the wisp's resonance in the last hour is targeted by an attack __Effect__  The wisp detonates itself in a small elemental explosion that gives temporary Hit Points equal to half the wisp's current Hit Points to allies within 30 feet that have benefited from the wisp's resonance in the last hour. These temporary Hit Points last 1 hour. A wisp that uses this reaction is permanently destroyed, and it can be restored only by a [[wish]] spell or similarly powerful effect. If an ability would prevent the wisp's destruction (for instance, if the wisp is summoned and would merely be dismissed), Accord Essence has no effect."
abilities_bot:
  - name: "Drench"
    desc: "⬻ ([[abjuration]], [[primal]], [[water]]);  The wisp puts out all fires in a single 5-foot square. It extinguishes non-magical fire of that size or smaller automatically and attempts to counteract magical fires (counteract modifier +6)."
  - name: "In Concert"
    desc: "  When an water wisp rolls a critical failure on a check to [[Aid]], they get a failure instead, and when they roll a success, they get a critical success instead."

speed: 25 feet, swim 25 feet

ac: 14
armorclass:
  - name: AC
    desc: "14; __Fort__: +8 (1d20+8); __Ref__: +4 (1d20+4); __Will__: +4 (1d20+4);"
hp: 20
health:
  - name: HP
    desc: "20;  __Immunities__ bleed, poison, paralyzed, sleep; __Resistances__ fire 2"


attacks:
  - name: Melee
    desc: "⬻ tendril +6 ([[reach|reach 10 feet]]); __Damage__ 1d6 (1d6) bludgeoning"

sourcebook: "_Bestiary 3_, page 91."
```

```encounter-table
name: Water Wisp
creatures:
  - 1: Water Wisp
```

````


