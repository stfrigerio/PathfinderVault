
---


Level: 10
Type:
- Construct
- Golem
- Mindless
Alignment: Neutral
Size: Large
CR: 10
Environment: Any


tag: 👹

---

> [!infobox]+
> #  `= this.file.name`
> ![[Rampaging_golem.jpg]]
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
name: "Clay Golem"
level: "Creature 10"
rare_02: "Uncommon"
alignment: "N"
size: "Large"
trait_04: "Construct"
trait_05: "Golem"
trait_06: "Mindless"
modifier: 16
perception:
  - name: "Perception"
    desc: "Perception +16; __darkvision__;"
skills:
  - name: "Skills"
    desc: "__Athletics__: +24 (1d20+24); "
abilityMods: [6, -1, 6, -5, 0, -5]

abilities_mid:
  - name: "Berserk"
    desc: "  A severely damaged clay golem has a chance of going berserk. If it has 50 or fewer Hit Points at the start of its turn, the golem must succeed at a DC 5 flat check or go berserk. A berserk golem wildly attacks the nearest living creature, or the nearest object if no creatures are nearby."
  - name: "Golem Antimagic"
    desc: "  harmed by cold and water (5d10 (5d10), 2d6 (2d6) from areas or [[persistent damage|persistent damage]]); healed by acid (area 2d6 (2d6) HP); [[slowed|slowed]] by earth."
  - name: "Vulnerable to Disintegrate"
    desc: "  A [[disintegrate]] spell affects the golem but deals half the normal amount of damage and causes the golem to become [[slowed|slowed 2]] for 1 round."
  - name: "Quicken"
    desc: "⭓ ([[divine]], [[transmutation]]); __Frequency__ once per day __Trigger__ The clay golem's turn begins. __Effect__  It can't trigger this free action on the first turn of combat. The clay golem becomes [[quickened|quickened]] for 1 minute."
abilities_bot:
  - name: "Berserk Slam"
    desc: "⬻ __Requirements__ The golem is berserk.  __Effect__  The clay golem [[Strike|Strikes]] with its fist at a –1 circumstance penalty. If its [[Strike]] hits, the clay golem deals an additional 1d8 (1d8) damage and knocks the target [[prone|prone]]."
  - name: "Cursed Wound"
    desc: " ([[divine]], [[curse]], [[necromancy]]);  A creature hit by the clay golem's fist must succeed at a DC 29 Fortitude save or be cursed until healed to its maximum HP. The cursed creature can't regain HP except via magic, and anyone casting a spell to heal the creature must succeed at a DC 29 counteract check or the healing has no effect. The golem's counteract level is equal to its creature level."

speed: 20 feet

ac: 29
armorclass:
  - name: AC
    desc: "29; __Fort__: +23 (1d20+23); __Ref__: +16 (1d20+16); __Will__: +17 (1d20+17);"
hp: 175
health:
  - name: HP
    desc: "175;  __Immunities__ acid, bleed, mental, poison, death effects, disease, doomed, drained, fatigued, healing, magic (see below), necromancy, nonlethal attacks, paralyzed, sickened, unconscious; __Resistances__ physical 10 (except adamantine)"


attacks:
  - name: Melee
    desc: "⬻ fist +24 ([[magical]], [[reach|reach 10 feet]]); __Damage__ 2d10+12 (2d10+12) bludgeoning plus cursed wound"

sourcebook: "_Bestiary_, page 186."
```

```encounter-table
name: Clay Golem
creatures:
  - 1: Clay Golem
```

````



> **Clay golems** are a type of golem created from soft clay, usually by powerful divine spellcasters. They are generally eight feet in height and six hundred pounds in weight. (To put that in context, the average [[Ogre|ogre]] is two feet taller but weighs only fifty pounds more.)



## Abilities

> The mindless clay golem is an uncomplicated opponent, and in combat attempts to batter its opponents into submission using its powerful fists. The wounds it causes are cursed. They do not heal naturally, and only the most experienced spellcasters are able to heal them via magical healing.
> Once per day, the normally lumbering golem can move at frightening speed for a short period.
> In common with most golems, they are immune to all but a handful of spells—typically those that affect earth. Acid attacks actually heal them.
> There is a flaw in the method of constructing clay golems; the elemental spirit that powers them is imperfectly bound. There are numerous tales of clay golems going berserk under stress, attacking the nearest creature or object regardless of any orders it may have. There is no known way of re-establishing control once a clay golem goes berserk


## Construction

> The golem's body is crafted from a single block of clay of at least 1,000 pounds in weight. Skill at either sculpture or pottery is required to create the final form, which is then treated with special oils and powders. Various spells are then cast to animate the golem; these spells are outside the scope of most arcane magicians, so clay golems are generally created by [[Cleric|clerics]].


## Variants


### Palanquin golem

> Palanquin golems, which were developed in [[Osirion]], lack the ability to increase their speed and are permanently attached to stone platforms that carry passengers. They are unable to fight, but there is no chance of them going berserk.


### Dero clay golem

> [[Dero|Deros]] have discovered how to create variant clay golems from the black sludge they remove from their mines at the bottom of the Makers' Mark, a great rift in the underground ruined city of [[Ilvarandin]].










