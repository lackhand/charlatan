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

Attributes in this game impact your defenses and your skills, but never an attack.

Player characters have five attributes which measure their capability in broad swathes; humans tend to be in the range 0-4 but could go beyond that range. NPCs use a simpler set of 3.

| Innate Attribute | Save Vs | Skills | NPC Attribute |
|---|---|---|---|
| **STRength** | Melee, paralysis, obstacles, entanglement | Climb, swim, jump, lift, force, throw | Fortitude |
| **REFLex** | Missiles, blasts, surprise, detection, inaction | Sneak, intuit, trail, balance | Instinct |
| **CONstitution** | Poison, deprivation, transformation, injury, death | Carry | Fortitude | 
| **INTellect** | Confusion, distraction, error | Tinker, prepare, know how, remember, operate | Instinct |
| **WILL** | Suasion, morale, disloyalty, reactions | Sway, inspire, channel | Will |

Roll 3d vs DC 4 (no crits) for each innate attribute in order, then switch 2 (if you want).

> Rolling an attribute: When you're told to "roll strength", add to the pool 1d per point of strength.
> When you're told to "reflex save", add 1b per point of reflex.
> And so on.
> By default, you're counting hits of damage; by default, that's against DC 4.

> Monsters have one stat each for Size (use for Str or Con), Speed (use for Refl and some kinds of Int), and Mind (Will & other Int).

Your character can have other non-innate attributes which you don't roll, but instead derive in some other way, for instance Armor (based on what you wear), Melee, Ranged Attack, Saving Throws, Casting, Skill, (each of which come from tier benefits), etc.
All of them start at 0d.
Player characters don't add their innate attributes to their damage.

| Danger | Attack (dice) | Defense (block) |
|---|---|---|
| Melee weapon | Weapon dice + Melee dice | (Armor dice or Strength) + Melee dice + Shield dice |
| Missile weapon | Weapon dice + Ranged Attack dice | (Armor dice or Reflex) + Ranged Defense dice + Shield dice |
| Bombs, fireballs, dragonbreath, etc | per-Effect dice + (Magic Attack dice or etc) | (Armor dice or Reflex) + Saving Throw dice + Shield dice |
| Swimming, climbing, move through thicket, etc | (obstacle dice: 1d, 3d, etc) | Strength dice + Saving Throw dice, each hit costs movement (or maybe is damage, etc) |
| Spell channeling | (Spell Complexity dice) | Will + Magic Cast dice |
| Surprise&Initiative | Single best opposing Reflex dice + Skill dice | Reflex dice + Saving Throw dice; hits determine phase, phase 0, phase 1, etc; side initiative for all phases |
| Morale break | Start of round at 0d +1d each round | Will + Saving Throw dice; only HD damage possible |
| Spark/Torch/Flaming oil | 0d/1d/2d + (Magic Attack dice or etc) | Refl + Saving Throw dice; on hit catch fire at number of hits, each round attacked by fire again at number of hits on previous round, going out after 0d misses |
| Poison | 1d (or more) | Con + Saving Throw dice; on any hit increase poison by 1, on all miss decrease poison by 1, cure after 0d misses |

## The Defenses

This game uses 3 pools of resources to absorb (or add) hits.

The player can spend these after the roll 1:1 to set a die in the pool to any face.

| Innate Pool | Use when... | Restored when... |
|---|---|---|
| **H**it **D**efense | Physically taking damage (such as with a weapon, suffering a fall, hit by a fireball, etc); fueling extra power, speed, or grit | A good night's sleep |
| **M**ana **D**efense | Add, avoid or erase errors of skill, knowledge, perception, understanding or manipulation | A good night's sleep |
| **K**arma **D**defense | Any roll | Your character is true to their Titles and entertains the DM; when you gain a level |

HD and MD come back through rest; roll 1d per point lost restoring each hit (DC 5 while camping, DC 2 at a hospital, etc).
KD are directly awarded by the DM for skillful play that lives up to your character's essential being.

Your initial HD and MD pools are 0.
Your KD pool is 0 modified as follows:
* +1 per innate attribute at 0
* +1/2 per innate attribute at 1
* +1/3 per innate attribute at 2
* Round down

> Effects on miss: When you spend HD or MD to erase a hit, you lessen but do not fully erase the hit: you twist out of the way at the last second, etc.
> If the attack had an on-hit rider (like "on hit: be set on fire 1d"), you're still set on fire, even if you reduce the hits to 0.

## Titles

Select a **Background Title** based on your **highest attribute** (if several are tied, you can choose one) and your **KD**:

| ... | 0 | 1 | 2 | 3 | 4+ |
|---|---|---|---|---|---|
| Strength (Warrior) | Barbarian | Gladiator | Guard/Soldier | Squire | Knight |
| Reflex (Hunter) | Ratcatcher | Thief | Scout/Outlaw | Ranger | Spy | 
| Health (Laborer) | Scullion | Farmer/Shepherd | Cook/Barber | Sailor | Merchant |
| Intelligence (Expert) | Tinker/Tailor | Artisan | Architect/Engineer | Herbalist/Poisoner | Alchemist/Doctor |
| Will (Adept) | Hermit/Monk | Nursemaid/Nun | Sorcerer | Scholar | Priest/Witch |
| Luck (Noble) | Beggar | Dancer | Bard | Traveler | Prince |

Your DM might tell you to pick other titles within categories that they think would be interesting for this campaign:
* **Bonds** that describe relationships to each other, a patron, an organization, etc. For instance:
  * With whom 1d...: 1-3: A patron or organization, 4-5: The player to your right, 6: The player to your left
  * ...Of nature 1d: 1-3: Debt, 4-5: Pact or Amity, 6: Kin or History
* **Ideals** that describe drives, alignments, creeds, etc. For instance:
  * Alignment: 1-3: Neutrality, 4-5: Chaos, 6: Law
  * Creed: 1-2: Church (High, Green, 
* **Traits** that describe species, race, culture, etc.
  * **Quirks** that make your character more fun, like flaws, appearance, old injuries, behaviors, etc.

> Alice's character has a high reflex and middling luck, so she was a _scout_. She decides her character is English (and human), a stout & pockmarked Protestant Kingswoman of Leeds.
> Bob's character has a high will and low luck, and so he was a _herald_. He decides his character is a pagan faerie Envoy from the Thistledowns, with fish-scale skin and here to ensure the Pretender claims the throne of Wales.
> Carol is always a red-haired dwarf, and in this game she chooses no differently: she's wound up with a Dwarven Cook -- and she'll figure out the rest as she goes.

> **BUT I WANT TO BREATHE FIRE**
> Perhaps you want to portray a (baby) dragon, a (fallen) angel, adventuring dryad, or other monstrous or inhuman creature.
> Sometimes this is just a trait -- a "goblin scullion" or "dwarven 


When a title is relevant, the DM might give _advantage_ or _disadvantage_, adjusting the DC (especially for skill or project rolls).
Don't worry, you'll acquire more titles as the game goes on.

## Level Up

All attribute improvement works the same way: roll 1d vs a DC of the attribute's current value.
If the attribute is already 7 or higher, use a DC of 6 but require 1 additional hit per point above 6 (which itself requires a crit).
On a hit, improve the attribute by 1 point (before resolving whatever situation called for the improvement!).
If the roll fails, the opportunity for advancement is lost.
Generally, the DM should allow only one opportunity for advancement per character per session.

### Level Up
Gain a new level when you spend 1000 sp per current level & 1 week per current level training with a tutor.
The DM can waive any percentage of this fee or time for any reason (story awards, tutor with cheaper rates, demonic pacts, etc).

A character can spend their Level Up on one of:
* HD: As attribute improvement
* MD: As attribute improvement
* KD: As attribute improvement
* an Item's Uses: As attriute improvement
* Claim a Feat Title: No roll; commemorate a moment of awesome or something we learn about your character.

### Tier Improvements
A level 1 character is entitled to an improvement at each of level 1, 2, 4, 7, 11, 17, 22, etc.

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
You might insist that there's a hand limit or something, so that 3 daggers is 1 dagger too many; use your best judgment.
It is free to lay hands on any readied item.

## Encumbranced
You can purchase additional stacks of stowed items by Readying "Encumbered: -25% speed; -1d to speedy, athletic or sneaky tasks".
This purchases +5 + CON unreadied slots each time.

Every 10-20 pounds of other gear is another slot of gear: for instance, every 500 coins.
An unconscious friend weighs 10 slots (+ their gear).

Randomly determine which item is drawn from one of these stacks when time is of the essence.

## Uses & Durability
Most items take one slot and have 3 Uses -- bundles of 3 single-use torches, packs of 3 weekly rations, etc.
This is sometimes written "Some Item (3)" or "Some Other Item (1)" or "(7)" or whatever.

Particularly large objects might take multiple slots.

When a durable item uses its last (or if intentionally destroying an object), roll damage using durability as block dice.
Destroy on any hits, otherwise just damage.

| Material | Durability |
|---|---|
| Cloth, Paper, Soft Leather, Wax | 0 |
| Crystal, Glass, Ice | 1 |
| Bone, Wood, Hard Leather | 2 |
| Silver | 3 |
| Clay, Stone | 4 |
| Bronze | 5 |
| Iron, Steel | 6 |
| Adamant | 7 |

## Starting equipment

There are alternative suggestions for starting equipment in the section on Magic.
Otherwise:

Roll Luck; fill up to that many slots of inventory with Armor & Helms, your choice how (you might not get any!).
Armor Uses absorb Hits of damage 1:1, and are repaired at 5% of the item cost per use restored.
Heavier metal armors also provide dice of block!

| Armors | Cost | Slots | Uses | Block | Notes |
|---|---|---|---|---|---|
| None | 0sp | 0 | 0 | 0b | Naked! Or clothes, robes, etc |
| Leather | 10sp | 1 | 3 | 0b | Or hide armor, winter clothing, heavy robes, or pauldrons; absorb 1 during Use |
| Scale | 25sp | 2 | 6 | 0b | Lamelar, chain shirt, or reinforced leather |
| Chain | 50sp | 1+1 Encumbered | 7 | 1b | Maille or breastplate |
| Half plate | 200sp | 1+2 Encumbered | 8 | 2b | Banded, splint, or plates-and-mail |
| Full plate | 1000sp | 2+2 Encumbered | 9 | 3b | Full gothic platemail |
| Helm | 10sp | 1 | 0 | 1b | Doesn't stack with chain or better |

Roll Luck; fill that many slots of inventory with your choice of weapons, shields, and ammunition.
If you got 0, you can choose 1 simple, crude, or thrown weapon.

You can mark a Use of your melee weapon (or ammunition) to expand your crit range by 1 for an attack (after seeing the potential crit!).
You can mark a Use of your shield to decrease the crit range by 1 for a save (after seeing the crit!).
You can mark a Use of your ranged weapon for advantage on an attack to counteract a penalty from range, firing into melee, etc.

| Weapon Type | Cost | Slots | Damage/Block | Examples |
|---|---|---|---|---|
| Melee, Simple | - | 1 | 0d | Dagger (3), club(1), whip(1) |
| Melee, Crude | - | 2 | 1d | Staff |
| Melee, Light | 1 | 1d | Sword, hatchet, mace, javelin |
| Melee, Heavy | 2 | 2d | Battleaxe, flail, spear |
| Melee, V. Heavy | 3 | 3d | Halberd, maul, lance, greatsword |
| Shield, Small | 1b | - | Buckler, targe, round wooden |
| Shield, Large | 2b | - | Kite, tower, large steel |
| Thrown (3) | 1 | 0d | Darts |
| Ammunition (3) | 1 | 0d | arrows, bolts, sling + stones, etc. |
| Ranged, Light | 1 | 1d | (Req Ammunition) Shortbow, hand crossbow, slingshot |
| Ranged, Heavy | 2 | 2d | (Req Ammunition) Longbow, crossbow, pistol |
| Ranged, V. Heavy | 3 | 3d | (Req Ammunition) Arbalest, Rifle |

Roll or choose Luck times below:
| d66 Gear | 1 | 2 | 3 | 4 | 5 | 6 | Or Else |
|---|---|---|---|---|---|---|---|
| 1 (Tools) | Chisel/Drill | Hacksaw | Hammer | Shovel | Rasp/File | Crowbar | Penknife |
| 2 (Camp Gear) | Bedroll | Tent | Cookpot | Iron Rations (5) | Tinderbox | Fishing Net | Soft Rations (3) |
| 3 (Cave Gear) | Pole, 10' | Chain, 10' | Pitons | Rope, 50' | Lantern+Oil (6) | Glowstone | Torches (3) |
| 4 (Thief Kit) | Caltrops | Glass Marbles | Lockpicks | Steel Wire | Manacles | Trap | Large Sack |
| 5 (Finery) | Musk | Pot Grease/Oil | Strong wine | Ink+Pen | Glue | Mirror, steel | Dice |
| 6 (Specialty) | Belladonna | Medicine (3) | Poison (1) | Acid | Mercury | Sulfur | Garlic/Salt | 

Afterwards you may choose to take the "or else" from any line in which you didn't get a result already.

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

Describe a hit with relish, then cancel it with HD:
> Dave describes how Alice gores Bob with her lance -- she'd scored an impressive 3 hits.
> But Bob still has HD left, and so he describes avoiding the blow at the last second.
> If he'd spent armor uses, he might describe it as glancing off a shield or armor.
Otherwise, we're looking at an Injury.

## Injury
Roll 1d per hit taken +1d per previous roll on the table today vs LUCK + armor block

| Injury Hits | Result |
|---|---|
| 0 | Momentary stun |
| 1 | & 1 Injury: -1d attack & -1b saves & -25% move |
| 2 | & knocked out |
| 3 | & dying |
| 4 | & dead |
| 5+ | & flagrantly dead |

Slots of injury are just like any other readied item.
They go away with medical attention and time, at least 1 month.

# Magic

During character generation, instead of choosing to roll for Armor you can choose to roll for slots of Relics.
Similarly, instead of Weapons, you can choose to begin with slots of Tricks.
Even if you trade initial Weapons for Tricks, you can still begin with a Simple, Crude, or Thrown weapon.

## Relics & Spells

Each Relic is a physical object that holds spells: a piece of a saint, a blessed amulet, a spell scroll, a magic wand, etc.
Some Relics could even be weapons, armor, etc -- but not for your starting adventurer.
Starting Relics contain 1 Spell (with 1 Use).
To cast the spell, test the Spell's Complexity against Will (or sometimes Intellect).
Spend MD for each Hit, or else roll for the spell's Miscast (this usually involves at least ticking its use).

| d6 | Relic | Spell School | Notes |
|---|---|---|---|
| 1 | Wand | Evocation | Blasts, gouts, beams, conjurations, etc. Complexity 2d6 take higher value; other die element 1: mist, 2: wind, 3: fire, 4: lightning, 5: ice, 6: stone. Miscast Fallout. |
| 2 | Icon | Intercession | Subtle spells of enhancement and encouragement. Complexity 2d6 take lower value; other die method 1: cursing 2: divining 3: enhancing 4: protection 5: smiting 6: health. Miscast Karmic. |
| 3 | Scroll | Summoning | Conjured servants, far travel. 1d6 Power 1: undead 2: demon 3: alien 4: fey 5: elemental 6: construct; 1d6 complexity. Miscast Fallout or Karmic (by Power). |
| 4 | Stone | Phantasm | Seeming, mentalism, and misdirection. Complexity 2d6 take lower; other die method 1: hallucination 2: confusion 3: love 4: dreams 5: fear 6: mundanity. Karmic. |
| 5 | Mask | Viridity | Geomantic, beast- and plant- related; transformation. Complexity 1d6; Association 1d6 1: forests 2: mountains 3: swamps 4: plains 5: oceans 6: skies. Miscast Fallout. |
| 6 | Bell | Artifice | Spells of crafting, metamagic, ritual. Complexity 1d6; effects very varied. Miscast Karmic. |

Some standby adventuring spells:
* Flute of Hypnosis (Complexity 1): Test while playing at +1 complexity each round for as long as you dare. Creatures hearing the sound test (#rounds played)d vs Will; more hits than HD knocked out into slumber. If critted, suggestible while asleep & sleepwalk.
* Chime of Opening (Complexity 2): all doors, latches, etc spring open to the sound.
* Augurs Dice (Complexity 2): 1d DC 2; on hit, Weal, Woe, or Uncertain to a question about the next hour. +1DC per cast within that hour.
* Wand of fireballs (Complexity 3): 6d to all in 20' radius within a bowshot; sets fire.
* Wand of Lightningbolts (Complexity 4): 8d to all in 60' line within a bowshot; sets fire.
* Rod of Cold (Complexity 5): 10d to all in a 120' cone. Freezes ice solid.
* Mask of Wolfseyes (Complexity 4): Your gaze deals 8d and on 0hd, transforms into a prey animal.

Others might include the effects of a trick, available as a Relic.

| (hits)d - Will + miscasts | Karmic | Fallout |
|---|---|---|
| 0 | Tick Use | Tick Use |
| 1+ | & -(hits)d forward until you take damage | & take (hits)d feedback |

## Tricks

Each Trick is a one-time consumable item like a potion, oil, poison, bomb, dust, drug, or similar.
Theoretically once used it's gone.
Practically, you've got a source for _these_ Tricks you pick up during character generation, and can restock in some way that makes sense for your background.
But a trick you pick up during an adventure is more likely one-and-done.
You can always use downtime projects to try to arrange a more continuous supply.

Smoke Bomb: 
Bomb (1): 6d


### Tier 0
* Lightspell: Cast light as a torch.
* Oilbomb: 10' wide pool of oil. Catches alight, dealing 2d dmg for minutes, anyone hit on fire 1d ongoing
* Charcoal: Absorbs swallowed or breathed poisons.
* Detect Magic. Sense the presence of magic/supernatural evil/etc.

### Tier 1
* Hypnotism: 0d attack in area, then 1d attack, then 2d attack, etc. Any hits beyond HD knock out the target, and it's suggestible if >HD hits. BUT: Cast each round to absorb hits.
* Fog Cloud: Make area opaque while you concentrate, then until dissipates naturally (10m).
* Potion of Curing: Heal 1 Injury (no effect on HD).
* Hex: -1d to damage and saves (1m).
* Firebomb: 2d damage to everyone in 10'; anyone hit on fire 1d ongoing.
* Abjure: 3d against supernatural evil; hits cause recoil.
* Protection: +1b against spells and attacks of supernatural evil.

### Tier 2
* Bless: +1d to damage and saves (1m).
* Phantasmal Forces: One creature also perceives what you want (10m).
* Invisibility: One creature is hidden from perception while they creep (10m).
* Gust of Wind: Use your Will as Str at range
* Entangle: Area deals 3d on first contact; hits Ensnare.
* Suggestion.
* Mindlink.
* Locate Object
* Augury
  
### Tier 3
* Fireball. 5d fire to all in a ball, hits alight 1d.
* Lightning Bolt. 6d lightning to all in a line.
* Clairvoyance. Detect eyes, and see through them.
* Dispel Magic.
* Bestow Curse.
* Animate Dead

### Tier 4
* Polymorph
* Dimension Door
* Wall of Fire/Ice

### Tier 5
* Heal
* Cone of Cold
* Wall of Stone/Iron
* Raise Dead
* Teleport

### Tier 6
* Disintegrate
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
