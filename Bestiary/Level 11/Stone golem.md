
---


Level: 11
Type:
- Construct
- Golem
- Mindless
Alignment: Neutral
Size: Large
CR: 11
Environment: Any


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
> **CR** | `= this.CR` |
> **Environment** | `= this.Environment` |




````ad-info
title: Statblock

```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "B1"
name: "Stone Golem"
level: "Creature 11"
rare_02: "Uncommon"
alignment: "N"
size: "Large"
trait_04: "Construct"
trait_05: "Golem"
trait_06: "Mindless"
modifier: 17
perception:
  - name: "Perception"
    desc: "Perception +17; __darkvision__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +26 (1d20+26); "
abilityMods: [7, -1, 4, -5, 0, -5]

abilities_mid:
  - name: "Golem Antimagic"
    desc: "  harmed by cold and water (5d10 (5d10), 2d8 (2d8) from areas and [[persistent damage|persistent damage]]); healed by acid (area 2d8 (2d8) HP); [[slowed|slowed]] by earth."
  - name: "Vulnerable to Stone to Flesh"
    desc: "  A [[stone to flesh]] spell negates the golem's golem antimagic and its resistance to physical damage for 1 round. A [[flesh to stone]] spell reverses this effect immediately."
abilities_bot:
  - name: "Impose Paralysis"
    desc: "⬲ ([[incapacitation]]); __Trigger__ The stone golem hits a [[slowed|slowed]] creature. __Effect__  The creature must succeed at a DC 30 Fortitude save or become [[paralyzed|paralyzed]] for 1 round."
  - name: "Inexorable March"
    desc: "⬻  The stone golem [[Stride|Strides]] up to its Speed, pushing back each creature whose space it moves into and damaging them if they try to stop its movement. A creature can attempt to bar the way by succeeding at a DC 34 Fortitude save. On a critical success, the resisting creature takes no damage; otherwise it is damaged as if hit by the golem's fist."
  - name: "Slowing Pulse"
    desc: "⬻ ([[arcane]], [[concentrate]], [[transmutation]]);  Each creature in a 10-foot emanation must succeed at a DC 30 Fortitude save or be [[slowed|slowed 1]] for 1 minute. The golem can't use Slowing Pulse again for 1d4 (1d4) rounds."

speed: 20 feet

ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__: +24 (1d20+24); __Ref__: +18 (1d20+18); __Will__: +19 (1d20+19);"
hp: 175
health:
  - name: HP
    desc: "175;  __Immunities__ acid, bleed, mental, poison, death effects, disease, doomed, drained, fatigued, healing, magic (see below), necromancy, nonlethal attacks, paralyzed, sickened, unconscious; __Resistances__ physical 10 (except adamantine)"


attacks:
  - name: Melee
    desc: "⬻ fist +24 ([[magical]], [[reach|reach 10 feet]]); __Damage__ 2d10+13 (2d10+13) bludgeoning"

sourcebook: "_Bestiary_, page 187."
```

```encounter-table
name: Stone Golem
creatures:
  - 1: Stone Golem
```

````



> **Stone golems** are powerful humanoid [[Construct|constructs]] made of stone, whose features are frequently personalized by their creators. A stone golem is nine feet tall and weighs around 2,000 pounds.


## Variants

> **Serpentstone golems** are built by the [[Serpentfolk|serpentfolk]] from serpentstone in the shape of [[PathfinderWiki/Creatures/Snake|snakes]] and [[Hydra|hydras]]. They are capable of breathing a green gas that petrifies enemies.










