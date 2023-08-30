
---


Level: 10
Type:
- Dragon
- Fire
Alignment: Lawful Evil
Size: Large
CR: 10
Environment: Temperate marshes and plains


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
source: "B2"
name: "Peluda"
level: "Creature 10"
alignment: "LE"
size: "Large"
trait_03: "Dragon"
trait_04: "Fire"
modifier: 21
perception:
  - name: "Perception"
    desc: "Perception +21; __darkvision__;"
languages: "Draconic; "
skills:
  - name: "Skills"
    desc: "__Athletics__: +23 (1d20+23); __Intimidation__: +19 (1d20+19); "
abilityMods: [7, 3, 5, -2, 5, 3]

abilities_mid:
  - name: "Vulnerable Tail"
    desc: "  If the peluda takes 30 or more slashing damage from a critical hit, the attacker severs the peluda's tail. The peluda takes 2d6 (2d6) [[persistent damage|persistent bleed damage]] and can't make tail attacks until their tail grows back (in about 1 week)."
  - name: "Quill Thrust"
    desc: "⬲ __Trigger__ A creature within 10 feet attempts a melee [[Strike]] against the peluda __Effect__  The peluda shifts their position and makes a quill [[Strike]] against the attacking creature. This [[Strike]] doesn't count toward the peluda's multiple attack penalty, and the peluda's multiple attack penalty doesn't apply to this [[Strike]]."
abilities_bot:
  - name: "Breath Weapon"
    desc: "⬺ ([[evocation]], [[fire]], [[primal]]);  The peluda breathes a torrent of flames that deals 7d10 (7d10) fire damage in a 60-foot line (DC 29 basic Reflex save). They can't use their Breath Weapon again for 1d4 (1d4) rounds."
  - name: "Peluda Venom"
    desc: " ([[poison]]);  __Saving Throw__ DC 29 Fortitude. __Maximum Duration__ 6 rounds __Stage 1__ 2d6 (2d6) poison and [[flat-footed|flat-footed]] (1 round) __Stage 2__ 2d6 (2d6) poison, [[enfeebled|enfeebled 1]], and [[flat-footed|flat-footed]] (1 round) __Stage 3__ 2d6 (2d6) poison, [[enfeebled|enfeebled 2]], and [[flat-footed|flat-footed]] (1 round)"
  - name: "Quill Barrage"
    desc: "⬺  The peluda bristles their quills and shakes, sending dozens of spear-like barbs in every direction. All creatures within 30 feet take 11d6 (11d6) piercing damage (DC 29 basic Reflex save) and are exposed to peluda venom if they take any damage. The peluda can't use Quill Barrage again for 1 minute."

speed: 30 feet, swim 30 feet

ac: 30
armorclass:
  - name: AC
    desc: "30; __Fort__: +21 (1d20+21); __Ref__: +17 (1d20+17); __Will__: +19 (1d20+19);"
hp: 170
health:
  - name: HP
    desc: "170;  __Immunities__ fire, paralyzed, sleep;"


attacks:
  - name: Melee
    desc: "⬻ jaws +23 ([[reach|reach 10 feet]]); __Damage__ 2d12+13 (2d12+13) piercing"
  - name: Melee
    desc: "⬻ quill +23 ([[agile]], [[reach|reach 10 feet]]); __Damage__ 2d6 (2d6) piercing plus peluda venom"
  - name: Melee
    desc: "⬻ tail +23 ([[reach|reach 15 feet]], [[versatile piercing]]); __Damage__ 2d6+13 (2d6+13) bludgeoning plus Improved Knockdown"

sourcebook: "_Bestiary 2_, page 196."
```

```encounter-table
name: Peluda
creatures:
  - 1: Peluda
```

````



> **Peludas** are a species of aggressive lesser [[Dragon|dragon]] most notable for the sharpened, [[Poison|poisonous]] quills which cover most of their bodies and their uniquely vulnerable tails.



## Appearance

> Peludas are large, wingless draconic beasts with long, sinuous necks ending in [[Serpent|serpent]]-like maws. Their bodies are covered in hundreds of sharpened black quills, they walk on [[Elephant|elephantine]] limbs, and possess a long, lashing tail. The average adult peluda is 15 feet long, weighs about 300 pounds, and is able to raise its head up to eight feet off the ground.


## Habitat & Ecology

> Peludas have a preference for inhabiting caves near temperate rivers, marshes, and plains, where they serve as potent predators with a voracious appetite; though they occasionally leave their lairs in order to attack neighboring farmlands before returning back to whence they came. Their preferred means of preparing their food is roasting it with their flame breath before pulverizing it with blows from their tails. In order to aid with feeding, they are capable of unhinging their jaws in a similar fashion to [[PathfinderWiki/Creatures/Snake|snakes]] in order to swallow large portions of food at once. Due to their [[PathfinderWiki/Items/Armors/Armor|armored]] hide and poisonous quills, peludas are rarely preyed on by larger creatures such as [[Roc|rocs]] or [[True dragon|true dragons]], being largely considered to be unappetizing. Peludas lay up to three eggs at a time, with their offspring being born bald. Few of them are able to reach adulthood, not just due to predators but also due to the violent tempers of their own parents.
> While not as intelligent as other species of dragons, peludas possess a strong survival instinct, and also have a tendency of accumulating hoards of materials which perk their interest, such as [[Metal|metallic]] tools, armor and [[Weapon|weapons]] from victims they have slain. They believe that swallowing [[Coin|coins]], [[Gem|gems]] and other forms of jewelry helps strengthen their quills and their breath attacks. They loathe all creatures smaller than themselves, having a particular distaste for [[Humanoid|humanoids]].


## Society

> Peludas are generally solitary, living at most in pairs. However, despite their hatred for humanoids, tribes of savage beings such as [[Orc|orcs]] and [[Lizardfolk|lizardfolk]] may be able to appease a local peluda with offerings of wealth and captives due to their belief that the peluda is [[Divine|divine]]. While peludas themselves rarely hold any affection for these self-declared subordinates, they may nonetheless choose to revel in their worship in order to feed their fragile draconic egos, having the opportunity to be adored as are the true dragons they envy. However, should any so-deemed lesser creature go as far as suggest the peluda is not as mighty as a true dragon, the beast is likely to raze the tribe off the map altogether in a terrible, flaming anger.


## Abilities

> The body and tail of a peluda is covered in sharpened, lance-shaped quills which possess a strong poison capable of eating away at the victim's constitution. Attempting to strike the dragon in melee or grappling them is enough to put the attacker in danger of being stung by these quills, and the peluda also has the ability of launching them as a barrage by violently shaking itself. The presence of a peluda in an area is often marked by the carcasses of their prey being covered in these quills. The creatures also possess the ability to breathe out a line of flame, and their strong hide grants them resistance against non-magical weapons and [[Spell|spells]], as well as immunity to fire.
> Despite their great strength, however, a peluda's tail is particularly vulnerable. Severing the tail of a peluda not only negates the dragon using it as a weapon to defend itself, it also causes the creature to suffer from strong blood loss until its eventual death, even if the peluda manages to fight off its attackers.




## External links

> - [[httpenwikipediaorgPeluda|WikipediaPeluda]] (real-world mythological dragon)







