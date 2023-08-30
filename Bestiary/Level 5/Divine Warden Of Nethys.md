---

Level: 5
Type:
- Construct
- Mindless
Alignment: Neutral
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
source: "B3"
name: "Divine Warden Of Nethys"
level: "Creature 5"
rare_02: "Uncommon"
alignment: "N"
size: "Large"
trait_04: "Construct"
trait_05: "Mindless"
modifier: 11
perception:
  - name: "Perception"
    desc: "Perception +11; __darkvision__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +14 (1d20+14); "
abilityMods: [5, -2, 4, -5, 0, -5]

abilities_mid:
  - name: "Divine Destruction"
    desc: " ([[divine]], [[necromancy]]);  5d6 (5d6) negative, DC 19."
  - name: "Faith Bound"
    desc: "  A divine warden can't attack a creature that openly wears or displays the religious symbol of the divine warden's patron deity unless that creature uses a hostile action against the divine warden first. If the divine warden is intelligent, it can also attack a creature it believes isn't faithful to its deity or who wears the religious symbol as a ruse (typically after succeeding at a Perception check to Sense Motive)"
abilities_bot:
  - name: "Faithful Weapon"
    desc: "  [[staff]], [[striking|striking rune]]."
  - name: "Instrument of Faith"
    desc: "  The divine warden is a beacon for its deity's faith. A cleric of the divine warden's patron deity can channel a [[heal]] spell through a divine warden they can see within 60 feet. The cleric determines any targets or area for the spell as if they were standing in the divine warden's space."

speed: 30 feet

ac: 22
armorclass:
  - name: AC
    desc: "22; __Fort__: +15 (1d20+15); __Ref__: +9 (1d20+9); __Will__: +11 (1d20+11);"
hp: 60
health:
  - name: HP
    desc: "60;  __Immunities__ mental, poison, death effects, disease, doomed, drained, fatigued, healing, necromancy, nonlethal attacks, paralyzed, sickened, unconscious;"


attacks:
  - name: Melee
    desc: "⬻ fist +14 ([[magical]], [[reach|reach 10 feet]]); __Damage__ 2d8+7 (2d8+7) bludgeoning plus [[Grab]]"
  - name: Melee
    desc: "⬻ staff +14 ([[magical]], [[reach|reach 10 feet]], [[two-hand|two-hand d8]]); __Damage__ 2d4+7 (2d4+7) bludgeoning plus [[Grab]]"

spellcasting:
  - name: "Divine Innate Spells"
    desc: "DC 19; __Cantrips (3rd)__ [[daze]];"
  - name: "Divine Domain Spells"
    desc: "DC 19, (1 Focus Point); __3rd__ [[cry of destruction]], [[protector's sacrifice]];"
sourcebook: "_Bestiary 3_, page 73."
```

```encounter-table
name: Divine Warden Of Nethys
creatures:
  - 1: Divine Warden Of Nethys
```

````


