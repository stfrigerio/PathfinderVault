---


Level: 1
Type:
- Amphibious
- Boggard
- Humanoid
Alignment: Chaotic Evil
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
source: "B1"
name: "Boggard Scout"
level: "Creature 1"
alignment: "CE"
size: "Medium"
trait_03: "Amphibious"
trait_04: "Boggard"
trait_05: "Humanoid"
modifier: 7
perception:
  - name: "Perception"
    desc: "Perception +7; __darkvision__;"
languages: "Boggard, Common; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +5 (1d20+5); __Athletics__: +8 (1d20+8); __Stealth__: +7 (1d20+7), (Stealth: +9 (1d20+9) in water); "
abilityMods: [3, 2, 4, -1, 2, 0]

abilities_bot:
  - name: "Swamp Stride"
    desc: "  A boggard scout ignores [[terrain|difficult terrain]] caused by swamp terrain features."
  - name: "Terrifying Croak"
    desc: "⬻ ([[auditory]], [[emotion]], [[fear]], [[mental]]);  The boggard scout unleashes a terrifying croak. Any non-boggard within 30 feet becomes [[frightened|frightened 1]] unless they succeed at a DC 17 Will save; those who critically succeed are temporarily immune for 1 minute."
  - name: "Tongue Grab"
    desc: "  If the boggard scout hits a creature with its tongue, that creature becomes [[grabbed|grabbed]] by the boggard. Unlike with a normal grab, the creature isn't [[immobilized|immobilized]], but it can't move beyond the reach of the boggard's tongue. A creature can sever the tongue by hitting AC 13 and dealing at least 2 slashing damage. Though this doesn't deal any damage to the boggard, it prevents it from using its tongue [[Strike]] until it regrows its tongue, which takes a week."
abilities_top:
  - name: Items
    desc: "leather armor, morningstar, sling (10 bullets);"

speed: 20 feet, swim 25 feet; swamp stride;

ac: 16
armorclass:
  - name: AC
    desc: "16; __Fort__: +9 (1d20+9); __Ref__: +5 (1d20+5); __Will__: +7 (1d20+7);"
hp: 24
health:
  - name: HP
    desc: "24; "


attacks:
  - name: Melee
    desc: "⬻ morningstar +8 ([[versatile|versatile p]]); __Damage__ 1d6+3 (1d6+3) bludgeoning"
  - name: Melee
    desc: "⬻ tongue +8 ([[reach|reach 10 feet]]); __Damage__ tongue grab"
  - name: Ranged
    desc: "⬻ sling +7 ([[propulsive]], [[reload|reload 1]], [[range increment|range increment 50 feet]]); __Damage__ 1d6+1 (1d6+1) bludgeoning"

sourcebook: "_Bestiary_, page 44."
```

```encounter-table
name: Boggard Scout
creatures:
  - 1: Boggard Scout
```

````


