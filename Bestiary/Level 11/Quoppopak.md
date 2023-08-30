---

Level: 11
Type:
- Aberration
- Aquatic
Alignment: Neutral Evil
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
source: "B2"
name: "Quoppopak"
level: "Creature 11"
alignment: "NE"
size: "Large"
trait_03: "Aberration"
trait_04: "Aquatic"
modifier: 22
perception:
  - name: "Perception"
    desc: "Perception +22; __low-light vision__;"
languages: "Aquan; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +23 (1d20+23); __Athletics__: +22 (1d20+22); __Stealth__: +23 (1d20+23); "
abilityMods: [7, 6, 5, -2, 5, 0]

abilities_mid:
  - name: "Attack of Opportunity"
    desc: "⬲  Tentacle only."
abilities_bot:
  - name: "Flooding Thrust"
    desc: "⬺ __Requirements__ The quoppopak's ventral tube is in water  __Effect__  The quoppopak uses Tentacle Stab against a creature within reach; if either of these [[Strike|Strikes]] hits, the creature must attempt a DC 30 Reflex save. On a failed save, the quoppopak shoots water through its tentacles into the creature, dealing 2d6+5 (2d6+5) bludgeoning damage and making the creature [[sickened|sickened 1]] as its internal organs fill with water (double damage and [[sickened|sickened 2]] on a critical failure)."
  - name: "Tentacle Stab"
    desc: "⬻ __Frequency__ once per round  __Effect__  The quoppopak makes two tentacle [[Strike|Strikes]] against the same creature. These [[Strike|Strikes]] deal piercing damage instead of bludgeoning, and the quoppopak can't Grab with them. Its multiple attack penalty doesn't increase until after both attacks."
  - name: "Water Glide"
    desc: "  The quoppopak can stand and move on the surface of water or other liquids without falling through. It can go underwater if it wishes, but it must [[Swim]] to do so."

speed: 15 feet, swim 40 feet, water glide 30 feet

ac: 31
armorclass:
  - name: AC
    desc: "31; __Fort__: +22 (1d20+22); __Ref__: +23 (1d20+23); __Will__: +18 (1d20+18);"
hp: 195
health:
  - name: HP
    desc: "195; "


attacks:
  - name: Melee
    desc: "⬻ beak +24 ([[reach|reach 10 feet]]); __Damage__ 3d8+13 (3d8+13) piercing"
  - name: Melee
    desc: "⬻ tentacle +24 ([[agile]], [[reach|reach 15 feet]]); __Damage__ 2d8+13 (2d8+13) bludgeoning plus Grab"
  - name: Melee
    desc: "⬻ ventral tube +24 ([[reach|reach 10 feet]]); __Damage__ 2d6+13 (2d6+13) slashing plus 1d6 (1d6) [[persistent damage|persistent bleed]]"
  - name: Ranged
    desc: "⬻ water jet +23 ([[range|range 100 feet]], [[water]]); __Damage__ 2d6+13 (2d6+13) bludgeoning plus"

sourcebook: "_Bestiary 2_, page 219."
```

```encounter-table
name: Quoppopak
creatures:
  - 1: Quoppopak
```

````


