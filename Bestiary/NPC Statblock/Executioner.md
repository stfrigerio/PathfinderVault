---

Level: 6
Type: Human, Humanoid
Alignment: Lawful Neutral
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
name: "Executioner"
level: "Creature 6"
alignment: "LN"
size: "Medium"
trait_03: "Human"
trait_04: "Humanoid"
modifier: 12
perception:
  - name: "Perception"
    desc: "Perception +12;"
languages: "Common; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +15 (1d20+15); __Intimidation__: +13 (1d20+13); __Medicine__: +10 (1d20+10); "
abilityMods: [5, 2, 3, -1, 2, 2]

abilities_bot:
  - name: "Behead"
    desc: "⬽ __Requirements__ The executioner is adjacent to a [[dying|dying]] creature or a creature specifically prepared for a killing blow  __Effect__  The executioner [[Strike|Strikes]] the creature with their greataxe. On a hit, in addition to taking damage, the target must attempt a Fortitude save or be reduced to 0 HP and become [[dying|dying 1]]. If the creature was already [[dying|dying]] (including if it was reduced to 0 HP by the [[Strike]]'s damage), the creature's [[dying|dying]] value increases by 1, in addition to any increase from the [[Strike]]. On a critical failure, the creature dies instantly. If the executioner's [[Strike]] was a critical hit, the target uses the outcome for one degree of success worse than the result of their saving throw."
  - name: "Intimidating Strike"
    desc: "⬺ ([[emotion]], [[fear]], [[fighter]], [[mental]]);  The executioner makes a melee [[Strike]]. If it hits and deals damage, the target is [[frightened|frightened 1]], or [[frightened|frightened 2]] on a critical hit. Mark for Death ⬻ (concentrate) The executioner marks a single creature they can see for death. The first time each round the executioner [[Strike|Strikes]] that creature, the [[Strike]] deals 1d12 (1d12) additional precision damage. The creature remains marked for death until the executioner is knocked out, marks a different creature for death, or the encounter ends."
abilities_top:
  - name: Items
    desc: "+1 greataxe, hood, leather armor;"

speed: 25 feet

ac: 23
armorclass:
  - name: AC
    desc: "23; __Fort__: +15 (1d20+15); __Ref__: +12 (1d20+12); __Will__: +14 (1d20+14);"
hp: 105
health:
  - name: HP
    desc: "105; "


attacks:
  - name: Melee
    desc: "⬻ greataxe +16 ([[magical]], [[sweep]]); __Damage__ 1d12+9 (1d12+9) slashing"

sourcebook: "_Gamemastery Guide_, page 236."
```

```encounter-table
name: Executioner
creatures:
  - 1: Executioner
```

````


