---


Level: 1
Type:
- Amphibious
- Mindless
- Ooze
Alignment: Neutral
Size: Small


tag: 👹

---

> [!infobox]+
> #  `= this.file.name`
> ![[Giant_amoeba.jpg]]
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
name: "Giant Amoeba"
level: "Creature 1"
alignment: "N"
size: "Small"
trait_03: "Amphibious"
trait_04: "Mindless"
trait_05: "Ooze"
modifier: 4
perception:
  - name: "Perception"
    desc: "Perception +4; __motion sense 60__, __no vision__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +6 (1d20+6); __Stealth__: +3 (1d20+3); "
abilityMods: [3, -2, 2, -5, 0, -5]

abilities_top:
  - name: "Motion Sense"
    desc: "  An amoeba swarm can sense nearby creatures through vibration and air or water movement."
abilities_bot:
  - name: "Constrict"
    desc: "⬻  1d4 (1d4) bludgeoning plus 1d4 (1d4) acid, DC 17."
  - name: "Envelop"
    desc: "⬽ __Requirements__ The giant amoeba begins its turn with a target its size or smaller [[grabbed|grabbed]]  __Effect__  The giant amoeba maintains the Grab and extends pseudopods to surround the creature and pull it inside the amoeba's body. This thereafter has the same effect as if the amoeba had Engulfed the creature (DC 17, 1d6 (1d6) acid, [[Escape]] DC 17, Rupture 3)."
  - name: "Weak Acid"
    desc: "  An amoeba's acid damages only organic material—not metal, stone, or other inorganic substances."

speed: 10 feet, climb 10 feet, swim 10 feet

ac: 8
armorclass:
  - name: AC
    desc: "8; __Fort__: +7 (1d20+7); __Ref__: +3 (1d20+3); __Will__: +5 (1d20+5);"
hp: 45
health:
  - name: HP
    desc: "45;  __Immunities__ acid, mental, precision, critical hits, unconscious, visual;"


attacks:
  - name: Melee
    desc: "⬻ pseudopod +8 __Damage__ 1d6 (1d6) acid plus Grab"

sourcebook: "_Bestiary 2_, page 192."
```

```encounter-table
name: Giant Amoeba
creatures:
  - 1: Giant Amoeba
```

````


