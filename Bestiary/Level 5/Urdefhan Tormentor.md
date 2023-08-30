---

Level: 5
Type:
- Humanoid
- Urdefhan
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
source: "B2"
name: "Urdefhan Tormentor"
level: "Creature 5"
alignment: "NE"
size: "Medium"
trait_03: "Humanoid"
trait_04: "Urdefhan"
modifier: 13
perception:
  - name: "Perception"
    desc: "Perception +13; __greater darkvision__;"
languages: "Aklo, Daemonic, Undercommon; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +8 (1d20+8); __Crafting__: +9 (1d20+9); __Intimidation__: +11 (1d20+11); __Occultism__: +11 (1d20+11); __Religion__: +13 (1d20+13); "
abilityMods: [3, 1, 3, 2, 4, 2]

abilities_mid:
  - name: "Necrotic Decay"
    desc: " ([[divine]], [[necromancy]], [[negative]]);  When an urdefhan dies, its [[invisible|invisible]] flesh quickly rots away and sublimates into a foul-smelling gas that fills a 5-foot emanation around the body. This gas deals 5d6 (5d6) negative damage to creatures in this area as their flesh curdles and rots as well (DC 21 basic Fortitude save)."
abilities_top:
  - name: Items
    desc: "warhammer;"

speed: 25 feet

ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__: +11 (1d20+11); __Ref__: +10 (1d20+10); __Will__: +15 (1d20+15);"
hp: 77
health:
  - name: HP
    desc: "77; negative healing; __Immunities__ death effects, disease, fear; __Weaknesses__ positive 5;"


attacks:
  - name: Melee
    desc: "⬻ warhammer +12 ([[shove]]); __Damage__ 1d8+5 (1d8+5) bludgeoning"
  - name: Melee
    desc: "⬻ jaws +14 __Damage__ 2d6+5 (2d6+5) piercing plus"

sourcebook: "_Bestiary 2_, page 273."
```

```encounter-table
name: Urdefhan Tormentor
creatures:
  - 1: Urdefhan Tormentor
```

````


