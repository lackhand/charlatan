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

When the pool size is...

| #d | #b | You will... |
|---|---|---|
| ... | ... | ... |
| -2 | 4 | Roll 4 dice and keep the lowest one. |
| -1 | 3 | Roll 3 dice and keep the lowest one. |
| 0 | 2 | Roll 2 dice and keep the lowest one. |
| 1 | 1 | Roll 1 die. Count it if it hits or crits. |
| 2 | 0 | Roll 2 dice. Count any that hit or crit. |
| 3 | -1 | Roll 3 dice. Count any that hit or crit. |
| 4 | -2 | Roll 4 dice. Count any that hit or crit. |
| ... | ... | ... |
| 7 | -5 | Roll 7 dice. Count any that hit or crit. |
| 8 | -6 | Roll 2 dice. Assume the other 6 were `[1, 2, 3, 4, 5, 6]` (which includes at least one crit). |
| 9 | -7 | Roll 3 dice. Assume the other 6 were `[1, 2, 3, 4, 5, 6]` (which includes at least one crit). |
| ... | ... | ... |
| 13 | -11 | Roll 7 dice. Assume the other 6 were `[1, 2, 3, 4, 5, 6]` (which includes at least one crit). |
| 14 | -12 | Roll 2 dice. Assume the other 12 were `[1,1, 2,2, 3,3, 4,4, 5,5, 6,6]` (which includes at least two crits). |
| ... | ... | ... |

## Players roll all of the dice.

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

Player characters have six attributes which measure their capability in broad swathes; humans tend to be in the range 0-4 but could go beyond that range:

* **STRength:** Resist paralysis, obstacles, impediments, or melee blows; power through.
* **REFLex:** Resist missiles, blasts, surprises, and detection; evade or become aware.
* **INTellect:** Resist confusion, distraction or hesitation; know how to do something & do it.
* **WILL:** Resist fear, compulsion, magical or social attacks; convince or resist.
* **CONstitution:** Resist poison, fatigue, transformation, and death; Carry more & carry on.
* **LUCK:** Begin with better gear and social standing; resist terrible fates.

> NPC attributes are a little bit simpler than player character's attributes, but otherwise work the same way.
> * **FORTitude:** A monster's Strength and Constitution. Small things can't use the fort they have as well as big things.
> * **INSTinct:** A monster's Reflex and Intellect. Animal intelligences can't use the inst they have as well as complex intelligences.
> * **WILL:** The monster's Will (& luck in a pinch).

Roll 3d DC 4 (no crits) for each of str, refl, int, will, & con (but not luck!) in order, then switch 2 (if you want).
* Start your luck at 0.
* For every other attribute equal to 0, increase your luck by 1.
* For every other attribute equal to 1, increase your luck by 1/2.
* For every other attribute equal to 2, increase your luck by 1/3.
* Round down.

> Rolling an attribute: When you're told to "roll strength", add to the pool 1d per point of strength.
> When you're told to "reflex save", add 1b per point of reflex.
> And so on.
> By default, you're counting hits of damage; by default, that's against DC 4.

## Titles

Select a **Background Title** based on your **highest attribute** (if several are tied, you can choose one) and your **luck score**:

| ... | 0 | 1 | 2 | 3 | 4+ |
|---|---|---|---|---|---|
| Strength (Warrior) | Barbarian | Gladiator | Guard/Soldier | Squire | Knight |
| Reflex (Hunter) | Ratcatcher | Thief | Scout/Outlaw | Ranger | Spy | 
| Health (Laborer) | Scullion | Farmer/Shepherd | Cook/Poisoner | Sailor | Merchant |
| Intelligence (Expert) | Tinker/Tailor | Artisan | Architect/Engineer | Herbalist | Alchemist |
| Will (Adept) | Hermit/Monk | Nursemaid/Nun | Sorcerer | Witch | Priest |
| Luck (Noble) | Beggar | Traveler | Scribe | Entertainer | Prince |

Your DM might tell you to pick other titles for your **nationality**, **race**, **religion**, **appearance**, **alignment**, etc (whatever might come up in your game).
> Alice's character has a high reflex and middling luck, so she was a _scout_. She decides her character is English (and human), a stout & ruddy Protestant Kingswoman of Leeds.
> Bob's character has a high will and low luck, and so he was a _herald_. He decides his character is a pagan faerie Envoy from the Thistledowns, armed in fish-scales and here to ensure the Pretender claims the throne of Wales.
> Carol is always a Dwarf, and in this game she chooses no differently: she's wound up with a Dwarven Cook -- and she'll figure out the rest as she goes.

When a title is relevant, the DM might give _advantage_ or _disadvantage_, adjusting the DC (especially for skill or project rolls).
Don't worry, you'll acquire more titles as the game goes on.

## Derived statistics & leveling
At every tier (including your first), a character gets 1 **T**ier **P**oint to spend in-game.
Each session, you can try to spend any unspent Tier Point(s) once; if you fail the opportunity, you have to wait until the next session to try again.
* +1 to **one stat**: While testing that stat, roll 1d vs a DC of the stat's current value. If you match or beat, increase the stat by 1 now and forever.
* +1 to **melee**: While rolling a melee attack or defense, roll 1d vs a DC of your number of melee dice. If you match or beat, increase your melee dice by 1 now and forever (starts at 0d).
* +1 to **ranged attacks**: While rolling an attack with any kind of ranged weapon (thrown, seige, etc)... otherwise as **melee**.
* +1 to **dodging**: While rolling a defense against a physical threat... (vs ranged, melee, blasts...)
* +1 to **magic skill**: When saving to activate a spell or device...
* +1 to **magic power**: When rolling spell damage (or other impact)...
* +1 to **magic defense**: When saving against a spell or power's effects...
* +1 to **skill**: While rolling a skill check... (vs _all_ skill and project checks!)

These pools of dice make you better at default adventurer checks -- attacks, defenses, magical casting or skill checks -- forever.
> Alice has +1 melee dice. She gets +1d to attacks with melee weapons, and +1b to defenses against melee weapons.
> She also then picks up +1b to dodging. She has a total of +2b to dodge melee weapons, on top of her shield, armor, or agility (if any).

**L**evel **P**oints work the same way as TP, but more frequently.
* +1 to **H**it **D**efence: When you would take damage at 0 HD, roll 1d vs a DC of your current max HD. If you match or beat, increase your max and current by 1 now and forever.
* +1 to **M**ana **D**efence: As HD, but for absorbing hits on a spellcasting check. This lets you convert spellcasting save hits into misses.
* +1 to **S**kill **D**efence: As HD, but for skill checks or projects. This lets you convert hits into misses.
* Invest Item: When you would mark use: Roll 1d vs DC of item max uses; if you match or beat, increase remaining & max uses by 1 now and forever, and give it a Title.
* New Feat: When you accomplish a feat, spend a LP to mark the occasion and take a title.

Whenever you sleep, you get back all of your HD, MD, and SD.

### Level Up
You level when you spend 1000 sp per current level & spend 1 week per current level training with a tutor of at least 2 levels above current level.
You can supplement this number with xp from monsters slain, at 10xp per HD, and freeform xp (no fixed schedule).

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
