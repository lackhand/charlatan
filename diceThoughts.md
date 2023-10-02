# dice & danger

A simple hack of old school dungeon crawling games in the vein of Into the Odd (and many other hacks).
Great gratitude to Ben Milton's CC BY 4.0 Maze Rats.

> This is a d6-based DIY elfgame about adventurers and their explorations into funhouse dungeons.
> One of you is the DM (Narrator, Referee, Judge), and the other Players have Player Characters (the DM also has Non-Player Characters).
> Much more ink has been spilled about How To Play an RPG; go there for more.

Have fun!

# Players roll d6s to determine damage given (or received)

The _damage source_ adds (or unusually removes) the number of six-sided **d**ice of **d**amage to the pool, like +1d or +4d.
> For instance, shortswords are 1d, longswords are 2d, and polearms 3d; level one fighters add +1d, and level eleven add +4d.

The _situation_ might give _advantage_ or _disadvantage_ to a roll, changing the **d**is**c**ard number.
**If it doesn't say otherwise, then the DC is 4**.
An easier check might have DC 3 or even 2; a harder check might have DC 5 or even 6.
Don't roll if the DC is not a number from 2-6; figure out what makes sense instead.
The DM is the ultimate arbiter of the total DC.

The _damage recipient_ removes (or unusually adds) a number of damage dice (**b**locking them), written as "2b" or "3b".
1d and 1b cancel each other out, 1 for 1, before the roll.
It's ok if this reduces the size of the dice pool below 0d.
> For instance, a small shield blocks 1b and a large shield gives 2b.

Dice showing values above the DC are **hits**. Announce the number of dice that hit as a **hit number**.
> Alice rolls 3d and gets `[1, 3, 5]` vs DC3.
> She **hits** with the `[3, 5]` and announces the count of dice that hit --  a **hit 2**.

Dice that show a 6 are **crits** and explode (it hits, and you roll an additional die which could also crit).
Some rolls don't allow crits, and will say so. Then it's just a normal hit.
> Bob rolls 7d and gets `[1, 2, 3, 4, 6, 6, 6]` vs DC3.
> He hit with the `[3, 4]` and crit with the `[6, 6, 6]` -- a _hit 2 crit 3_ (so far!).
> He rerolls 3d and gets `[2, 4, 6]` -- a _hit 3 crit 4_ so far.
> He rerolls the new 1d that hasn't exploded yet and gets `[4]` -- a total of **hit 8**.

## Weird pool sizes

When the pool is smaller than 1 die, roll 2 (or 3, 4, etc) dice and keep only the lowest (so 0d is the worst of 2 dice, -1d worst of 3, etc).
When the pool is larger than 8 dice (lucky you), assume sets of 6 roll `[1, 2, 3, 4, 5, 6]`.

## Players roll all of the dice

* When a player rolls to deal damage, it's a "damage" or "dmg" roll.
  > Bob tries to stab Alizard Mann, so he rolls a pool of dice for damage he could deal.
* When a player rolls to avoid taking damage from someone else, it's a "saving throw" or "save" roll.
  > Boblin tries to stab Alice, so she rolls a pool of dice for damage she couldn't dodge.
* Sometimes the player rolls a saving throw but the stakes are more metaphorical; that's a "skill check" or "skill" roll.
  > Alice tries to avoid detection by a guard, rolling a saving throw. On a failure, she can take damage or raise the alarm.
* Sometimes, the player rolls metaphorical damage to make progress on a "project check" or "project" roll.
  > Bob tries to pick a lock, trying to rack up a number of successes during this opportune moment.
* Sometimes anyone (including the DM) just rolls dice to randomize what happens next like on a table.
  That's different.

## Sometimes the "damage" is metaphorical

> Alice searches the room.
> She rolls 1d against DC 6, hoping for a hit; either way, some time passes.
> And if she were a Dwarf (or an Architect) or otherwise secret-door-wise, she might have advantage and thus DC 5.
> It's perfectly acceptable for everyone to roll in cases like these.
> And the same example might work searching your own mind-palace to recall a fact.

> Bob climbs the cliff in the dark and rain, with plentiful handholds.
> It all cancels out to 1d against DC 4; on a miss, he's facing the 10d fall.

> Carol faces The Locked Door.
> She could attempt to batter or hack it down (melee damage) -- probably 2d or 3d or so, against the door's obstinate HD.
> She could attempt to pick it (skill check) -- 2d for the picks, against the lock's lower-but-harder-to-attack HD (or 0d without picks, or maybe a one-time 3d for a vial of metal-eating acid).
> She could attack the hinges with a tool, another version of 2d (with penalty dice against battery!).

# Character Statistics

As with any game, characters (and obstacles, scenery, items, and other phenomena) have statistics to help the rules mediate their interactions.
It's the DM's job to resolve "what happens next" and should only call for the dice if the answer seems fun to randomize.

## Tier & Level

> Can my wizard knock out a dragon in one punch? Why (or why not)?

| Level | Tier | Tier Title | Notes & Examples |
|---|---|---|---|
| 0 | 0 | Common | Ordinary: a random villager, a wooden club; a goblin |
| 1 | 1 | Novice | **Your new adventurer**; a precocious student; a simple weapon like a spear or dagger; an orc |
| 2-3 | 2 | Apprentice | You after a few adventures, a guard; a martial weapon like a sword or axe; a gnoll |
| 4-6 | 3 | Journeyman | A veteran soldier, a finely made sword or axe; an ogre |
| 7-10 | 4 | Master | A knight or wizard; a magic sword; a hill giant |
| 11-15 | 5 | Grandmaster | A famous knight or archmage; a flaming magic sword; an efreet |
| 16-21 | 6 | Legendary | A world-famous knight or archmage; an intelligent magic sword; a mighty dragon |
| 22+ | 7+ | Demigod (or better) | A force of nature; awe-inspiring and unharnessable; an ancient dragon |
| -1 (etc) | -1 (etc) | Poor (or worse) | A giant rat, a broken wretch; a broom handle, a sharpened stone; a kobold |

This game uses a power **tier** to suggest the power, scale, and impact of something within the game.
Each tier represents an order-of-magnitude increase.

Within each tier, player characters have **level** to measure slightly more fine-grained progress.
Nothing else in the world has (or needs) a level; it's just so that we can give your character regularly scheduled growth.

> Note: As a starting character of Level 1, you have one **T**ier **P**oint and one **L**evel **P**oint to spend; read on!

## The Attributes

Attributes in this game add dice to your skills, remove dice from saves (reducing their damage), and certain specific attributes add dice to your attacks.
A starting character has scores from 0-3, with "average competency" being 1 and "peak naturally possible" being 7.

| Innate Attribute | Save Vs | Skills |
|---|---|---|
| **STRength** | Melee, paralysis, obstacles, entanglement | Climb, swim, jump, lift, force, throw |
| **REFLex** | Missiles, blasts, surprise, detection, inaction | Sneak, intuit, trail, balance |
| **CONstitution** | Poison, deprivation, transformation, injury, death | Carry |
| **INTellect** | Confusion, distraction, error | Tinker, prepare, know how, remember, operate |
| **WILL** | Suasion, morale, disloyalty, reactions | Sway, inspire, channel |

Roll 3d vs DC 4 (no crits) for each innate attribute in order, then switch 2 (if you want).

> Rolling an attribute: When you're told to "roll strength" (for a skill check), add to the pool 1d per point of strength.
> When you're told to "reflex save", add 1b per point of reflex (removing them from the pool).
> And so on.
> By default, you're counting hits of damage; by default, that's against DC 4.

Your character can have other non-innate attributes which you don't roll, but instead derive in some other way, for instance Armor (based on what you wear), Melee, Ranged Attack, Saving Throws, Casting, Skill, (each of which come from tier benefits), etc.
All of them start at 0d.
Don't add innate attributes to damage.

See the Combat chapter for some examples of when you might use certain saves, checks, etc.

## The Defense Pools

This game uses 3 pools of resources to absorb (or to add!) hits.
The player can spend these after the roll is fully evaluated 1:1 to set a die in the pool to any face (but no critical hits).

| Innate Pool | Use when... | Restored when... |
|---|---|---|
| **H**it **D**efense | Physical consequences like stress, injury, illness, or fatigue | A good night's sleep |
| **M**ana **D**efense | Mental, spiritual, social, or situational consequences like embarrassment, debt, bad karma, perception or understanding  | A good night's sleep |
| **K**arma **D**defense | Any roll | Your character is true to their Titles and entertains the DM; when you gain a level |

HD and MD come back through rest; roll 1d per maximum defense and restore any that hit up to the maximum (DC 3 in an inn, DC 5 while camping, DC 2 at a hospital, etc).
KD are awarded by the DM (for acting in alignment with your character, quest, flaws, etc; or for being entertaining).

Your initial HD and MD pools are 0 (though as a level 1 character, you are entitled to improve one of them through play!).
Your KD pool begins at 0 plus each of:
* +1 per innate attribute at 0
* +1/2 per innate attribute at 1
* +1/3 per innate attribute at 2
* Then round down

> Effects on miss: When you spend defense to erase a hit, you lessen but do not fully erase the hit: you twist out of the way at the last second, etc.
> If the attack had an on-hit rider (like "on hit: be set on fire 1d"), you're still set on fire, even if you reduce the hits to 0.

## Titles

Select a **Background Title** based on your **highest attribute** (if several are tied, you can choose one) and your **KD**:

| ... | 0 | 1 | 2 | 3 | 4+ |
|---|---|---|---|---|---|
| Strength (Warrior) | Barbarian/Gladiator | Squire | Guard | Soldier | Knight |
| Reflex (Hunter) | Ratcatcher | Woodcutter | Thief | Scout/Outlaw | Ranger/Spy |
| Health (Laborer) | Scullion/Farmhand | Shepherd/Groom | Cook/Barber | Sailor | Merchant |
| Intelligence (Expert) | Tinker/Tailor | Artisan/Scribe | Architect/Engineer | Herbalist/Poisoner | Alchemist/Doctor |
| Will (Adept) | Hermit/Monk | Seer | Nursemaid/Nun | Sorcerer/Witch | Official/Priest |
| Luck (Noble) | Beggar | Dancer | Bard | Traveler | Prince/ss |

Your DM might tell you to pick other titles within categories that they think would be interesting for this campaign:
* **Bonds** describe relationships between your character and places or things.
* **Ideals** describe drives, alignments, creeds, attitudes, etc.
* **Traits** (including **Flaws**) describe things like species or race or culture, but also appearance, mannerisms, etc.

You can pick some, generate some as they come up, add additional kind of titles the campaign needs, etc.

| d6 | 1 | 2 | 3 | 4 | 5 | 6 |
|---|---|---|---|---|---|---|
| Bond with... | The Crown | The Church | The Land | The Guild | The player to your left | ... to your right |
| Bond nature... | Debt | Oath | Kin | Interests | Opportunity | History |
| Alignment | Chaos | Chaos | Chaos/Neutrality | Neutrality | Neutrality/Order | Order |
| Chaos Drives | Mercenary | Revenge | Freedom | Joy | Belonging | Strength |
| Neutral Drives | Peace | Justice | Abundance | Excellence | Understanding | Knowledge |
| Order Drives | Altruism | Mercy | Duty | Fairness | Conformity | Unity |
| Size Traits | Slight | Stout | Wiry | Soft | Big | Gangly |
| Origin Traits | City | Castle | Town | Wilds | Nomadic | Afar |
| Environmental Traits | Mountains | Hills | Forests | Farmland | Swamp | Caves |
| Old injury | Facial scar | Finger(s) | Chunk | Limp | Tremor | Teeth |

When a title is especially relevant, the DM might give _advantage_ or _disadvantage_, adjusting the DC (especially for skill or project rolls).
Don't worry, you'll acquire more titles as the game goes on.

> Dave is running a fantasy campaign set against the backdrop of the American Revolution vaguely aligned with the rebels, but with like faeries and dragons and undead too.
> He proposes that all of the characters are human, just to keep things grounded; they all speak English, the language of their own nation, and one other language.
> He proposes that characters need a **Nation** for things like appearance, native language, etc (along with a suggested **ideal**, though they can pick their own as well) (1: Protestant New English (freedom)/Catholic New English (wealth) 2: White Virginian (wealth)/Black Virginian (freedom) 3: Olde English (hatred of the english) 4: Dutch/French (hatred of the english) 5: Algonquin (Mohegan, Wampanoag, etc; hatred of the english), 6: Iroquois (Mohawk, Cherokee, etc; hatred of the english))
> Within those **Nations**, they also need a **Bond** to the Rebellion; perhaps d6 1: Mercenary 2: Outlaw 3: Agent of another Nation 4: Personal Vendetta 5: Anarchy or other philosophy 6: Defense of someone specific.
> Finally, they need to pick a second specific **Bond** to the Culper Ring, their handler Robert Townsend, or to one other.
> It's game on!

> **BUT I WANT TO BREATHE FIRE**
> Sometimes being a supernatural creature is just a trait -- a "goblin scullion" or "dwarven tinker" are perfectly reasonable character types; don't overthink it.
> But other times you want to portray a (baby) dragon, a (fallen) angel, adventuring dryad, friendly ghost, or other monstrous or inhuman creature.
> That's fine too; remember to choose appropriate gear to reflect the supernatural powers you might have, and that you might need to grow into your power.

## Level Up

Characters get stronger over time, which lets them improve their attributes (both innate, and other).

All attribute improvement works the same way: roll 1d vs a DC of the attribute's current value.
If the attribute is already 7 or higher, use a DC of 6 but require 1 additional hit per point above 6 (which itself requires a crit).
On a hit, improve the attribute by 1 point (before resolving whatever situation called for the improvement!).
If the roll fails, the opportunity for advancement is lost (though it should be retriable during the next session of play!).

### Level Up
Gain a new level when you spend 1000 sp per current level & 1 week per current level training with a tutor.
The DM can waive any percentage of this fee or time for any reason (story awards, tutor with cheaper rates, demonic pacts, etc).

A character can spend their Level Up on one of:
* HD: As attribute improvement (while spending or recovering)
* MD: As attribute improvement (while spending or recovering)
* KD: As attribute improvement (while spending or recovering)
* Claim a Feat Title: No roll; commemorate a deed or revealed facet (in the moment or in retrospect).
  * "Seven in One Blow", "Marshwalker", "Darksighted", "Deadshot", "Hero of the Lanternos", "Elf-friend", "Botanic Expert", "Master of the Flame Rune", etc etc.
  * You can choose to overcome an Injury (see combat) by making it into a Title; like replacing "Missing Hand" with your new title, "Hook handed"; "Missing Eye" into "One Eyed", etc.
  * As with any title, you'll want this to either be a good source of karma, contextually likely to give advantage, or both.
* Progress on a Project (a sudden breakthrough or insight, revelation of time spent in background)

### Tier Improvements
A level 1 character is entitled to an improvement after each Triangular Number; at each of levels 1, 2, 4, 7, 11, 16, 22, 29, etc.

| Tier Improvement | Situation |
|---|---|
| one **innate stat** | Rolling a skill or save with that stat (athletics for Str, tinkering for Int, etc) |
| **evasion** | Avoiding melee, missile, blast attacks |
| **melee** | Attacking or defending in melee, including unarmed |
| **missiles** | Damage from an aimed non-melee attack (such as a bow, dart, magic wand, thrown oil, etc) |
| **blasts** | Creating a damaging effect or area (such as casting or triggering a _fireball_ spell, setting a bomb or flaming oil, splashing holy water, caltrops, etc) |
| **casts** | Resist the channeling complexity of a spell |
| **skills** | Avoid detection and surprise, make progress on projects, careful or skillful errors, etc |
| **saves** | Resist poisons, non-evasion spells, pit traps, etc |

# Inventory
You may carry Ready (equipped, on your body or in your hands) 6 + CON items in slots.
You might insist that there's a hand limit or something, so that 3 daggers is 1 dagger too many and you can't wear two kinds of armor; use your best judgment.
It is free to lay hands on any readied item.

## Encumbrance & Carrying More
You can purchase additional stacks of stowed items by Readying "Encumbered: disadvantage to speedy or athletic tasks (like movement, dodging, etc)".
This purchases +5 + CON unreadied slots each time; certain armor requires Enumbered slots to ready.

Every 10ish pounds of other gear weighs one slot.
Coins (or gems, etc) stack 500 to the slot. Don't bother tracking the first 50 or so.

Particularly light gear like a bandolier of daggers, darts or a packet of torches or candles stack 6 items to the container (in one slot).
Mark that with the name of the item and a number of "x-es" after it as the items are consumed or lost.
This also works for a potion belt, a tome of spells, etc: 1 slot, multiple combined light items (whose use is tracked individually).
But don't combine multiple stacks of un-like items; one torch consumes as much weight as six torches, and you can't combine partial stacks of daggers and torches.

Particularly large objects might consume multiple slots (like two handed weapons or armor).
An unconscious friend stripped of armor & gear, a chest, or a statue weighs 10 slots.

Determine which item is drawn from being stowed randomly if time is of the essence (for instance, each action to draw an item from a sack gets a random item from that sack).

## Uses & Durability

Consumable items that are used are used up.
Sometimes the thing that's used up is abstract, like the pint of oil in a lantern being turned into 6 hours of light.

| Item | Instances/Uses/Durability | Used per... |
|---|---|---|
| Ammunition (~25 arrows, bolts, stones) | 6 | Combat (can glean 1d per spent ammunition afterwards) |
| Rations | 1 | 1/week (soft rations start checking spoilage after 1 week) |
| Torches/Candles | 6 | 1 hr |
| Lamp/Lantern | 6 | 1 hr |

Other times we're tracking the remaining durability to a more permanent item, like damage to armor or weapons or shields.

| Item | Durability | 
|---|---|
| Crystal/Glass/Ice; Paper/Cord/Cloth | 1 |
| Wood/Bone/Hard Leather | 2 |
| Silver/Soft Metal | 3 |
| Stone | 4 |
| Bronze | 5 |
| Steel | 6 |
| Mithral | 6 |
| Adamant | 7 |

Items take damage when something specifically tries to injure them, including their bearer suffering an injury.
When someone takes an injury, damage their armor (or: test damage for all ready items).
When someone deals an injury to someone whose armor has more durability remaining than the weapon, remove one use from the weapon.

# The Things you Carry

Anything your character starts with, you know how to use.
Anything your background suggests you know how to use, you know how to use.

There are alternative suggestions for starting equipment in the section on Magic.
Otherwise choose each of Armor, Weapons, and Gear as directed below:

Armor: Roll 1d per KD then select armors of that or lesser quality.
| Quality | Armor | Slots | Notes |
|---|---|---|---|
| 0 | None | 0 | -1b Armor |
| 0 | Light (Buff coat, Hides, Linothorax) | 2 | 0b Armor |
| 1 | Helmet | +1 encumbrance | +1b Armor (from base none/light) |
| 2 | Medium (Brigandine, Chain Shirt, Breastplate) | 1 + 1 encumbrance | 1b Armor |
| 3 | Heavy (Maille, Plates) | 1 + 2 encumbrance | 2b Armor |
| 4 | V. Heavy (Half Plate) | 2 + 2 encumbrance | 3b Armor |
| 5 | V. V. Heavy (Gothic Plate) | 3 + 2 encumbrance | 4b Armor |

Roll or choose up to KD times below:
| d66 Gear | 1 | 2 | 3 | 4 | 5 | 6 | Or Else |
|---|---|---|---|---|---|---|---|
| 1 (Tools) | Chisel/Drill | Hacksaw | Hammer | Shovel | Rasp/File | Crowbar | Pot |
| 2 (Camp Gear) | Warm Cloak | Oilcloth | Bear Trap | Pemmican (1) | Tinderbox | Fishing Net | Sack Oats (1) |
| 3 (Cave Gear) | Pole, 10' | Chain, 10' | Pitons | Rope, 50' | Lantern+Oil (6) | Glowstone | Torches (3/6) |
| 4 (Thief Kit) | Caltrops | Glass Marbles | Lockpicks | Steel Wire | Grapple | Pouch of 50+10/KD silver | Large Sack |
| 5 (Finery) | Musk | Pot Grease | Strong wine | Ink+Pen | Glue | Mirror, steel | Cards/Dice |
| 6 (Specialty) | Belladonna/Garlic Flowers | Purgative | Venom | Acid | Mercury | Sulfur | Box Salt | 

Afterwards you may choose to take the "or else" from any line in which you didn't get a result already (including if you don't have enough KD choices).

You have your KD in silver coins.

Weapons: Roll 1d per KD for Quality Table, then take as many entries as you like from any table with quality less than or equal to the one you rolled.
> Bare handed attacks or thrown stones deal -1d damage.

**0 Quality: Crude Weapons**
| Slots | Damage | Example |
|---|---|---|
| 1 | 0d | Club, tool hammer, sickle |
| 2 | 1d | Staff, pitchfork, scythe |
| 1 | - | Stones(6) |
| 0 | 0d | Sling (needs stones) |

**1 Quality: Simple Weapons**
| Slots | Damage | Example |
|---|---|---|
| 1 | 0d | Dagger (3), Dart (6), whip |
| 1 | 1d | Hatchet, mace, spear |
| 2 | 2d | Pike |
| 2 | 1b | Wooden shield |
| 1 | - | Arrows or Bolts(6) |
| 1 | 1d | Light Crossbow (+Bolts) |
| 2 | 1d | Hunting Bow (+Arrows) |

**2 Quality: Martial Weapons**
| Slots | Damage | Example |
|---|---|---|
| 1 | 1d | Javelin (3) |
| 1 | 1d | Sword, flail |
| 2 | 2d | Battleax, broadsword, warhammer |
| 1 | 1b | Buckler |
| 3 | 2b | Tower Shield |
| 2 | 2d | Heavy crossbow, war bow (+Arrows/Bolts) |

**3 Quality: Fine Weapons**
| 3 | 3d | Polearm, glaive, halberd, lance |
| 1 | - | Cartridges (6) - per shot |
| 1 | - | Blackpowder (6) |
| 1 | 2d | Pistol (+Powder) |
| 2 | 3d | Blunderbuss (+Powder) |

Go adventure!

# Combat

* Melee: roll melee dice + weapon dice vs opponent melee dice + armor dice + shield dice, count hits
* Missile: roll ranged dice + weapon dice vs opponent dodge dice + armor dice + shield dice, count hits
* Combat Feat: The attacker proposes a combat trick. Before rolling, the defender chooses that the attacker succeed, or to take the damage the attack would otherwise do. DM should announce DC for maneuver plausibility.
* Blasts: roll effect's blast dice vs opponent dodge dice + reflex in dice + armor dice + shield dice, count hits
* Petrification Gazes: roll gaze dice vs opponent magic defense + STR dice. On 0hp, petrified.
* Difficult terrain: roll 1d vs opponent STR dice. On hits, -25% speed.
* Pits: roll surprise (1d? 3d?) vs opponent REFL dice. On hit, falling!
* Falls: Roll 1d per 10' unopposed. Ouch.
* On Fire: roll 1d each turn (vs Refl if stop/drop/roll, advantage with aid). On each crit, increase fire by 1; on all miss, fire out.
* Poisoned: roll 1d each turn vs Con; poison deals hits in dice next turn; ends after 2 turns at 0d.
* Lava: Dead no save.

> TODO: Merge the above!

| Danger | Attack (dice) | Defense (block) |
|---|---|---|
| Melee weapon | Weapon dice + Melee dice | (Armor dice or Strength) + Melee dice + Shield dice |
| Missile weapon | Weapon dice + Ranged Attack dice | (Armor dice or Reflex) + Ranged Defense dice + Shield dice |
| Bombs, fireballs, dragonbreath, etc | per-Effect dice + (Magic Attack dice or etc) | (Armor dice or Reflex) + Saving Throw dice + Shield dice |
| Swimming, climbing, move through thicket, etc | (obstacle dice: 1d, 3d, etc) | Strength dice + Saving Throw dice, each hit costs movement (or maybe is damage, etc) |
| Spell channeling | (Spell Complexity dice) | Will + Magic Cast dice |
| Reaction | DM gauge of hostility, 2d by default | Highest Will + Skill; 0 hits: friendly, 1 hit: guarded, 2+ hits: hostile |
| Initiative | Reflex dice + Skill dice; hits determine initiative order (highest first, then randomly by side) | - |
| _Suprise_ | _Note: If either side was plausibly surprised, they can't act during combat round 1 initiative order 0_ | - |
| Morale | Start of round at 0d +1d each round | Will + Saving Throw dice; only MD damage possible |
| Spark/Torch/Flaming oil | 0d/1d/2d + (Magic Attack dice or etc) | Refl + Saving Throw dice; on hit catch fire at number of hits, each round attacked by fire again at number of hits on previous round, going out after 0d misses |
| Poison | 1d (or more) | Con + Saving Throw dice; on any hit increase poison by 1, on all miss decrease poison by 1, cure after 0d misses |
| Exposure | -2d (+1d per: air minutes, shelter hours, water days, food weeks) | Con + Saving Throw dice |

Describe a hit with relish, then cancel it with HD (or KD, or sometimes MD).

## Injury
When you face physically damaging hits:
* First, cancel them out with HD 1:1. If you cancel them all, no further consequences.
* Second, cancel them out with damage to your gear 1:1 (some hits require you to do _both_, like blasts).
  * Items with no uses left are destroyed
  * If you did have any hits you didn't cancel with HD, you still have to roll on the Consequences Table, though perhaps at 0d
* Thirdly, take injuries whose total points equal the number of hits remaining
  * Like, if you have 3 hits to absorb from a giant's club, you could Mangled Leg (3) or Broken Rib (2)+Dazed (1) or Wobbly Leg (1) + Wobbly Leg (1) + Wobbly Arm (1)
  * If you can't take another Injury, you die; Injuries remain until Healed
  * Roll on the consequences table +1d per point of injury

In any case, roll 1d per (time you've rolled on this table since resting) - (Con + Saving Throw dice):
| Consequence Hits | Consequence |
|---|---|
| 0 | Stunned, repeat the check each round and recover if all miss |
| 1 | KO; as stunned but can only recheck with medical help |
| 2 | Dying. Take 1 hit of damage each round. |
| 3+ | Fatal. Higher scores, more flagrantly fatal. |

Injury Recovery: Saving throw against the Injury's dice. If any hit, you don't recover; if they do, it shrinks by 1, disappearing at -1.
You're entitled to a saving throw once per day of care for Injury(1), week for Injury(2), month for Injury(3), season+ for Injury(4).
You can short circuit this by overcoming the injury by taking it as a new Title during level up.

This can also represent mutations or other bodily changes like "Becoming Petrified", "Transformed into a worm", "Fatigued (1)", or "Mutated arm into tentacle".
That last one might be part injury, part power: the tentacle might still be useable as a limb, with greater reach, strength, and grippiness.

## Afflictions
Mental, magical, legal and social effects work along similar logic to Injuries, but with a few differences:
* They inflict Titles (usually not slots of inventory)
* They are resisted with Will (instead of Con)
* They can be lifted via Atonement or Therapy (or similar), a story quest.
  * The recipient might remove the affliction, transform it, or embrace it; their choice.

> Alice the Archer is on trial for the murder of a corrupt royal guard (along with Bob the bard and Carol the cook).
> Alice is her team's lawyer; Devious Davel is the NPC on the other side.
> Davel makes the court's arguments; it's an automatic 4 hits because he's an NPC and that's the strength of the case.
> Alice makes her arguments, Will (for charm) + Skill, and gets 2 hits.
> Each member of the party is facing the difference at Sentencing, with Davel arguing for exile.
>  
> Alice is facing 2 hits.
> She has no MD or KD to spend, and so she takes the hit: she's a Branded Exile, and outlaw and a pariah.
> (she's already planning ahead; when she next level ups, she'll become a Beloved Outlaw, transforming this Affliction into a Trait with a more positive spin)
>
> Bob is facing 2 hits.
> He has lots of MD and KD. He spends both, absorbing the hit and beating the rap (this time).
> He still has to take some kind of title, but it can be pretty gentle; he negotiates into "Person of Interest".
>
> Carol is facing 2 hits.
> She has only a little MD and KD. She spends 1 point.
> She's an Exile (Davel's goal).
> She doesn't see that being too bad of a problem.

If in doubt, determine afflictions randomly:
| d6 | Mental Affliction | Spiritual Affliction |
|---|---|---|---|
| 1 | Unreason (or Delusion, Paranoia, etc) | Unlucky & Ill-Omened |
| 2 | Treachery (or New Personality, Alignment, Emnities, etc) | Haunted (attracts ghosts, demons, witches, etc) |
| 3 | Despair (or Mania, etc) | Isolated, people & animals avoid |
| 4 | Compulsion (or Obsession, etc) | Presence of something nauseates (garlic, sunlight, laughter, etc) |
| 5 | Incapacity (or Amnesia, tremors, catatonia, etc) | Targeted by someone specific: demon lord, king, etc |
| 6 | Phobia (As above, but triggered by exposure...) | Plagued by something specific: flies, fires, debt, thieves, etc | 

# Magic

Magical effects are divided into schools.

Some effects are channeled through **spells**.
Spells are written on **scrolls**, which are stored in **tomes** (2 item slots, 6 spells).
A spell can be cast as quickly as an action using the tome which contains it.
Each spell has a **complexity**, a number of dice which must be saved against by the caster.
Spells of greater effect will have greater complexity.
The default DC for a spell is DC 3; character backgrounds might reduce the damage from the spell.
On a failure, its **fallout** occurs (environment: damage to the environment like a fire starts; mutation as injury but related to the power source; magical cuts the wizard off from their source of magic for a time). Uses of magical reagents or the spell itself (1 durability) can swallow these conflicts.
Then, assuming the spell didn't self-interrupt, its effects take place.

Other effects take place through a **focus**.
Foci are usually 1 handed objects with 3 uses (or 2 handed objects with 6 uses) that hold a single effect.
Mark off uses equal to the spell's complexity and it takes place (no casting roll necessary).

Finally, **tricks** are consumable items like potions, dusts, drugs, bombs, reagents, candles, etc.
They have magical/chemical effects that are released as part of using them, such as inhaling a dust, applying an oil, etc.

During character creation, you may choose any or all of:
* Instead of rolling for Armor, roll KD for a number of initial spells, each of which is randomly generated (complexity -- thus power -- the lower of 2d; same dice, complexity 0).
* Instead of rolling for Gear, you may make all of your KD rolls on the Trick table below (you can still choose to take the "fallback" options from the normal Gear table)
* Instead of rolling for Weapons, you may roll KD for the (single) Quality of Focus you have; your choice whether it's a 1 slot/3 use focus or a 2 slot/6 use focus.
  * You may also select Quality 0 weapons like clubs or staves as normal if you wish.

**Magical effects** such as for spells and foci:
| d6 | 1 | 2 | 3 | 4 | 5 | 6 |
|---|---|---|---|---|---|---|
| **School** | Evocation | Intercession | Conjuration | Phantasm | Viridity | Artifice |
| **Fallout** | Environmental | Injury | Mental | Spiritual | Mutation | Magical |
| **Game Mechanic** | Item/Uses | Bond | Trait | Attacks | Saves | Skills |
| **Terrain** | Wood & Field | Frozen Mountain | Coast & Swamp | Desert | Sea | Storm & Sky |
| **Entity** | Shadow | Alien | Fey | Elemental | Arcane | Demon |
| **Phantasm** | Dreaming | Bonds & Feelings | Obscurement | (Un)Reason | Seeming | Transformation |
| **Emotion** | Joy | Fear | Calm | Despair | Anger | Disgust |
| **Element** | Mist | Wind | Fire | Lightning | Ice | Stone |
| **Darkness** | Bone | Blood | Rot | Smoke | Locust | Fatigue |
| **Shape** | Cloud | Beam | Ball | Wall | Wave/Cone | Zone |
| **Intercession** | Curse | Reveal | Empower | Protect | Rebuke | Heal |
| **Focus** | Wand | Icon | Cup/Bell | Mask/Shroud | Stone | Flower |
| **Weapon** | Sword | Axe | Spear | Hammer | Dart | Whip |
| **Metal** | Iron | Gold | Silver | Mercury | Copper | Lead/Tin |

Other times it makes more sense to look at the kinds of effects that make sense at given complexities:
* **Complexity 0**: Spells that duplicate the effects of tools or equipment: a spell to dig a pit by moving the sand; a spell that lets you cast light as a torch; a spell that feeds or waters a group.
* **Complexity 1**: Spells that reveal, translate, obscure (fog cloud, detect evil, comprehend languages, hex)
* **Complexity 2**: Spells that heal, inspire, bypass, entangle, augur, manipulate (cure wounds, bless, augury, invisibility, levitation, phantasmal force, web)
* **Complexity 3**: Spells that attack, defend, observe, subvert, command, adapt (fireball, lightning bolt, clairvoyance, fly, water breathing, suggestion)
* **Complexity 4**: Spells that travel, transform (polymorph, dimension door)
* **Complexity 5**: Spells that undo error, shape nature, slay (heal, flesh to stone/stone to flesh, wall of stone/iron, finger of death)
* **Complexity 6**: Spells that finalize (disintegrate)



### Tricks
* Balm Oil: Ignore Injuries (or Afflictions) for 1h per complexity & -complexity rolls on injury table
* Potion of Healing: Remove an injury of up to (complexity) & -1d rolls on injury table
* Potion of Strength: Increase Str & Con up to (complexity) for 10m (or: Speed for Int & Refl or Spirit for Will)
* Potion of Purgation: Advantage save vs poison per round spent retching
* Oil of Venom: +(complexity)d poison on any hit for one attack
* Fire Bomb: Bursts open dealing (complexity)d in a (complexity)*10' diameter.
* Smoke Bomb: Bursts into a cloud (complexity)*10' radius for (complexity)minutes. Might have a distinctive smell, cling to eyes, etc.
* Petard: Bursts open dealing 2*(complexity)d in a (complexity)*5' diameter
* 


# Monsters

Organizing from [OSE](https://oldschoolessentials.necroticgnome.com/srd/index.php/Monster_Descriptions).


## Tier -1
Bat
Cat
Rat

## Tier 0
Giant rat
Kobold
Killer bee
Sprite
Centipede, Giant
Goblin

## Tier 1
Giant beetle (fire, oil)
Orc
Bugbear
Skeleton
Cobra
Stirge

Acolyte
Bandit/Brigand/Buccaneer

## Tier 2
Berserker
Gnoll
Lizardman
Giant beetle (tiger)
Green Slime
Giant Lizard
Giant Crab
Wolf
Bat, Giant (+Vampire)
Boar
Camel
Cave Locust
Crocodile

## Tier 3
Bugbear
Ape, White
Bear, Black (+Grizzly +Polar)
Blink Dog
Carcass Crawler
Ogre
Lion (, Mountain, Panther, Tiger)
Cockatrice
Large Crcodile

## Tier 4
Basilisk
Bear, Cave
Black Pudding
Caecilia
Sabre-tooth tiger
Centaur
Chimera


## Tier 5
Cyclops

## Tier 6
Giant Crocodile

## Tier 7
