---

Alignment: True neutral
Racespecies: Human
Class:
- Commoner 

Gender: Male
Organization:
- None
Homeland: Dustpawn, Isger
tag: 👤️
---

> [!infobox]+
> #  `= this.file.name`
> ![[Pasted image 20230629121714.png]]
> ##### Stats
> Type | Stat |
> :---: |:---:|
> **Alignment** | `= this.Alignment` |
> **RaceSpecies** | `= this.Racespecies` |
> **Class** | `= this.Class` |
> **Gender** | `= this.Gender` |
> **Homeland** | `= this.Homeland` |


>**Adramas Mevron** is a somewhat short and robust middle aged man from the city of [[Dustpawn]], [[Isger]].
> Adramas lived is whole life in the small goat raising town, where he managed to create a family and a few good friends. Coming from a family of goat breeders Adramas inherited the job, as well as a few beasts.
> His marriage came relatively early, when he was 17 and his wife, Camelia, 15. They now have three children (Mede, Cillian, Aramas). The family is tightly knit together, having only some minor discussion with the eldest, Mede, who feels she's coming of age and aspires to something more than goat breeding.
> Though many in the town know of [[Elladas Demos]]' smuggling activity, only a selected few get to take part and profit off it. Adramas has been forever trying to get in on the action, but only managed to help the smugglers in a couple occasions, making some money and growing ever more desiring of a part of it. Whilst his wife is contempt with what they have, Adramas has, in a way, transmitted his greed for sonething more to youg Mede. 
> In a foolish attempt to impress the owner of [[Demos Leather Goods]] Mede offered as a guard of sort during one of the smuggling trips to [[Druma]].
> During the trip her carovan was attacjed by [[Hobgoblin]]s and [[Bestiary/Goblin]]s from the mountain tunnels. 
> Barely escaping alive Mede managed to return home, heavily injured.
> This mishap put Adramas in debt with [[Elladas Demos]], who blames the young girl for having fled the carovan instead of defending it.

---
>[!question] **Open Questions for the master**
> 1. How does Adramas feels towards Mede and Elladas now?
> 2. Is the man gonna repay is debt?
> 3. What role will his wife play in these events?


````ad-info
title: Statblock

```statblock
columns: 2
forcecolumns: true
layout: Path2eBlock
statblock: true
source: "GMG"
name: "Commoner"
level: "Creature -1"
alignment: "N"
size: "Medium"
trait_03: "Human"
trait_04: "Humanoid"
modifier: 3
perception:
  - name: "Perception"
    desc: "Perception +3;"
languages: "Common; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +5 (1d20+5); __Society__: +2 (1d20+2); __Lore (any one related to their trade)__: +6 (1d20+6); "
abilityMods: [3, 1, 2, 0, 1, 0]

abilities_bot:
  - name: "Power of the Mob"
    desc: "  When three or more commoners are adjacent to each other, each commoner gets a +1 circumstance bonus to Athletic checks to [[Shove]], attack rolls, and damage rolls."
abilities_top:
  - name: Items
    desc: "sickle;"

speed: 25 feet

ac: 13
armorclass:
  - name: AC
    desc: "13; __Fort__: +6 (1d20+6); __Ref__: +3 (1d20+3); __Will__: +3 (1d20+3);"
hp: 10
health:
  - name: HP
    desc: "10; "


attacks:
  - name: Melee
    desc: "⬻ sickle +5 ([[agile]], [[trip]]); __Damage__ 1d4+2 (1d4+2) slashing"
  - name: Ranged
    desc: "⬻ rock +3 ([[thrown|thrown 10 feet]]); __Damage__ 1d4+2 (1d4+2) bludgeoning"

sourcebook: "_Gamemastery Guide_, page 214."
```