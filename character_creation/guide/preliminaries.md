---
title: Character Creation - Preliminaries
description: Things you need to know before starting character creation
---

When creating a character, you record all the information you need about them onto a character sheet.
This sheet (in reality, sheets) is what you bring along to a session when you're playing as that character, and lets you keep track of things like the spells your character has access to, their current hit points (HP), what skills they have, etc.

Character sheets can vary in format, but ultimately all contain the same information.
For this session, we'll be using the standard 5e template - you can find this [online as a fillable PDF here](TODO:link to fillable char sheet) or you can print out a blank copy and fill it in by hand.
We would recommend also keeping a spare sheet of paper / empty text document alongside you during the character creation process too, so you can write down the details of all of your class and racial abilities.
You'll write these things down on your sheet too, but typically the templates you find online don't have space for both the description of your abilities and how many uses you have for them - an extra sheet of plain paper helps in that regard!

Throughout this guide we'll assume you haven't made a DnD character before, and will try to explain as much is necessary.
We might reference some of the core player rules to give context or specific examples - again don't worry if you've never played before, one of us will be happy to explain.

## Reading the Character Sheet, page 1

We'll go through each part of the character sheet in sequence, explaining the information that it contains.

![](char-sheet-image-annotated) TODO MAKE ME!!!!!

### Character Information

This section contains your character's name, level, class, and (if we were tracking experience) their experience points to next level.

You cna also describe your character's personality, alignment, and other character traits in the box provided.
These are intended as a quick reference for yourself - there is space further down the character sheet to put detailed background information about your character.

Your character background also goes in here if you took one of the default backgrounds from the player's handbook.

### Ability Scores

Your character's ability scores describe (broadly) how good your character is in particular situations, at least one "score" will usually affect anything you want to do.
The 6 ability scores are:

- Strength (STR): How physically strong and athletic you are.
- Dexterity (DEX): How nimble and agile you are.
- Constitution (CON): How hardy and resilient to physical damage or disease you are.
- Intelligence (INT): How good your logical processing or powers of deduction are.
- Wisdom (WIS): How good you are at reading the environment or other people.
- Charisma (CHA): How eloquent you are in a social situation, or a measure of the force of your personality.

For player characters, ability scores cannot go below 3 nor be increased above 20.
Typically player characters will have one or two good stats (15+), one or above average stats (10-14), and a few average or below average stats (9-).
The value of an ability score dictates your modifier for dice rolls that rely on that ability score:

$$ \text{ability modifier} = \frac{(\text{ability score} - 10)}{2}, \quad \text{(rounded down)}. $$

An ability score of 10 is deemed average as this gives you a +0 modifier - your average-ness does not affect the potential outcome either way.
Every 2 points above 10 will increase your modifier by 1, so an ability score of 17 will give you a +3 modifier - your character's natural affinity for the kind of task you're doing nudges the result towards being better.
Conversely, every 2 points below 10 will _decrease_ your modifier by 1; so a character with an ability score of 9 will have a -1 modifier - they just aren't suited to the kind of task they're trying to do!

You write your _modifier_ for an ability score in the large box for that particular score (+1, +0, -2, etc).
In the smaller box underneath, you write the raw value of the score (11, 10, 7, etc).

At the start of character creation, you'll determine your ability scores and assign them to your STR, DEX, CON, INT, WIS and CHA in the order you like.
Most races provide an immediate boost to one or more of these scores at character creation too.
Most classes depend on one or two ability scores for their primary features, and offer Ability Score Improvements (ASIs) at certain level-ups to help your character improve their power.
You can use these ASIs to later increase your odd-numbered ability scores to even numbers, for example (as a score of 10 and 11 will give the same modifier of +0, but 12 will give you +1).

### Skill Proficiencies and Proficiency Bonus

Your ability scores are general measures of how good your character is at things.
Your _proficiencies_ are the specific skills, tools, languages, weapons, armour, and even vehicles your character has been trained to use (or has otherwise learnt to master).

Your proficiency bonus is based on your character's level and will be between +2 and +6.
Whenever you level up, you'll check to see if your proficiency bonus increases.

Your skill proficiencies are then recorded in the column.
Put a tick (or double-tick if you have a class that gives you _expertise_ in that skill) in all of the skills your character is trained in.
These proficiencies are typically given by your class, background, and sometimes race.
You may acquire more skills as you continue your adventures.
The space next to the small circle beside each skill is where you write the total modifier for that skill:

$$ \text{skill modifier} = \text{ability modifier} + \text{proficiency bonus (if proficient in that skill)}. $$

Every skill is tied to an ability score; for example performance is tied to CHA, athletics to STR, insight to WIS, etc.
So even if your character is untrained in that skill they might have some natural affinity that helps (or hinders!) them.

When your character attempts to do something in the story, the DM might ask for an "ability check".
In this case, you will roll a d20 and use the result to determine the outcome of your character's attempt.
You'll add to this roll the ability score the check depends on, _and_ your proficiency bonus if your character is trained in the relevant skill.

As an example, let's say your character and their friend are travelling down a road in a carriage, when a highwayman wielding a pistol pulls out in front of the carriage.
The carriage halts abruptly and the highwayman comes to the carriage window to demand you hand over your coin purse.
Whilst your friend stalls the highwayman for time, you might ask the DM "I'd like to silently slip out the other carriage door and sneak behind the highwayman".
In this case, whether your character can do this successfully is uncertain and roll dependent - the DM might ask you "make a DEX-stealth check".
You look at your character sheet - your character is trained in stealth, has a proficiency bonus of +2 and has a DEX modifier of +3.
So you roll a d20 and add three to the result - let's say you roll 14+3+2 for a total of 19.
The DM then takes in the result and tells you what happens; they might say "as you slip out of the opposite side, the carriage rocks with the shift of your weight but the highwayman doesn't notice" - congratulations, you succeeded!
But now let's imagine your character was not trained in stealth, and had a DEX modifier of -1.
In this case, your roll of 14-1 only gets you 13.
The DM might then say instead, "as you attempt to slip out of the opposite side, the weight of your movement rocks the carriage and alerts the highwayman to your presence" - your character failed the check.

The other proficiencies box is where you put proficiencies in certain tools, armour, weapons, etc.
Whenever you try to do something that uses that particular proficiency, you can also add your proficiency bonus to the roll.
The most common can of this use is weapon proficiencies - if you're trained in a weapon, you gain a bonus to hit with that weapon!
Armour proficiencies dictate what types of armour your character can wear for protection.

### Saving Throws, Health, and AC

This section contains information about each character's key values during combat.

Your saving throws work exactly like skill proficiencies above - each class is proficient in (at least) 2 types of saving throw, and you tick the boxes you are proficient in.
Saving throws represent your character's instinctive ability to avoid harm; DEX saving throws might be required to throw yourself out the way of a stampeding horse, CON saves to prevent contracting a disease, INT saves to prevent mind control, etc.

Your initiative bonus usually equals your DEX modifier, although some classes might get other benefits.
It dictates the order of turns in a fight - a higher score helps you move before the enemies do.

Your armour class (AC) is how tough it is for enemies to actively hit you with weapons, spells, or ranged attacks.
Contrary to your saving throws with you make to avoid danger, enemies trying to attack you have to beat your armour class to do damage (the same applies to _you_ trying to damage the enemies!).
It's usually a combination of the armour you're wearing, and if you have a shield or particular fighting style.
Melee-focused characters tend to have a high AC, whilst magic users tend to go without armour.

Your hit point (HP) maximum is the amount of damage your character can take until they are dead - it resets to maximum when your character rests, and increases when you level up.
Your current hit points is how much _more_ damage you can take!
Temporary hit points are bonus HP that might come from potions, spells, etc, that provide a buffer or extra protection to your character.

Hit dice can be used to regain HP when your character rests.
They are determined by your character level and class.

Death saves are what your character makes when they reach 0 HP - they don't die outright.
Instead, you have a chance to stabilise and go unconscious rather than dying outright - you keep track of this process here.

### Attacks and Equipment

The equipment box contains all of your character's gear that they have on them - weapons, armour, spell books, trinkets, torches, magic rings, etc.
It all goes in here.

The CP (copper pieces), SP (silver pieces), GP (gol pieces), EP (electrum pieces), PP (platinum pieces) boxes are used to track currency.

The three "attunement" boxes are used to keep track of how many magic items your character is attuned to - some powerful magic items require your character to bond with the item to gain it's benefits, and you can only do so to three such items at a time.

The attacks box can be used as a quick reference for the types of attacks you can make in combat, and the damage they do.
A fighter with a greatsword might write the following row into this box for example:

```bash
Greatsword, +STR +Proficiency bonus to hit, 2d6 + STR slashing damage. 
```

This means that whenever they attack with their greatsword, they add their STR modifier and proficiency bonus to the roll to hit.
If they hit, they then roll 2d6 and add their STR modifier to determine how much damage they do.
"Slashing" is a particular type of damage that their weapon does.

A wizard however might want to write down how good they are at attacking with their spells:

```bash
Spell attack, +INT +Proficiency bonus to hit
```

This means that whenever the wizard makes a spell attack, they add their INT modifier and proficiency bonus to the roll to hit.
Since different spells do different damage, they'll then have to look at their spells section to determine the damage they do if they hit.

### Features and Traits

In this box you should put your abilities provided by your class, race, or any feats you have taken.
The box isn't very big, so the best thing to do here is:

- Put the name of each ability your character has in a list, in this box.
- If that ability has limited uses, put some checkboxes next to it so you can track them quickly.
- On your spare sheet of paper, write down what the ability does so you have a reference!

## Reading the Character Sheet, page 2

Page two is the place to put background information about your character.
What do they look like?
Where are they from?
Why are they adventuring?
What particular prized possessions do they have?

## Reading the Character Sheet, page 3

All of the spells!
If your class or race provides you with spellcasting abilities, this is the place they go.
The amount of spells you can cast before you need a rest is measured by "spell slots", whilst the "power" of spells is measured by "spell levels".
To cast a level 2 spell, you need at least one level 2 (or higher) spell slot available to you.
Level 0 spells are called cantrips and can be spammed indefinitely without using up any resources.

Your class will dictate how many spells you know, and how many spell slots you have.

Your spellcasting ability will also be dictated by your class, and is typically one of INT, WIS, or CHA.
This is the ability modifier that you add to all of your spell-related checks and attacks; Sorcerers use CHA for their spellcasting since their magic is innate to them, whereas wizards use INT since their spells are learnt rather than inherent.

Your spellcasting ability then dictates your spell save DC (difficulty class) and your spell attack bonus (again plus a formula from your class).
Your spell save DC reflects how hard your spells are to resist - if you attempt a _charm person_ spell for example, the target has to beat your spell save DC in a saving throw or suffer the consequences.

## [Next: Determining Ability Scores](./ability-scores.md)

## [Prev: Character Creation Overview](../index.md)