# Technology Guide

This section attempts to convert all the supplementary material to the Iron Gods adventure path that still need to be included to actually run it within 2e. Most of it will be entries from the *[Technology Guide](https://paizo.com/products/btpy98i0?Pathfinder-Campaign-Setting-Technology-Guide)* but some may be homebrewed extras to help with the conversion.

Please note that there will be **MAJOR SWEEPING CHANGES** to many items. As a GM you may wish to discuss with your players how these items are presented and what they consider to be the most important thing when converting an item, and develop your own take on things from there.

## Looking for Items?

This document covers general concepts and mechanics for an adventure in Numeria. For individual item lists, please check out the following:

* [Weapons](Weapons/README.md)
* [Armor](Armor/README.md)
* [Pharmaceuticals](Pharmaceuticals/README.md)
* [Gear](Gear/README.md)
* [Cybertech](Cybertech/README.md)

## New Traits

To see an overview of the traits that were added, please click [here](/Traits/README.md).

## Table of Contents

* [Silverdisks](#silverdisks)
* [New Actions](#new-actions)
  * [Identify Technology](#identify-technology)
  * [Identify Pharmaceutical](#identify-pharmaceutical)
* [New Spells](#new-spells)
  * [Technomancy](#technomancy)
  * [Detect Radiation](#detect-radiation)
  * [Rebuke Technology](#rebuke-technology)
* [Color Grading](#color-grading)
* [Timeworn Technology](#timeworn-technology)
* [Technological Radiation](#technological-radiation)
* [Numerian Fluids](#numerian-fluids)
* [Skymetals](#skymetals)
  * [Glaucite](#glaucite)
  * [Siccatite](#siccatite)

## Silverdisks

Silverdisks are [batteries^](Gear/README.md#battery) that no longer function. They are often used as a secondary currency in Numeria.

One silverdisk is worth 1gp.

## New Actions

### Identify Technology

**Traits:** Concentrate, Exploration, Secret

You can identify the nature of a technological item with 10 minutes of testing. If your attempt is interrupted in any way, you must start over. Attempt a Engineering Lore check. You may instead make Crafting check at a -5 penalty.

If you have a [zipstick^](Gear/README.md#zipstick) on hand you can expend a use to gain a +2 circumstance bonus to your check.

The DC of the item being identified is the same as its listed Craft DC.

* **Success** You identify the item and the means of activating it.
* **Failure** You fail to identify the item, but can try again.
* **Critical Failure** You misidentify the item as another item of the GM's choice.

### Identify Pharmaceutical

**Traits:** Concentrate, Exploration, Secret

**Requirements:** You have alchemist's tools.

You can identify the nature of a pharmaceutical item with 10 minutes of testing. If your attempt is interrupted in any way, you must start over. Attempt a Engineering Lore check. You may instead make Crafting check at a -5 penalty.

The DC of the item being identified is the same as its listed Craft DC.

* **Success** You identify the item and the means of activating it.
* **Failure** You fail to identify the item, but can try again.
* **Critical Failure** You misidentify the item as another item of the GM's choice.

## New Spells

### Technomancy

![Technomancy](Technomancy.png)

* [JSON](Technomancy.json)
* [PDF](Technomancy.pdf)

### Detect Radiation

![Detect Radiation](DetectRadiation.png)

* [JSON](DetectRadiation.json)
* [PDF](DetectRadiation.pdf)

### Rebuke Technology

![Rebuke Technology](RebukeTechnology.png)

* [JSON](RebukeTechnology.json)
* [PDF](RebukeTechnology.pdf)

## Color Grading

Technology with various grades sometimes use a color-based grading scale. The mapping is as follows.

Color Grade | Level
------------|------
Brown       | 1
Black       | 3
White       | 5
Gray        | 7
Green       | 9
Red         | 11
Blue        | 13
Orange      | 15
Prismatic   | 17

## Timeworn Technology

Items with the Timeworn trait are worth 50% of its original value, cannot be recharged - gaining the Consumable trait - and has a 50% chance of glitching under the following circumstances:

* When the item is used for the first time in a month or more of inactivty
* Any time a single-use consumable is used
* When using the item would drain its last charge
* When using an item requires a roll of a d20 and the roll results in a natural 1
* When a critical hit is confirmed against the wearer of an active defensive item, such as armor or a force field.

When an item glitches, roll a d% on the corresponding table.

### Armor Glitches

as inside cover of the Technology Guide.

### Pharmaceutical Glitches

d%     | Glitch
-------|-------
01-02  | Spoiled. Treat as poisoning by [violet venom](http://2e.aonprd.com/Equipment.aspx?ID=651).
03-11  | Spoiled. Treat as exposure to [fly pox](http://2e.aonprd.com/Diseases.aspx?ID=20).
12-20  | Spoiled. Patient is fascinated by the ceiling for 1d6 rounds.
21-30  | Spoiled. Patient is sickened 1 for 1d6 x 10 minutes (Fort DC 15)
31-40  | Spoiled. Pharmaceutical has no effect.
41-50  | Less potent. Decrease all save DCs by 2. Use minimum values for all dice rolls in effects. Decreasure durations by 50%.
51-60  | Normal effect, but patient needs to make a DC 15 Fortitude save or be drained 1.
61-75  | Normal effect, but patient needs to make a DC 15 Will save or be fascinated by the ceiling for 2d4 rounds.
76-85  | Normal effect.
86-95  | More potent. Increase any save DCs by 2. Reroll any result of 1 for effects. Increase duration by 100%.
96-100 | Far more potent. Increase any save DCs by 2. Reroll any result of 1 for effects. Increase duration by 100%. Count as two doses.

### General Glitches

as inside cover of the Technology Guide.

### Weapon Glitches

as inside cover of the Technology Guide.

## Technological Radiation

Technological radiation is a mostly invisible hazard that suffuses a spherical area and can extend into objects. Each area of radiation has an associated intensity stepping up from Low to Medium to High to Severe, and the areas work the same way as listed on *[Technology Guide, pg. 55-56](https://www.d20pfsrd.com/gamemastering/traps-hazards-and-special-terrains/hazards/environmental-hazards/radiation/)*.

Whenever a creature enters or starts their turn in an area of technological radiation, they make a single Fortitude save. On a failure, they become drained and afflicted with Radiation Poisoning, with the value and stage dependent on the intensity of radiation they were exposed to. This drained condition cannot be lowered by a full-night's rest.

Intensity | Fort DC | Drained value | Radiation Poisoning
----------|---------|---------------|--------------------
Low       | 13      | 1             | Stage 1
Medium    | 17      | 2             | Stage 2
High      | 22      | 3             | Stage 3
Severe    | 30      | 5             | Stage 5

### Radiation Poisoning

**Traits** Poison

**Saving Throw** see table above; **Onset** 1 day; **Stage 1** enfeebled 1 (1 day); **Stage 2** enfeebled 2 (1 day); **Stage 3** enfeebled 3 (1 day); **Stage 4** enfeebled 4 (1 day); **Stage 5** enfeebled 5 (1 day)

## Numerian Fluids

This is a section from *[Numeria, Land of Fallen Stars, pg. 28-29](https://paizo.com/products/btpy978l?Pathfinder-Campaign-Setting-Numeria-Land-of-Fallen-Stars)* that can come up in this adventure path.

**Traits** Alchemical, Drug, Ingested

**Saving Throw** DC 20 Fortitude; **Stage 1** +2 item bonus to Perception and a side effect on the Numberian Fluids table (see below) (1 hours); **Stage 2** fascinated and stupefied 2 (6 hours);

d%    | Result
------|-------
01    | The drinker's cellular structure breaks down, and their flesh dissolves off their bones. The victim dies in 1 round unless the *[regenerate](http://2e.aonprd.com/Spells.aspx?ID=248)* or *[wish](http://2e.aonprd.com/Spells.aspx?ID=377)* spell is administered.
02-04 | The drinker permanently loses a random sense (roll 1d4: 1 - hearing, 2 - sight, 3 - smell, 4 - taste). A *[regenerate](http://2e.aonprd.com/Spells.aspx?ID=248)* spell can restore it.
05-07 | The drinker ages 2d10 years.
08-10 | The drinker becomes sickened 6 and gains another side effect on this table. Reroll any result less than 15.
11-15 | The drinker becomes drained 2.
16-20 | The drinker becomes stupefied 4 and loses the ability to speak or write for 1 day.
21-30 | The drinker becomes confused.
31-35 | The drinker becomes enfeebled 2 and clumsy 2
36-40 | The drinker becomes unconscious.
41-50 | The drinker becomes stupefied 1.
51-60 | The drinker becomes sickened 1.
61-65 | The drinker becomes fascinated. Any attempts to disrupt the fascination causes the drinker to become confused.
66-70 | The drinker exudes an unpleasant stench (aura, olfactory). A creature entering this aura must succeed at a DC 20 Fortitude save or be sickened 1 (plus slowed 1 for the same duration on a critical failure).
71-75 | The drinker gains increased empathy with mechanical minds. It gains a +10 item bonus on Deception, Diplomacy and Perception checks against androids and robots, but a -5 item penalty against anyone else.
76-80 | The drinker becomes healed by a random energy type (acid, cold, fire, electricity or sonic) instead of harmed, but being healed this way inflicts stunned 1.
81-85 | The drinker's skin thickens into armor-like plates. This gives a +2 bonus to AC but they become clumsy 2. It takes 1d4 months for the skin to slough off.
86-90 | Roll twice. If the first result is below 20, add 20 to the result. If the second result is above 80, deduct 20 from the result. If it's the same roll twice, apply it once.
91-92 | The drinker gains fast healing 5 for 24 hours, but must consume twice as much food and water as normal.
93-94 | The drinker gains a +6 status bonus to a random ability score for the next 2d4 days.
95-96 | The drinker gains telepathy with a range of 100 feet for 2d4 days.
97    | The drinker gains the ability to see possible futures a few seconds ahead for 24 hours. They become fascinated. When they perform an attack roll, a skill check or a saving throw, they may declare to use the vision's guidance to reroll and take the better result. This ends the fascinated condition and the visions.
98    | The drinker becomes 1d6 years younger.
99    | The drinker foresees their death in a cryptic and disjointed vision. The next time an effect would cause their death, they can take an extra action just before they die.
100   | Roll on the exceptional Numerian Fluid Effects table below for a permanent effect!

d10 | Result
----|-------
1   | The drinker no longer dies of old age.
2   | The drinker permanently becomes under the effect of a mutagen that suits their personality.
3   | The drinker gains the ability to become incorporeal for 1d4 rounds as an action by becoming drained 1. Coming out of a phase while inside of a solid object is instantly fatal.
4   | The drinker gains either scent or echolocation as an imprecise sense of 30 feet.
5   | The drinker grows a pair of batlike wings that grant a fly speed of 25 feet.
6   | The drinker gains a +2 untyped bonus to a random ability score.
7   | The drinker's body begins to produce its own Numerian fluids, save for the fact it cannot produce exceptional effects (reroll rolls of 100).
8   | The drinker grows a metal mesh surrounding their skin which grants electricity resistance 10.
9   | The drinker's body constantly emits as much light as a hooded lantern. They may use a concentrate sustained action to suppress this effect.
10  | For 24 hours, the drinker falls into a coma and cannot be awakened. During this time, they dream of living an entire lifetime on a different planet in an alien body. The drinker gains the Bardic Lore skill at Master proficiency when they wake.

## Skymetals

### Glaucite

Glaucite is an alloy of adamantine and steel that's 1.5x as heavy as steel but not much better than it. Glaucite is what the *Divinity*'s hull is made from, which is why scavengers leave these ships mostly in tact. For the sake of determining Hardness and HP for objects (likely structures if you're looking here), glaucite performs the same as steel.

Item       | Level | Hardness | HP | BT
-----------|-------|----------|----|----
Thin item  | 1     | 5        | 20 | 10
Item       | 1     | 9        | 36 | 18
Structure  | 1     | 18       | 72 | 36

### Siccatite

**Traits** Rare, Cold or Fire, Precious

Siccatite is a shining silver metal that is either incredibly hot or freezing cold when found. With regards to its hardness, it is comparable to iron or steel.

Item           | Level | Hardness | HP | BT
---------------|-------|----------|----|----
**Thin item**  |
Standard-Grade | 9     | 5        | 20 | 10
High-Grade     | 17    | 8        | 32 | 16
**Item**       |
Standard-Grade | 9     | 9        | 36 | 18
High-Grade     | 17    | 12       | 48 | 24
**Structure**  |
Standard-Grade | 9     | 18       | 72 | 36
High-Grade     | 17    | 24       | 96 | 48

Compared to other rare skymetals, unprocessed siccatite is more expensive than expected by the virtue of it being a difficult material to transport - hot siccatite will eventually ignite items and cold siccatite will quickly surround itself with a 1-foot thick shell of ice in water. Physical contact with siccatite objects deal 1 point of damage - fire damage for hot siccatite and cold damage for cold siccatite - per round.

* Siccatite Chunk **Price** 1,000 gp; **Bulk** L
* Siccatite Ingot **Price** 10,000 gp; **Bulk** 1
* Siccatite Item (Standard-Grade) **Level** 9; **Price** 500 gp/bulk
* Siccatite Item (High-Grade) **Level** 17; **Price** 8,000 gp/bulk

#### Siccatite Armor

**Traits** Rare, Cold or Fire

An armor made entirely out of siccatite is unviable, as the extreme temperatures make it dangerous to wear. However due to its insulating properties there are still some that desire to incorporate components made from siccatite into their armor.

Hot siccatite armor grants cold resistance 5, negates the damage from severe cold and reduces damage of extreme cold to severe cold. Similarly, cold siccatite armor grants fire resistance 5, negates the damage from severe heat and reduces damage of extreme heat to severe heat.

Armor                            | Level | Price                          | Crafting Requirements
---------------------------------|-------|--------------------------------|-----------------------------------------------
Siccatite Armor (Standard-Grade) | 11    | 1,100 gp (+110 gp per bulk)    | at least 110 gp of siccatite of the same type + 11 gp/bulk.
Siccatite Armor (High-Grade)     | 17    | 14,000 gp (+1,400 gp per bulk) | at lease 3,500 gp of siccatite of the same type + 350 gp/bulk.

#### Siccatite Shields

**Traits** Rare, Cold or Fire

Like siccatite armor, siccatite shields provide resistance 5 to the opposite energy damage (cold for hot siccatite and fire for cold siccatite) when the Shield Block reaction is used in addition to its hardness. In addition if you raise a siccatite shield against a spell attack that would deal energy damage of the opposing type you gain a +2 circumstance bonus to your AC.

Shield                             | Level | Price     | Hardness | HP | BT | Craft Requirements
-----------------------------------|-------|-----------|----------|----|----|----------------------
Siccatite Buckler (Standard-Grade) | 10    | 900 gp    | 3        | 12 | 6  | 113 gp of siccatite of the same type.
Siccatite Shield (Standard-Grade)  | 10    | 1,000 gp  | 5        | 20 | 10 | 125 gp of siccatite of the same type.
Siccatite Bucker (High-Grade)      | 15    | 6,000 gp  | 6        | 24 | 12 | 3,000 gp of siccatite of the same type
Siccatite Shield (High-Grade)      | 15    | 6,600 gp  | 8        | 32 | 16 | 3,300 gp of siccatite of the same type

#### Siccatite Weapons

**Traits** Rare, Cold or Fire

Siccatite weapons deal 1 additional point of damage of the appropriate energy per weapon damage die on a successful Strike, but the wielder of the weapon takes the same damage for each round it is used in combat at the end of their turn.

On a critical hit, the target takes the additional precision damage as persistent damage (e.g. critically hitting with a *+1 striking hot siccatite longsword* and a +3 strength modifier would deal 2 x (2d8+3) piercing damage, 2 fire damage and 2 persistent fire damage).

As with other precious materials, 10 pieces of ammunition made from siccatite costs as much as a siccatite weapon of 1 bulk, and unless the ammunition is stored in a place that requires the equivalent of a reload 1 trait on the weapon, the user takes the additional damage per round at the end of their turn as if they were wielding a siccatite weapon.

Weapon                            | Level | Price                          | Crafting Requirements
----------------------------------|-------|--------------------------------|-----------------------------------------------
Siccatite Weapon (Standard-Grade) | 12    | 1,600 gp (+160 gp per bulk)    | at least 200 gp of siccatite of the same type + 20 gp/bulk.
Siccatite Weapon (High-Grade)     | 19    | 32,000 gp (+3,200 gp per bulk) | at lease 16,000 gp of siccatite of the same type + 1,600 gp/bulk.
