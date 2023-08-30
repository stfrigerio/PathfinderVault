
---


Level: 5
Type: Fey
Alignment: Chaotic Evil
Size: Small
Adjective: Redcap
CR: 6
Environment:
- mountains
- Temperate forests
- or underground


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
> **Adjective** | `= this.Adjective` |
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
name: "Redcap"
level: "Creature 5"
alignment: "CE"
size: "Small"
trait_03: "Fey"
modifier: 12
perception:
  - name: "Perception"
    desc: "Perception +12; __low-light vision__;"
languages: "Common, Sylvan; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +13 (1d20+13); __Athletics__: +15 (1d20+15); __Deception__: +11 (1d20+11); __Intimidation__: +13 (1d20+13); __Nature__: +10 (1d20+10); __Stealth__: +13 (1d20+13); "
abilityMods: [4, 4, 2, 1, 1, 2]

abilities_top:
  - name: "Red Cap"
    desc: " ([[necromancy]], [[primal]]);  A redcap's woolen hat is dyed with the blood of its victims. If the redcap loses its cap, it no longer benefits from fast healing and takes a –4 status penalty to its damage rolls. It can create a new cap in 10 minutes, but that cap doesn't grant its powers until the redcap has turned it red with Blood Soak. A cap has no benefit for creatures other than the redcap who made it."
  - name: Items
    desc: "iron boots, red cap, scythe;"
abilities_mid:
  - name: "Divine Revulsion"
    desc: " ([[emotion]], [[fear]], [[mental]]);  If a redcap sees a creature brandish a religious symbol of a good deity (which requires an interact action by that creature) or use one to cast a divine spell, the redcap must attempt a DC 19 Will save. It then becomes temporarily immune to all brandished religious symbols for 10 minutes.\n__Critical Success__ The redcap is unaffected.\n__Success__ The redcap is [[frightened|frightened 2]].\n__Failure__ The redcap gains the [[fleeing|fleeing]] condition for 1 round and is [[frightened|frightened 4]]."
abilities_bot:
  - name: "Blood Soak"
    desc: "⬻ ([[manipulate]]);  The redcap dips its cap in the blood of a slain foe. The foe must have died in the last minute, and the redcap must have helped kill it. The redcap gains a +4 status bonus to damage rolls for 1 minute."
  - name: "Deadly Cleave"
    desc: "⬲ __Trigger__ The redcap reduces a creature to 0 Hit __Effect__  Points with a scythe [[Strike]]. The redcap makes another scythe [[Strike]] against a different creature, using the same multiple attack penalty as the scythe [[Strike]] that triggered this reaction. This counts toward its multiple attack penalty."
  - name: "Stomp"
    desc: "⬻  The redcap [[Stride|Strides]] up to half its Speed and makes a boot [[Strike]] at any point during that movement. If the boot [[Strike]] hits a [[prone|prone]] creature, it deals an extra 2d6 (2d6) [[persistent damage|persistent bleed damage]]."

speed: 50 feet

ac: 21
armorclass:
  - name: AC
    desc: "21; __Fort__: +11 (1d20+11); __Ref__: +15 (1d20+15); __Will__: +10 (1d20+10);"
hp: 60
health:
  - name: HP
    desc: "60; fast healing 10; __Weaknesses__ cold iron 5, divine revulsion ;"


attacks:
  - name: Melee
    desc: "⬻ scythe +15 ([[deadly|deadly 1d10]], [[trip]]); __Damage__ 1d10+10 (1d10+10) slashing"
  - name: Melee
    desc: "⬻ boot +13 ([[agile]], [[versatile|versatile b]]); __Damage__ 1d6+8 (1d6+8) piercing"

sourcebook: "_Bestiary_, page 278."
```

```encounter-table
name: Redcap
creatures:
  - 1: Redcap
```

````



> **Redcaps** are vicious little [[Fey|fey]] that relish the pain and suffering of other creatures. They are an embodiment of the savage, merciless side of nature. They love nothing more than cutting creatures down to size with their over-sized scythes, mushing them to paste beneath their [[Iron|iron]]-shod boots, and then soaking their caps in the bloody mess that remains.



## Appearance

> Redcaps look like small, wrinkled old men with over-sized hands and feet and huge [[Nethys/Animals and Gears/Bat|bat]]-like ears. Female redcaps have shorter, patchier beards, slimmer bodies and less hair on their hands than males. Their faces look utterly hateful topped off with small red hats. Originally white, their headwear is completely soaked in blood, sometimes dripping onto the redcap's face. All redcaps carry over-sized scythes, normally bigger even than their entire body. They also wear distinctive iron boots covered with spikes. They love nothing more than reducing a big 'un (as they call [[Humanoid|humanoids]]) to their height through cunning traps or their vicious scythes, after which they stomp their victim into a bloodied pulp.


## Habitat and ecology

> Redcaps embody the the most merciless and unpleasant aspects of nature. As such, they often do not get along well with other fey. A redcap generally shows other fey a certain minimal amount of courtesy but are not friendly to them, particularly to fey that do not fight like [[Bestiary/Nymph|nymphs]] and [[Dryad|dryads]], as they consider them too delicate or flowery. Despite this dislike, redcaps often serve as mercenaries to other less violent fey. An exception to this dislike exists in regards to the redcaps' association with the [[Cat|catlike]] fey known as [[Bestiary/Elananx|elananxes]]. The redcaps greatly admire the elananxes' cleverness and cruelty, and particularly enjoy watching multiple elananxes pursue a single target. Consequently, redcaps often go out of their way to ally with and befriend the cruel felines.
> Redcaps prefer to dwell in hills though they can be found in other types of terrain from underground to mountains. They are also often found in abandoned buildings vacated after some great tragedy. They seem to be drawn to the sense of doom that pervades these buildings.
> While redcaps are vicious hunters they are not very fond of eating flesh. They prefer to drink the blood of their victims or to suck the marrow from their bones. The main reason redcaps hunt is to keep their caps soaking in blood. Redcaps believe that if their caps are not kept constantly soaked deep red then the redcap will sicken and die. While there is little evidence of this, the redcaps believe it unquestioningly. They are so protective of their caps that some of them even sew their caps onto their scalps.
> Redcaps are believed to mate only after successful murders. Female redcaps give birth to twins or triplets after 6 to 8 months. Siblings constantly fight for the respect of others and the attention of parents, and usually only one redcap per birth survive to adulthood. Parents usually encourage this fight: those that show weakness are culled. Redcaps can live up to 60 years, but are almost always killed before that.


## Abilities

> While small in stature, redcaps are capable of wielding large weapons to great effect although their preferred method of attack is to stomp on opponents with heavy boots. A redcap's psychological attachment to its cap is so strong that without it they do not fight with nearly the same effectiveness as they do if wearing it.


## On Golarion

> Redcaps are relatively common in [[Golarion]], a [[Material Plane]] [[Planet|planet]] with a large number of [[First World]] breaches, particularly in [[Avistan]]. They are rumoured to be attracted to the [[Choking shade|choking shade]]-infested caverns of [[Hollow Mountain]], the [[Goblin|goblin]]-filled forests of the [[Lost Coast]], and several other areas in [[Varisia]].
> A small population of territorial redcaps is known to inhabit the [[Barrowmoor]] of northern [[Nidal]]. These bloodthirsty creatures attack anyone foolish enough to enter their territory. They are also said to dwell in the caverns below the fire-scarred [[Chitterwood]] in [[Isger]], where they ally with the local [[Goblin|goblin]] and [[Hobgoblin|hobgoblin]] tribes, and in the Isgeri ghost town of [[Finder's Gulch|Finders Gulch]]. A redcap named [[Mauxpaudi]] rules the [[Irrisen Land of Eternal Winter|Irrisen]] province of [[Feyfrost]]. The redcaps inhabiting the [[Fangwood 1]] are rumoured to be [[Blighted fey|blighted]], but such blighted redcaps have never been seen firsthand. They also live in [[Kyonin]] peacefully with other fey, and often terrorise the ne'er-do-wells that consider the [[River Kingdoms]] home.
> On their home plane of the First World, redcaps are known to live on the slopes of the [[Tane]] known as [[Ulas|Great Ulas]]. These redcaps venerate Great Ulas as a divine parent and protect it from those who seek to harvest the living mountain's blood for its potent [[Alchemy|alchemical]] properties.


> [[Paizo]] published a chapter about redcaps in *[[Fey Revisited]]*.








