---

Level: 8
Type:
- Amphibious
- Dragon
Alignment: Lawful Evil
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
source: "B1"
name: "Young Green Dragon"
level: "Creature 8"
alignment: "LE"
size: "Large"
trait_03: "Amphibious"
trait_04: "Dragon"
modifier: 16
perception:
  - name: "Perception"
    desc: "Perception +16; __darkvision__, __imprecise scent 60__;"
languages: "Common, Draconic; "
skills:
  - name: "Skills"
    desc: "__Acrobatics__: +13 (1d20+13); __Arcana__: +16 (1d20+16); __Athletics__: +17 (1d20+17); __Deception__: +14 (1d20+14); __Diplomacy__: +16 (1d20+16); __Intimidation__: +16 (1d20+16); __Nature__: +14 (1d20+14); __Occultism__: +17 (1d20+17); __Society__: +14 (1d20+14); __Stealth__: +15 (1d20+15); "
abilityMods: [5, 1, 3, 2, 2, 4]

abilities_mid:
  - name: "Frightful Presence"
    desc: " ([[aura]], [[emotion]], [[fear]], [[mental]]);  90 feet, DC 24."
  - name: "Twisting Tail"
    desc: "⬲ __Trigger__ A creature within reach of the dragon's tail uses a move action or leaves a square during a move action it's using. __Effect__  The dragon makes a tail [[Strike]] at the creature with a –2 penalty. If it hits, the dragon disrupts the creature's action."
abilities_bot:
  - name: "Breath Weapon"
    desc: "⬺ ([[arcane]], [[evocation]], [[poison]]);  The dragon breathes a toxic cloud that deals 9d6 (9d6) poison damage in a 40-foot cone (DC 25 basic Fortitude save). It can't use Breath Weapon again for 1d4 (1d4) rounds."
  - name: "Draconic Frenzy"
    desc: "⬺  The dragon makes two claw [[Strike|Strikes]] and one horn [[Strike]] in any order."
  - name: "Draconic Momentum"
    desc: "  The dragon recharges its Breath Weapon whenever it scores a critical hit with a [[Strike]]."
  - name: "Woodland Stride"
    desc: "  The green dragon ignores [[terrain|difficult terrain]] and [[terrain|greater difficult terrain]] from non-magical foliage."

speed: 30 feet, fly 120 feet, swim 30 feet; woodland stride;

ac: 28
armorclass:
  - name: AC
    desc: "28; __Fort__: +16 (1d20+16); __Ref__: +16 (1d20+16); __Will__: +17 (1d20+17);"
hp: 135
health:
  - name: HP
    desc: "135;  __Immunities__ poison, paralyzed, sleep;"


attacks:
  - name: Melee
    desc: "⬻ jaws +20 ([[poison]], [[reach|reach 10 feet]]); __Damage__ 2d10+8 (2d10+8) piercing plus 2d4 (2d4) poison"
  - name: Melee
    desc: "⬻ claw +20 ([[agile]]); __Damage__ 2d8+8 (2d8+8) slashing"
  - name: Melee
    desc: "⬻ tail +18 ([[reach|reach 15 feet]]); __Damage__ 2d8+7 (2d8+7) bludgeoning"
  - name: Melee
    desc: "⬻ horn +18 ([[reach|reach 10 feet]]); __Damage__ 1d12+7 (1d12+7) piercing"

spellcasting:
  - name: "Arcane Innate Spells"
    desc: "DC 26; __1st__ [[charm]] (2); __2nd__ [[entangle]];"
sourcebook: "_Bestiary_, page 109."
```

```encounter-table
name: Young Green Dragon
creatures:
  - 1: Young Green Dragon
```

````


