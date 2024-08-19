---
layout: default
title: Combat
nav_order: 7
permalink: /combat
---

> The main version of Block, Dodge, Parry is currently in [release 2.0](https://dicegoblin.blog/out-now-block-dodge-parry-v2-0/). This SRD still reflects version 1.32, and will be updated - in time. My primary focus is perfecting and supporting the full release. Curious? Check it out on [itch.io](https://dicegoblingames.itch.io/block-dodge-parry) and [DriveThruRPG](https://www.drivethrurpg.com/product/425888/Block-Dodge-Parry--A-Levelless-Classless-Expansion-of-Cairn)!

# Combat

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

## Rounds
The game typically plays without strict literal time accounting. In a fight or circumstance where timing is helpful, use rounds to keep track of when something occurs. A **round** is roughly ten seconds of in-game time and is comprised of turns.

## Initiative & Actions
The following Initiative system is inspired by the one featured in the amazing [Errant](https://errantrpg.carrd.co/). This system works best in situations where there are two or more parties with weapons drawn, sizing each other up. 

For most moments, a regular “Make a **DEX Save** to go before the enemy” ruling (as in base _Cairn_) works perfectly fine. For more tactical depth, consider the following rules:

### Declare Actions

At the start of a **round**, each PC declares their **intentions** that round. The Warden decides what the enemies will do, and will telegraph this to some degree when prompted: _“The orc seems focused on Mirah, his sword drawn”_.

### Determine Quick Turns & Full Turns
Next, all combatants must determine whether those intentions are covered by a **quick turn** or a **full turn**.

A **quick turn** consists of a **single action**, such as:

- Making a **melee attack** or trying a **gambit** against a close opponent
- Making a **ranged attack**
- **Running away/retreating** from foes **nearby** or **further away**, or **moving** somewhere else on the battlefield.
- **Casting a fast spell** or trying a **trick**

A **full turn** consists of **moving + a single action**, or **actions that take more time**, such as:

- Moving **close** to an enemy before **making a melee attack** or **trying a gambit**
- Making a **melee attack** or **trying a gambit**, and then **moving away**
- Moving before or after making a **ranged attack**
- Casting a **spell** or **miracle**
- **Running away/retreating** from foes **close** to you, or moving **two range bands** on the battlefield.

### Determine Order (and Resolve the Actions)
Once it’s been determined whether one’s turn will be **quick** or **full**, determine the order:

- All quick turns go before all full turns. 
- If any players and enemies want to take a **quick turn**, the players make a **DEX Save** to see who gets to act before and after those enemies.
- If any players and enemies want to take a **full turn**, the players make a **DEX Save** to see who gets to act before and after those enemies.

### Optional Rule: Melee Clashes

You can use weapon properties to resolve who strikes first in a clash of melee users. This adds yet another layer of tactics (through weapon choice), but also removes some random chaos (less DEX Saves to determine who goes first).

When two combatants enter into **Close** proximity to one another (either by one combatant or both combatants moving towards the other), the **LONGER WEAPON** (i.e., the one with the most reach) strikes first. That means:

> Weapon with the **Reach** tag (polearms, spears) > **slow** weapons (d10) > **balanced** weapons (d8) > **fast** weapons (d6)

When two combatants are already in **Close** proximity attack each other, the order is **REVERSED**, meaning the **FASTER**, **SHORTER WEAPON** strikes first. That means:

> **Fast** weapons (d6) > **balanced** weapons (d8) > **slow** weapons (d10) > Weapon with the **Reach** tag (polearms, spears)

And finally, **Enhanced** attacks also go before normal attacks, and normal attacks go before **impaired** attacks.

### In Summary
So, in summary, the order will look like this:
1.	Quick turns, consisting of a single action. If any players and enemies both take a quick turn, resolve with a DEX Save.
2.	Full turns, consisting of two actions or a slow action such as casting magic or a miracle. If any players and enemies both take a full turn, resolve with a DEX Save.

## Range Bands
Distances are measured as:

- **Close**: In your face. Within punch- or sword range.
-	**Near**: In the same room as you: reachable within a few moments/quick paces. It takes one **Move Action** in combat to get here. When inside dungeons or buildings, all creatures in the same room are most likely Near each other.
-	**Far**: A few rooms away: optimal range for most ranged weapons. It takes one or multiple **Move Actions** in combat to get here.
-	**Distant**: Barely visible in the distance. It might take many Move Actions in combat to get here. By definition, Distant targets are beyond the range of ranged weapons (If they are in range, they’d be Far).

## Attacking & Damage

The Warden will declare which enemies will attack which character. The attacker rolls their **weapon die** and **subtracts** the target’s **Armor**, then deals the **remaining total** to their **opponent’s HP**. 

HP stands for your ability to **protect yourself** from hits. Unaware targets might be unable to do so, meaning damage is done straight to their **STR**. Similarly, a character with a full inventory (10 slots) is overburdened to a degree that they are unable to defend themselves.

### Unarmed Combat & Brawls

Unarmed attacks always do 1d4 damage. In a brawl, PCs can use furniture as improvised weapons. Bottle-sized objects do 1d6 damage, chair-sized objects do 1d8 damage, and table/bench-sized objects do 1d10 damage. All improvised weapons break after 1 attack. Unarmed/non-lethal attacks still do damage to STR, but failing a Critical Damage Save means the target is knocked unconscious instead.

## Block, Dodge & Parry
Before damage is rolled, a Player Character under attack has **4 options**:
- **Fight back**. Choose one attacker and deal your damage against it - after you’ve taken the incoming damage. Fighting back gives you **1 Fatigue**.
- **Block**. Any incoming **Fast** or **Balanced** attacks become **Impaired**. Blocking gives you **1 Fatigue**.
- **Dodge**. Any incoming **Slow** or **Balanced** attacks become **Impaired**. Dodging gives you **1 Fatigue**.
- **Parry**. Choose one attacking opponent that you can attack in return:
-- If you roll **higher** attack damage than they do, their dice roll is invalidated, and you deal your damage straight to their STR. This does not trigger a Critical Damage Save.
-- If the **opponent rolls higher**, the damage is dealt to your STR instead. This does not trigger a Critical Damage Save.
-- If the **two rolls are equal**, both weapons bounce off each other with a satisfying twing! and a rain of sparks. No damage is done to either party.

Each of these options is essentially a reaction – they happen in the split-second in which a PC is attacked. Some enemies might also have access to these abilities! Note that an attacking creature cannot take a reaction; if an orc blademaster strikes at a PC and the PC fights back, the orc cannot block or take similar reactions, as that could create an infinite chain of reactions.

### Optional Rule: Blocking & Dodging

By default, blocking and dodging are relatively simple processes, and quite similar to each other, only distinguished by the particular weapon used against you. To create an interesting difference between the two, consider these rules:

- **Blocking** requires a **Balanced** or **Heavy** melee weapon, or a **shield** (ruling out light weapons).
-	**Dodging** is not possible with an **Armor score** of **3**, or when wielding a **Heavy** weapon.

Optionally on top of that, instead of blocking and dodging being impossible in certain scenarios, consider:

- **Blocking** without a Balanced/Heavy melee weapon or shield **impairs** the incoming Fast or Balanced attack. 
-	**Blocking** with a Balanced/Heavy melee weapon or shield **negates** the incoming Fast or Balanced attack.
-	**Dodging** while having an Armor score of 3 or wielding a Heavy weapon **impairs** the incoming Balanced or Heavy attack. 
-	**Dodging** without an Armor score of 3 or wielding a Heavy weapon **negates** the incoming Balanced or Heavy attack.

## Multiple Attackers
If **multiple attackers** target the **same foe at the same time**, roll **all damage dice** and keep the **single highest result**. Note that a creature can still take damage at multiple moments during a round (before and after their turn, as part of Fight Back, etc.), and that these separate moments do not use a shared single highest result.

Also note that only the weapon tag/effects of the highest result are used; it’s as if only the highest result lands the blow.

## Attack Modifiers
If fighting from a position of **weakness** (such as through cover or with bound hands), the attack is **impaired** and the attacker must roll **1d4 damage** regardless of the attack's damage die. **Impaired** attacks go last in **clashes**.

If fighting from a position of **advantage** (such as against a helpless foe or through a daring maneuver), the attack is **enhanced**, allowing the attacker to roll **1d12 damage in addition to their normal die**. **Enhanced** attacks go first in **clashes**.

## Dual Weapons
If attacking with two weapons at the same time, roll **both damage dice** and keep the single highest result. 

If both weapons have different lengths for melee clashes, one of which would allow the user to go before the target and one of which would usually require a DEX Save (or go after the target altogether), the user can choose to either strike only with the quicker weapon, or wait and strike with both.

## Gambits
When making an attack, you can choose to make a **gambit**. A gambit is a move such as **stunning**, **shoving**, **disarming**, **tripping**, and so forth. Declare that you make a gambit as you declare your attack. When making a Gambit, you **do not deal damage**. 

1. Roll your Weapon Damage Dice. If you are dual-wielding, roll both, and take the highest value. 
2. If your roll is 1, 2, or 3, use this value as the Difficulty of the enemy’s Save. If your roll is 4 or higher, no Difficulty is applied. 
3. The type of Save is determined together with the Warden, and the target must roll equal to or under their Attribute but also above the Difficulty. 
4. If the target fails their Save, the gambit succeeds.  
5. If they succeed, they may immediately make an attack back.


Gambits cannot be blocked, dodged, or parried. If multiple attackers attack a single target and one or more attackers choose to perform a gambit, resolve those before checking who rolled the highest damage.

For determining the priority of Gambits in the initiative order, use the size of your weapon as described in Melee Clashes.

## Critical Damage

Damage that reduces a target’s HP below zero decreases a target’s STR by the amount remaining. 

They must then make a **STR save** to avoid **Critical Damage**. Additionally, some enemies will have special abilities or effects that are triggered when their target fails a critical damage save.

Any PC that suffers critical damage must roll a d6.

|d6|Result|
|:---|:---|
|1|You die.|
|2-5|Incapacitated - you die within the hour, unless treated.|
|6|No. Not today. You instantly regain 1d4 HP.|

### Optional rule: Critical Hit Locations

Instead of a generic 1d6 roll, roll on the following table. Interpret the results within fiction (one might get disarmed, injured in the leg, and thus find it harder to move, etc.). Upon suffering critical damage, roll a d10.

|d10|Result|Possible effect|
|:--|:---|:-------|
|1-5|Torso|Lose an additional 1d4 STR.|
|6|Left leg|Lose ability to move quickly; lose use of leg.|
|7|Right leg|Lose ability to move quickly; lose use of leg.|
|8|Left arm|Disarmament; lose use of arm.|
|9|Right arm|Disarmament; lose use of arm.|
|10|Head|Most likely lethal.|

Failing a Critical Damage Save should still have dire consequences.

Being hit on your right leg might mean rolling the next **Initiative** with **disadvantage** (roll 2d20, take the least beneficial result). Being hit there again might mean a near-amputation, meaning you automatically lose any Initiative rolls. When rolling on the Hit Locations table, add an Injury to your inventory as a form of long-term fatigue.

Any creature that has **Failed** a **Critical Damage Save** but has not died, is **Impaired** in their attacks. Damage against them is likely **Enhanced** – see what makes sense in fiction!

## Ability Score Loss

If a PC’s **STR** is reduced to 0, they die. 

If their **DEX** is reduced to 0, they are paralyzed or knocked out.

If their **WIL** is reduced to 0, they are delirious.

Complete DEX and WIL loss renders the character unable to act until they are restored through extended rest or by extraordinary means.

## Wounds

Adventuring is a dangerous profession. A way to reflect that is to use these rules for wounds. Wounds can come from a variety of sources:

- Fire (such as from a burning building or a dragon's breath) can inflict **burns**.

- Electricity (such as from magic or an ancient contraption) can inflict **nerve damage**.

- Cold (such as from weather or magic) can inflict **frostbite**.

- Poison can inflict, well, **poisoning**.

Some creatures might inflict wounds when dealing **Critical Damage**, or on special attacks. Wounds can also be gained as a cost of player action (storming into a burning tavern to save one's treasure, for instance, might inflict burns).

A wound occupies a **slot** in your **inventory**. The type of wound is mechanically just flavoring, while in fiction a character with burns might have nasty blisters.

Wounds come in 3 levels. Whenever a wound of the same type is gained, the player can choose to have their existing wound increase in severity or to fill in a new slot in their Inventory. This allows player choice between short- or long-term impact: do you suffer another mild wound and heal after combat, or stack up to possibly permanent injury?

- **Light wounds** can be healed in the field, given that proper medicine and treatment is available. Light burns can be healed by gathering the right herbs and applying them overnight, for instance.

- **Severe wounds** require serious medical attention, probably between adventures. Severe frostbite could be cured with a comfortable week-long rest in a healing temple.

- **Permanent wounds** are just that, permanent. They can never be healed. Every permanent wound also lowers a fitting Attribute by -1 (For instance, WIL for nerve damage). While this -1 penalty can be overcome in time by training, the wounds' Inventory slot is forever lost.

Wounds are intended to, once again, provide a **prompt for adventure**; curing them can tie into the Complex Tasks system, for instance!

## Retreat
Some battles cannot be won - and running away should always be a viable option. Just like in base _Cairn_, a successful **DEX Save** allows one to run away from a dangerous situation, as long as there is a safe place to run to.

Retreating from an enemy that is **nearby** or **further away**, i.e. not in melee range, takes a **single action** and can be done as a **quick turn**. 

Retreating from an enemy that is **close**, i.e. in melee range, takes **two actions** (one to create some distance, one to make the retreat attempt) and takes a **full turn**.
