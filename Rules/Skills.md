
While your character’s ability scores represent their raw talent and potential, skills represent their training and experience at performing certain tasks. Each skill is keyed to one of your character’s ability scores and used for an array of related actions. Your character’s expertise in a skill comes from several sources, including their [[background]] and class. In this section, you’ll learn about skills, their scope, and the actions they can be used for.
A character’s acumen in skills can come from all sorts of training, from practicing acrobatic tricks to studying academic topics to rehearsing a performing art. When you create your character and as they advance in level, you have flexibility as to which skills they become better at and when. Some classes depend heavily on certain skills—such as the alchemist’s reliance on [[Crafting]]—but for most classes, you can choose whichever skills make the most sense for your character’s theme and backstory at 1st level, then use their adventure and downtime experiences to inform how their skills should improve as your character levels up.
A character gains training in certain skills at 1st level: typically two skills from their background, a small number of predetermined skills from their class, and several skills of your choice granted by your class. This training increases your proficiency ranks for those skills to trained instead of untrained and lets you use more of the skills’ actions. Sometimes you might gain training in a specific skill from multiple sources, such as if your [[background]] granted training in [[Crafting]] and you took the alchemist class, which also grants training in [[Crafting]]. Each time after the first that you would gain the trained proficiency rank in a given skill, you instead allocate the trained proficiency to any other skill of your choice.


## Skill Descriptions

The following entries describe the skills in the game. The heading for each entry provides the skill’s name, with that skill’s key ability in parentheses. A brief description of the skill is followed by a list of actions you can use if you’re untrained in that skill, and then the actions you can perform if you are trained in that skill. Some actions list sample tasks for each rank to give you a better sense of what you can accomplish as your proficiency increases. As the actions of a skill aren’t comprehensive, there may be times when the GM asks you to attempt a skill check without using any of the listed actions, or times when the GM asks you to roll using a different key ability modifier.
Most skills include entries for success and failure, as well as descriptions of what occurs on a critical success or a critical failure. If either of the critical entries is absent, treat those results as a success or failure, as normal.


## Skill Actions

The actions you can perform with a given skill are sorted into those you can use untrained and those that require you to be trained in the skill, as shown on **Table 4–1: Skills, Key Abilities, and Actions**. The untrained and trained actions of each skill appear in separate sections within the skill’s description.
Anyone can use a skill’s untrained actions, but you can use trained actions only if you have a proficiency rank of trained or better in that skill. A circumstance, condition, or effect might bar you from a skill action regardless of your proficiency rank, and sometimes using a skill in a specific situation might require you to have a higher proficiency rank than what is listed on the table. For instance, even though a barbarian untrained in [[Arcana]] could identify a construct with a lucky roll using [[Arcana]] to [[Recall Knowledge]], the GM might decide that Recalling Knowledge to determine the spells used to create such a construct is beyond the scope of the barbarian’s anecdotal knowledge. The GM decides whether a task requires a particular proficiency rank.

```dataview
table without id
	file.link as "Skill",
	parentSkill as "Parent"

FROM "Rules/Skills"
WHERE file.name != this.file.name
SORT parentSkill ASC


```

### Improving Skills

As your character advances in level, there are two main ways their skills improve: skill increases and skill feats. Your class lists the levels at which you gain each of these improvements.

### Skill Increases

Skill increases improve your proficiency in skills of your choice. You can use these increases to become trained in new skills or increase your proficiency rank in skills you’re trained in (from trained to expert at any level, expert to master at 7th level or higher, and master to legendary at 15th level or higher). Unlike when you first become trained at a skill, if two different abilities would make you an expert, master, or legendary in a skill, you don’t get to choose a second skill to become expert in—the redundant benefit simply has no effect.

### Skill Feats

Skill feats are a type of general feat that often grant you a new way to use a skill or make you better at using a skill in a particular way. Skill feats always have the skill trait.

## Skill Checks and Skill DCs

When you’re actively using a skill, often by performing one of its actions, you might attempt a skill check: rolling a d20 and adding your skill modifier. To determine this modifier, add your ability modifier for the skill’s key ability, your proficiency bonus for the skill, and any other bonuses and penalties.
**Skill modifier = modifier of the skill’s key ability score + proficiency bonus + other bonuses + penalties**
When writing down the modifier on your character sheet, you should write down only the numbers that always apply—typically just your ability modifier and proficiency bonus at 1st level. At higher levels, you may wear or use items to improve your skills with item bonuses pretty much all the time; you should write those down, too.
The GM sets the DC of a skill check, using the guidelines in Game Mastering. The most important DCs to remember are the five simple skill DCs below.


| Task Difficulty | Simple DC |
| --------------- | --------- |
| Untrained       | 10        |
| Trained         | 15        |
| Expert          | 20        | 
| Master          | 30        |
| Legendary       | 40        |



When someone or something tests your skill, they attempt a check against your skill DC, which is equal to 10 plus your skill modifier. A skill DC works like any other DC to determine the effect of an opposing creature’s skill action.
See Playing the Game for more information about modifiers, bonuses, and penalties.

### Armor and Skills

Some armor imposes a penalty on specific skill checks and DCs. If a creature is wearing armor that imparts a skill penalty, that penalty is applied to the creature’s [[Strength]] and [[Dexterity]]-based skill checks and skill DCs, unless the action has the attack trait. Check penalties from armor are detailed in Equipment.

### Secret Checks

Sometimes you won’t know whether you succeed at a skill check. If an action has the secret trait, the GM rolls the check for you and informs you of the effect without revealing the result of the roll or the degree of success. The GM rolls secret checks when your knowledge about the outcome is imperfect, like when you’re searching for a hidden creature or object, attempting to deceive someone, translating a tricky bit of ancient text, or remembering some piece of lore.
This way, you as the player don’t know things that your character wouldn’t. This rule is the default for actions with the secret trait, but the GM can choose not to use secret checks if they would rather some or all rolls be public.

### Exploration and Downtime Activities

Some skill activities have the exploration or downtime trait. Exploration activities usually take a minute or more, while downtime activities may take a day or more. They usually can’t be used during an encounter, though the GM might bend this restriction. If you’re not sure whether you have the time to use one of these activities, ask your GM.