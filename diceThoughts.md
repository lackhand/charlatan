# dice & danger

A simple hack of old school dungeon crawling games in the vein of Into the Odd (and many other hacks).

> This is a d6-based DIY elfgame about adventurers and their explorations into funhouse dungeons.
> One of you is the DM (Narrator, Referee, Judge), and the other Players have Player Characters (the DM also has Non-Player Characters).
> Much more ink has been spilled about How To Play an RPG; go there.

Have fun!

# Players roll d6s to determine damage given or received

The _damage source_ adds (or unusually removes) the number of six-sided **d**ice of **d**amage to the pool, like +1d or +4d.
> For instance, shortswords are 1d, longswords are 2d, and polearms 3d.

The _situation_ might give advantage or disadvantage to a roll, changing the **d**is**c**ard number.
The DM is the ultimate arbiter of the total DC.
**If it doesn't say otherwise, then the DC is 4**, but an easier check might have DC 3 or even 2; a harder check might have DC 5 or even 6.
You can never have DC 1 or DC 7, which are inevitable and impossible respectively.

The _damage recipient_ removes (or unusually adds) a number of damage dice (**b**locking them), written as "2b" or "3b".
1d and 1b cancel each other out, 1 for 1, before the roll.
It's ok if this reduces the size of the dice pool below 0d.
> For instance, a small shield blocks 1b and a large shield gives 2b.

Dice showing values above the DC are **hits**. Announce the number of dice that hit as a **hit number**.
> Alice rolls 3d and gets `[1, 3, 5]` vs DC3.
> She **hits** with the `[3, 5]` and announces the count of dice that hit --  a **hit 2**.

Dice that show a 6 are **crits** and explode (roll an additional die, exploding any new crits).
Some rolls don't allow crits, and will say so -- sometimes called "no crits".
> Bob rolls 7d and gets `[1, 2, 3, 4, 6, 6, 6]` vs DC3.
> He hit with the `[3, 4]` and crit with the `[6, 6, 6]` -- a _hit 2 crit 3_ (so far!).
> He rerolls 3d and gets `[2, 4, 6]` -- a _hit 3 crit 4_ so far.
> He rerolls the new 1d that hasn't exploded yet and gets `[4]` -- a total of **hit 8**.

## Weird pool sizes

Sometimes you need to roll fewer than 1d, like 0d or -1d (such as when the pool is all block dice...).
When you roll 0d, roll 2d and pick the lowest die (leading to a smaller hit).
Do the same thing with one additional die for each number below 0.
> Alice rolls a saving throw against a rat bite at -1d.
> She rolls and picks the least-damaging result from `[1, 4, 6]`.
> The 6 _would be_ a crit and explode, but that 1 makes it a complete _miss_.

If you would otherwise roll 9d or more, assume every 6d roll `[1,2,3,4,5,6]` and roll for the remainder.
This is necessarily at least one crit.

## Players roll all of the dice.

* When a player rolls to deal damage, it's a "damage" or "dmg" roll.
  > Bob tries to stab Alizard Mann, so he rolls a pool of dice for damage he could deal.
* When a player rolls to avoid taking damage from someone else, it's a "saving throw" or "save" roll.
  > Boblin tries to stab Alice, so she rolls a pool of dice for damage she couldn't dodge.
* Sometimes the player rolls a saving throw but the stakes are more metaphorical; that's a "skill check" or "skill" roll.
  > Alice tries to avoid detection by a guard, rolling a saving throw. On a failure, she can take damage or raise the alarm.
* Sometimes, the player rolls damage against a metaphorical "project check" or "project" roll.
  > Bob tries to pick a lock, trying to rack up a number of successes during this opportune moment.

The rules still work the same way in each case!
> Obviously anyone (including the DM) might roll dice on a random table.
> That's different.
> Within the fiction of the game, the DM asks the players to roll dice when the outcome is uncertain in order to determine "how much" of something happens.

# Character Statistics

As with any game, characters (and obstacles, scenery, items, and other phenomena) have statistics to help the rules mediate their interactions.
It's the DM's job to resolve "what happens next" and should only call for the dice if the answer seems fun to randomize.

## Tier & Level

> Can my wizard knock out a dragon in one punch? Why (or why not)?

| Level | Tier | Tier Title | Notes & Examples |
|---|---|---|---|
| 0 | 0 | Common | Ordinary: a random villager, a wooden club |
| 1 | 1 | Novice | **Your new adventurer**, a precocious student; a spear or dagger |
| 2-3 | 2 | Apprentice | You after a few adventures, a guard; a martial weapon |
| 4-6 | 3 | Journeyman | A veteran soldier, a fine martial weapon |
| 7-10 | 4 | Master | A knight or wizard; a magic sword |
| 11-15 | 5 | Grandmaster | A famous knight or archmage; a flaming magic sword |
| 16-21 | 6 | Legendary | A world-famous knight or archmage; an intelligent magic sword |
| 22+ | 7+ | Demigod (or better) | A force of nature; awe-inspiring and unharnessable |
| -1 (etc) | -1 (etc) | Poor (or worse) | A giant rat, a broken wretch, a thighbone-as-club or pen-knife |


This game uses a power **tier** to suggest the power, scale, and impact of something within the game.
Each tier represents a pretty big power break to the level before it.

Within each tier, player characters have **level** to indicate slightly more fine-grained progress.
Nothing else in the world has (or needs) a level; it's just so that we can regularly give your character growth.

As a starting character, you have one Tier Point and one Level Point to spend.

## The Attributes

* **Strength:** Resist paralysis, obstacles, impediments, or melee blows; power through.
* **Reflex:** Resist missiles, blasts, surprises, and detection; evade or become aware.
* **Intelligence:** Resist confusion, amnesia, distraction or hesitation; know how to do something.
* **Will:** Resist fear, compulsion, magical or social attacks; convince or resist.
* **Health:** Resist poison, fatigue, transformation, and death; Carry more & carry on.

## Attributes

Roll 3d (no crits) for each attribute in order, then switch 2 (if you want):


Define your **Luck**, which works like your other statistics but is calculated by summing the other 5 statistics and checking the below table.
* **Luck:** Starting social standing, avoid scars, improve your character's abilities.
  * For every attribute equal to 0, increase your luck by 1.
  * For every attributes equal to 1, increase your luck by 1/2.
  * For every attribute equal to 2, increase your luck by 1/3.
  * Round down.
> Starting luck ranges from 0->5; 30% of characters start with luck 1, and 60% luck 2.

# Levels, Experience, Titles & Tiers.

Your starting character is **Level 1** with 0 e**X**perience **P**oints.
You have 1 **H**it **D**ice which you use to determine **H**it **P**oints.
You have 0 **C**ast **D**ice which you use to determine **C**ast **P**oints.

> A more ethereal character like a wizard, fairy, or goblin might begin with 0 HD and 1 CD.

Select a **Background Title** based on your **highest attribute** (if several are tied, you can choose one) and your **luck score**:

| ... | 0 | 1 | 2 | 3 | 4 |
|---|---|---|---|---|---|
| Strength (Warrior) | Barbarian | Gladiator | Guard/Soldier | Squire | Knight |
| Reflex (Hunter) | Ratcatcher | Thief | Scout/Outlaw | Ranger | Spy | 
| Health (Laborer) | Farmer | Sailor | Cook/Poisoner | Merchant | Armorer |
| Intelligence (Expert) | Tinker/Tailor | Artisan | Architect/Engineer | Herbalist | Alchemist |
| Will (Adept) | Hermit/Monk | Herald | Sorcerer | Witch | Priest |
| Luck (Noble) | Beggar | Traveler | Scribe | Entertainer | Prince |

Pick other titles for your **nationality**, **race**, **appearance**, **alignment**, or **creed** (whatever you're using in the game).
> Alice's character has a high reflex and middling luck, so she was a _scout_. She decides her character is English (and human), a stout & ruddy Protestant Kingswoman of Leeds.
> Bob's character has a high will and low luck, and so he was a _herald_. He decides his character is an enigmatic faerie Envoy from the Thistledowns, armed in fish-scales and here to ensure the Pretender claims the throne of Wales.

## Level up and spending Luck
Every level requires 1000 more experience points than the level before it did and resets your experience points to 0.
Whenever you level up, increase your luck by 1.
You can permanently spend luck during play for one of the following:
* Improve Hit Dice: When you roll hit points if all of the dice are 1, choose to spend 1 luck to increase HD by 1 and reroll.
* Improve Cast Dice: When you roll cast points if all of the dice are 1, choose to spend 1 luck to increase CD by 1 and reroll.
* Improve an Item: When you mark the last Use of an item, choose to spend 1 luck to give the item 1 more Use and a new Title (always succeeds).
* Claim Title: When something impressive happens, choose to spend 1 luck to gain a new Title (always succeeds).


When you get a new Tier Title, you can improve one of your character's statistics automatically:
* +1d to melee attacks (or ranged attacks, or damage from spells, etc etc)
* +1d to casting evocations (or illusions, or benisons, etc etc)
* Improve a stat: +1 to one of your character's statistics.
* Slot: Get 1 more inventory slot.

## Backgrounds
Consult your highest stat (roll or choose if a tie) & Luck to determine a background:

## Starting Items

Choose 2 columns below and roll 1d per point of Luck (can crit!) vs DC 4:

| Hits | Armor | Spells |
|---|---|---|
| 0 | None | None |
| 1 | Leather | 1 Spell |
| 2 | Scale | 2 Spells |
| 3 | Chain | 3 Spells |
| 4+ | Half plate | 4 Spells |

### Weapons and Armor

| Class | Slots | Damage | Examples | Notes |
|---|---|---|---|---|
| V. Light Melee | 1 | 0d | Dagger, club, whip | |
| Light Melee | 1 | 1d | Shortsword, hatchet, mace | |
| Crude Melee | 2 | 1d | Staff | |
| Heavy Melee | 2 | 2d | Longsword, battleax, flail, spear | |
| V. Heavy Melee | 3 | 3d | Halberd, greatsword, maul, lance | |
| Small Shield | 1 | - | Buckler, targe, round wooden | Improve armor by 1. |
| Large Shield | 2 | - | Kite, tower, large steel | Improve armor by 2. |
| Ammunition (3) | 1 | - | Stones, arrows, bolts, etc. |
| V. Light Ranged | 0 | 0d | Sling, hand crossbow | Requires Ammunition |
| V. Light Thrown (3) | 0 | 0d | Darts | Requires Ammunition |
| Light Ranged | 1 | 1d | Shortbow, light crossbow | Requires Ammunition |
| Heavy Ranged | 2 | 2d | Longbow, heavy crossbow | Requires Ammunition |

| Class | Slots | Notes |
|---|---|---|
| None | 0 | Naked! Or clothes, robes, etc |
| Hide | 1 | Leather armor, hide armor, winter clothing, heavy robes, or gladiator's armor |
| Scale | 2 | Lamelar, chain shirt, or reinforced leather |
| Chain | 3 | Maille or breastplate |
| Half plate | 4 | Banded, splint, or plates-and-mail |
| Full plate | 5 | Full gothic platemail |

Roll 4 times on A, B, or C (your choice).
* If you don't have any light sources, you can trade any item for "torches (3)".
* If you don't have any food, you can trade any item for "rations (3)".

## Other 

# Inventory

Inventory is measured in slots.
Anything "major" -- a weapon, a bundle of torches -- goes into a slot.
Items like armor take multiple slots.
Every 100 coins takes 1 slot.

You have 5 slots, +1 per point of health, +1 if your class gave you any.

After that, each 3 items you carry give you 1p to all physical rolls.

## Items
Many items have 1, or 3, or sometimes even 6 "uses".
You don't necessarily mark one each time you use the item, but when the rules tell you to mark a use.
When the item's used up all 3 uses, it's consumed, or broken, or even destroyed.
During downtime, you can roll to replenish items at some cost.

Rations: Purchased in 1 week's worth at a time.
Candles: Bundles of 6 which each burn dimly for about 1 hour.
Torches: Bundles of 3 which each burn for about 1 hour.
Lantern: Oil burns brightly for about 6 hours per pint.
Weapons, shields, armor, ammunition: Mark use for +1b.

Item saves: A weapon or armor with all uses marked is either irreperably destroyed or merely broken.
Roll a 1d save (sometimes more?) to figure out which:

| Material | DC | Examples |
|----------|----|----------|
| Soft leather, cloth, rope, wicker | 2 | Clothing, bags |
| Hard Leather, wood, bone | 3 | Armor, club, spear |
| ceramic, stone, silver | 4 | Orb, pot, chain |
| bronze | 5 | Dagger, breastplate |
| steel | 6 | Sword |

## Other goods

| Animals | sp cost |
|---|---|
| Mule | 20 |
| Draft horse | 30 |
| Light horse | 40 |
| Medium warhorse | 100 |
| Heavy warhorse | 200 |

| Light Sources | uses | sp cost |
|---|---|---|
| torches | 3 | 1 |
| lantern | 6 | 10 |
| flask oil | 1 | 2 |

| Other | sp cost |
|---|---|
| 3 Stakes & mallet | 3 |
| steel mirror | 5 |
| silver mirror | 15 |
| wooden cross | 2 |
| silver cross | 25 |
| holy water | 25 |
| wolfsbane/belladona | 25 |
| garlic | 5 |
| quart wine | 1 |
| iron rations (1 week) | 15 |
| rations (1 week) | 5 |



## Conditions

When you take Hits, for each hit you can either:
* Mark off a Hit Defense
* Conditions:
  * Over a piece of equipment, which Mars it (still useable)
  * Over an empty slot, which gives you a Mood (like Angry, Sad, Sleepy, etc)
  * Over a slot that already has a Condition, which Breaks equipment and injures you.
Conditions are like antiTitles, giving you +1p per relevant condition when you do something.
You can't use Broken equipment (or indeed, limbs).

If you took any conditions, Health save against +1d per condition you took +1p per condition you already had:
* 0: Free parking
* 1: Stunned 1 round
* 2: Knocked out rest of combat
* 3: Dying (mood was an injury)
* 4: Dead (mood was an injury)
* 5: Flagrantly Dead (mood was an injury)

