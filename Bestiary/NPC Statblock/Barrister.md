---

Level: None
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
name: "Barrister"
level: "Creature -1"
alignment: "LN"
size: "Medium"
trait_03: "Human"
trait_04: "Humanoid"
modifier: 6
perception:
  - name: "Perception"
    desc: "Perception +6;"
languages: "Common; "
skills:
  - name: "Skills"
    desc: "__Deception__: +10 (1d20+10); __Diplomacy__: +12 (1d20+12); __Performance__: +10 (1d20+10); __Society__: +9 (1d20+9); __Legal lore__: +13 (1d20+13); "
abilityMods: [0, 1, 1, 3, 2, 4]

abilities_top:
  - name: "Society"
    desc: "  +9 Str +0, Dex +1, Con +1, Int +3, Wis +2, Cha + 4 Items court garb (functions as fine clothing), law book (functions as scholarly journal), writing set."
  - name: "Sway the Judge and Jury"
    desc: "  A barrister gains a +2 circumstance bonus to [[Diplomacy]] checks to [[Make an Impression]] or [[Request]] something of the deciding members within a courtroom. If the barrister successfully Performs against a DC of 20 during the 20 minutes prior to the check, they increase the circumstance bonus to +4."
abilities_bot:
  - name: "Cite Precedent"
    desc: "⬻ ([[auditory]], [[linguistic]]);  The barrister uses existing case law to undermine their opposition. If they succeed at a DC 20 [[Lore|Legal Lore]] check, they impose a –2 circumstance penalty on the next [[Diplomacy]] check an opponent attempts in a legal argument. Any further attempts to Cite Precedent fail until a new topic with different precedents is being argued."

speed: 25 feet

ac: 13
armorclass:
  - name: AC
    desc: "13; __Fort__: +3 (1d20+3); __Ref__: +3 (1d20+3); __Will__: +12 (1d20+12);"
hp: 8
health:
  - name: HP
    desc: "8; "


attacks:
  - name: Melee
    desc: "⬻ fist +4 ([[agile]], [[nonlethal]]); __Damage__ 1d4 (1d4) bludgeoning"

sourcebook: "_Gamemastery Guide_, page 233."
```

```encounter-table
name: Barrister
creatures:
  - 1: Barrister
```

````


