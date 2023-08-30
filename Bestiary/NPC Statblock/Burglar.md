---

Level: 4
Type: Human, Humanoid
Alignment: Neutral Evil
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
source: "GMG"
name: "Burglar"
level: "Creature 4"
alignment: "NE"
size: "Medium"
trait_03: "Human"
trait_04: "Humanoid"
modifier: 10
perception:
  - name: "Perception"
    desc: "Perception +10;"
languages: "Common; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +10 (1d20+10); __Athletics__: +8 (1d20+8); __Deception__: +7 (1d20+7); __Society__: +7 (1d20+7); __Stealth__: +12 (1d20+12); __Thievery__: +12 (1d20+12); __Underworld lore__: +7 (1d20+7); "
abilityMods: [2, 4, 1, 1, 2, 1]

abilities_mid:
  - name: "Deny Advantage"
    desc: "  The burglar isn't [[flat-footed|flat-footed]] to creatures of 4th level or lower that are [[hidden|hidden]], [[undetected|undetected]], flanking, or using surprise attack."
  - name: "Nimble Dodge"
    desc: "⬲ __Trigger__ The burglar is targeted with a melee or ranged attack by an attacker it can see __Effect__  The burglar gains a +2 circumstance bonus to AC against the triggering attack."
abilities_bot:
  - name: "Mobility"
    desc: "  When the burglar [[Stride|Strides]] half their Speed or less, that movement does not trigger reactions."
  - name: "Sneak Attack"
    desc: "  The burglar deals an extra 1d6 (1d6) precision damage to flatfooted creatures."
  - name: "Surprise Attack"
    desc: "  On the first round of combat, if the burglar rolls [[Deception]] or [[Stealth]] for initiative, creatures that haven't acted are [[flat-footed|flat-footed]] to them."

speed: 30 feet

ac: 21
armorclass:
  - name: AC
    desc: "21;  (22 vs. traps); __Fort__: +7 (1d20+7); __Ref__: +12 (1d20+12); __Will__: +10 (1d20+10);"
hp: 60
health:
  - name: HP
    desc: "60; "


attacks:
  - name: Melee
    desc: "⬻ shortsword +14 ([[agile]], [[finesse]], [[versatile|versatile s]]); __Damage__ 1d6+6 (1d6+6) piercing"
  - name: Melee
    desc: "⬻ sap +12 ([[agile]], [[nonlethal]]); __Damage__ 1d6+4 (1d6+4) bludgeoning"
  - name: Ranged
    desc: "⬻ composite shortbow +14 ([[deadly|deadly 1d10]], [[propulsive]], [[range increment|range increment 60 feet]], [[reload|reload 0]]); __Damage__ 1d6+4 (1d6+4) piercing"

sourcebook: "_Gamemastery Guide_, page 212."
```

```encounter-table
name: Burglar
creatures:
  - 1: Burglar
```

````


