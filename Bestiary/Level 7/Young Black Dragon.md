---

Level: 7
Type:
- Acid
- Amphibious
- Dragon
Alignment: Chaotic Evil
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
source: "B1"
name: "Young Black Dragon"
level: "Creature 7"
alignment: "CE"
size: "Large"
trait_03: "Acid"
trait_04: "Amphibious"
trait_05: "Dragon"
modifier: 15
perception:
  - name: "Perception"
    desc: "Perception +15; __darkvision__, __imprecise scent 60__;"
languages: "Draconic; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +14 (1d20+14); __Arcana__: +12 (1d20+12); __Athletics__: +17 (1d20+17); __Deception__: +15 (1d20+15); __Intimidation__: +15 (1d20+15); __Stealth__: +16 (1d20+16); "
abilityMods: [6, 3, 4, 1, 2, 2]

abilities_mid:
  - name: "Frightful Presence"
    desc: " ([[aura]], [[emotion]], [[fear]], [[mental]]);  90 feet, DC 23."
  - name: "Tail Lash"
    desc: "⬲ __Trigger__ A creature within reach of the dragon's tail takes an action to [[Strike]] or attempt a skill check __Effect__  The dragon [[Strike|Strikes]] with its tail at the triggering creature at a –2 penalty. If it hits, the creature takes a –2 circumstance penalty to the triggering roll."
abilities_bot:
  - name: "Breath Weapon"
    desc: "⬺ ([[acid]], [[arcane]], [[evocation]]);  The dragon breathes a spray of acid that deals 8d6 (8d6) acid damage in a 60-foot line (DC 25 basic Reflex save). It can't use Breath Weapon again for 1d4 (1d4) rounds."
  - name: "Draconic Frenzy"
    desc: "⬺  The dragon makes two claw [[Strike|Strikes]] and one horns [[Strike]] in any order."
  - name: "Draconic Momentum"
    desc: "  The dragon recharges its Breath Weapon whenever it scores a critical hit with a [[Strike]]."

speed: 40 feet, fly 100 feet, swim 40 feet

ac: 25
armorclass:
  - name: AC
    desc: "25; __Fort__: +17 (1d20+17); __Ref__: +12 (1d20+12); __Will__: +15 (1d20+15);"
hp: 125
health:
  - name: HP
    desc: "125;  __Immunities__ acid, paralyzed, sleep;"


attacks:
  - name: Melee
    desc: "⬻ jaws +19 ([[acid]], [[reach|reach 10 feet]]); __Damage__ 2d10+9 (2d10+9) piercing plus 1d6 (1d6) acid"
  - name: Melee
    desc: "⬻ claw +19 ([[agile]]); __Damage__ 2d6+9 (2d6+9) slashing"
  - name: Melee
    desc: "⬻ tail +17 ([[reach|reach 15 feet]]); __Damage__ 2d8+7 (2d8+7) bludgeoning"
  - name: Melee
    desc: "⬻ horns +17 ([[reach|reach 10 feet]]); __Damage__ 1d8+7 (1d8+7) piercing"

sourcebook: "_Bestiary_, page 105."
```

```encounter-table
name: Young Black Dragon
creatures:
  - 1: Young Black Dragon
```

````


