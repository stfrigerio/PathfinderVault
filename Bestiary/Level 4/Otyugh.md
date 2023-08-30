
---


Level: 4
Type: Aberration
Alignment: Neutral
Size: Large
CR: 4
Environment: Any underground


tag: 👹

---

> [!infobox]+
> #  `= this.file.name`
> ![[Otyugh.jpg]]
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
name: "Otyugh"
level: "Creature 4"
alignment: "N"
size: "Large"
trait_03: "Aberration"
modifier: 10
perception:
  - name: "Perception"
    desc: "Perception +10; __darkvision__, __imprecise scent 30__;"
languages: "Common; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +8 (1d20+8); __Athletics__: +14 (1d20+14); __Stealth__: +8 (1d20+8), (Stealth: +11 (1d20+11) in lair); "
abilityMods: [6, 2, 4, -2, 2, -2]

abilities_mid:
  - name: "Stench"
    desc: " ([[aura]], [[olfactory]]);  40 feet. A creature entering the aura must succeed at a DC 20 Fortitude save or be [[sickened|sickened 1]] (plus [[slowed|slowed 1]] for the same duration on a critical failure). On a success, the creature is temporarily immune to the [[sickened|sickened]] and [[slowed|slowed]] effects of this stench for 1 hour. Regardless of the save, while within the aura, creatures take a –2 circumstance penalty to saves against diseases. An otyugh's stench is due to the offal and refuse that it wallows in, so cleaning the creature thoroughly (with create water and sufficient scrubbing, for example) deactivates the aura, while a sufficiently plugged nose allows an individual to avoid exposure to the stench."
abilities_bot:
  - name: "Constrict"
    desc: "⬻  1d6+6 (1d6+6) bludgeoning, DC 22."
  - name: "Reposition"
    desc: "⬻  The otyugh attempts to move all creatures that it has [[grabbed|grabbed]] into other spaces within the reach of its tentacles, rolling a single [[Athletics]] check and comparing the result against each creature's Fortitude DC. On a failure, the creature remains in place, and on a critical failure, the creature is no longer [[grabbed|grabbed]]."
  - name: "Filth Fever"
    desc: " ([[disease]]);  __Saving Throw__ DC 20 Fortitude. __Stage 1__ carrier with no ill effect (1d4 (1d4) hours) __Stage 2__ [[sickened|sickened 1]] (1 day) __Stage 3__ [[sickened|sickened 1]] and [[slowed|slowed 1]] as long as it remains [[sickened|sickened]] (1 day) __Stage 4__ [[unconscious|unconscious]] ; (1 day)"

speed: 20 feet

ac: 20
armorclass:
  - name: AC
    desc: "20; __Fort__: +12 (1d20+12); __Ref__: +8 (1d20+8); __Will__: +10 (1d20+10);"
hp: 70
health:
  - name: HP
    desc: "70;  __Immunities__ disease;"


attacks:
  - name: Melee
    desc: "⬻ jaws +14 __Damage__ 2d6+6 (2d6+6) piercing plus filth fever"
  - name: Melee
    desc: "⬻ tentacle +14 ([[agile]], [[reach|reach 10 feet]]); __Damage__ 1d6+6 (1d6+6) bludgeoning plus Grab"

sourcebook: "_Bestiary_, page 258."
```

```encounter-table
name: Otyugh
creatures:
  - 1: Otyugh
```

````



> The **otyugh** is a weird-looking scavenger, sometimes called a **trash eater** or a **sewer beast**.



## Appearance

> The otyugh has a bizarre [[Anatomy|anatomy]]: its large central body is mostly mouth, with three stumpy legs and three tentacles—two with barbs, and one with numerous eyes.


## Ecology

> Their origin is unknown, but they are believed to be natural creatures rather than the result of a [[Magic|magical]] experiment. One theory is that they may be related to [[Crocodile|crocodiles]]. They can be found in both swamps and sewers; presumably they originated in swamps, but later discovered sewers to be a great source of food. They live on garbage in sewers, or on rotting [[Plant|plants]] and [[Animal|animals]] in the swamp. Few creatures can stomach eating an otyugh, so numbers are usually determined by the amount of food available.
> Courtship between otyughs takes about a month, with both parties offering more and more choice morsels of food. If the two otyughs are agreeable, at the end of this time, they agree to mate, and each gives half of its "trophies" to the other. They generally mate for life, but continue to maintain separate lairs.
> A female carries the young internally for approximately 30 days, after which they are carried in a pouch on her back. They eat the mother's blood for six months, until she expels them. Their teeth do not grow for another month, so during this time the parents chew the food for them.
> After a year, the young leave in search of lairs of their own. They are fully grown after five years, and begin to look for mates of their own.


## Habitat and society

![[Otyugh_image_1.jpg|right+hmed]] 
 An otyugh makes a surprise appearance away from the sewers.
> Otyughs are not very intelligent, but they are not mere animals. They can speak the [[Taldane|Common tongue]], and also communicate with each other via scents. However, they prefer to live alone, in a lair next to their feeding grounds. An otyugh stores in its lair all the "treasures" it has acquired when rooting through garbage.
> At irregular intervals, such as when there is a threat to their environment, an elder otyugh will give off a particularly acrid scent, which the other otyughs recognise as a call for a moot. The otyughs gather together in response to this, and each tries to out-shout the others to get its opinions heard. On rare occasions, a leader is elected to deal with the crisis.
> The moot can also be a chance for otyughs to resolve individual differences. The interested parties are each given an object to hold, and then the combatants flail and slam into each other. The last otyugh to retain possession of his object is the winner.


## Abilities

> Otyughs have tough skin and large teeth. They can also reach foes up to fifteen feet away using their tentacles. Their bite transmits the dangerous [[Diseases of GolarionFilth fever|filth fever]]. They can also be hard to spot in their lairs, as they can lie submerged with only their eye tentacle above the water.


## Variants

> There are a number of reports of **mutant otyughs**, with extra tentacles or legs, or webbed feet and gills. There are also a number of other variations discussed below.


### Corpsefeaster

> Some particularly noxious otyughs, known as **corpsefeasters**, prefer to eat dead creatures. They have the ability to vomit a shower of rotting flesh over opponents; aside from the disgusting nature of this substance, it can also transmit [[Disease|disease]].


### Oozing otyughs

> Others, known as **oozing otyughs**, secrete an acidic substance which causes additional damage to those bitten or struck by a tentacle. On the plus side, their bites are usually not diseased.


### Plaguebearer

> **Plaguebearers** are otyughs that have become infected with numerous diseases (in addition to the filth fever which all otyughs carry and to which they are immune). Plaguebearers are covered in sores and lesions, and live in considerable pain. Their bite, and also their tentacles, can inflict [[Diseases of GolarionSewer madness|sewer madness]]. Other otyughs view them as prophets, paying heed to their pain-induced babbling and helping to feed and care for them from a safe distance.


## On Golarion

> Otyughs are common in the sewer systems of [[Avistan]] and northern [[Garund]]. They are particularly common in [[Korvosa]], where their rapidly growing numbers may drive them up onto the streets in search of food. Otyughs are also a known menace of the [[Sewers Vyre|sewers]] of [[Vyre]], their domains avoided by the sinister folk that use the sewers as a subterranean thoroughfare.
> There is a self-appointed king of the otyughs in the sewers of [[Zimar]] in [[Taldor]]. He refers to himself as [[Gulreesh]], the Lord of Filth, and he demands respect from all who enter his domain.
> Otyughs are common in the [[Sodden Lands]], seemingly unfazed by the constant rainfall and other effects caused by proximity to the [[Eye of Abendego]]. Some of these have become feral, losing the ability to speak.









