# dice & danger

A simple hack of old school dungeon crawling games in the vein of Into the Odd (and many other hacks).
Great gratitude to Ben Milton's CC BY 4.0 Maze Rats.

> This is a d6-based DIY elfgame about adventurers and their explorations into funhouse dungeons.
> One of you is the DM (Narrator, Referee, Judge), and the other Players have Player Characters (the DM also has Non-Player Characters).
> Much more ink has been spilled about How To Play an RPG; go there for more.

Have fun!

# Players roll d6s to determine damage given or received

The _damage source_ adds (or unusually removes) the number of six-sided **d**ice of **d**amage to the pool, like +1d or +4d.
> For instance, shortswords are 1d, longswords are 2d, and polearms 3d.

The _situation_ might give _advantage_ or _disadvantage_ to a roll, changing the **d**is**c**ard number.
**If it doesn't say otherwise, then the DC is 4**, but an easier check might have DC 3 or even 2; a harder check might have DC 5 or even 6.
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
* Sometimes anyone (including the DM) just rolls dice to randomize what happens next.
  That's different.

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

> Note: As a starting character of Level 1, you have one **T**ier **P**oint and one **L**evel **P**oint to spend.

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
> * **WILL:** The monster's Will. This is pretty universal, and can also include their luck in a pinch.

Roll 3d DC 4 (no crits) for each of str, refl, int, will, & con (but not luck!) in order, then switch 2 (if you want).
* For every attribute equal to 0, increase your luck by 1.
* For every attribute equal to 1, increase your luck by 1/2.
* For every attribute equal to 2, increase your luck by 1/3.
* Round down.

> Rolling an attribute: When you're told to "roll strength", add 1d per point of strength.
> When you're told to "reflex save", add 1b per point of reflex.
> And so on.
> By default, you're counting hits of damage; by default, that's against DC 4.

## Titles

Select a **Background Title** based on your **highest attribute** (if several are tied, you can choose one) and your **luck score**:

| ... | 0 | 1 | 2 | 3 | 4+ |
|---|---|---|---|---|---|
| Strength (Warrior) | Barbarian | Gladiator | Guard/Soldier | Squire | Knight |
| Reflex (Hunter) | Ratcatcher | Thief | Scout/Outlaw | Ranger | Spy | 
| Health (Laborer) | Farmer | Sailor | Cook/Poisoner | Merchant | Armorer |
| Intelligence (Expert) | Tinker/Tailor | Artisan | Architect/Engineer | Herbalist | Alchemist |
| Will (Adept) | Hermit/Monk | Herald | Sorcerer | Witch | Priest |
| Luck (Noble) | Beggar | Traveler | Scribe | Entertainer | Prince |

Your DM might tell you to pick other titles for your **nationality**, **race**, **appearance**, **alignment**, or **creed** (whatever you're using in the game).
> Alice's character has a high reflex and middling luck, so she was a _scout_. She decides her character is English (and human), a stout & ruddy Protestant Kingswoman of Leeds.
> Bob's character has a high will and low luck, and so he was a _herald_. He decides his character is an enigmatic faerie Envoy from the Thistledowns, armed in fish-scales and here to ensure the Pretender claims the throne of Wales.

When a title is relevant, the DM might give _advantage_ or _disadvantage_, adjusting the DC (especially for skill or project rolls).
You'll acquire more titles as the game goes on.

## Derived statistics & leveling
At every tier (including your first), a character gets 1 **T**ier **P**oint to spend in-game.
Each session, you can try to spend any unspent Tier Point(s) once; if you fail the opportunity, you have to wait until the next session to try again.
* +1 to one stat: While testing that stat, roll 1d vs a DC of the stat's current value. If you match or beat, increase the stat by 1 now and forever.

**L**evel **P**oints work the same way as TP, but more frequently.
* +1 to **H**it **D**ice: When you would take damage at 0 HD, roll 1d vs a DC of your current max HD. If you match or beat, increase your max and current by 1 now and forever.
* +1 to **M**ana **D**ice: As HD, but for MD.
* Invest Item: When you would mark use: Roll 1d vs DC of item max uses; if you match or beat, increase remaining & max uses by 1 now and forever, and give it a Title.
* New Feat: When you accomplish a feat, spend a LP to mark the occasion and take a title.

You can spend hit dice to absorb dice of incoming damage.
If you're out of hit dice, you'll take injuries (most NPCs just get knocked out at this point).
You can spend mana dice to attempt to cast magic spells.
If you're out of mana dice, you can't cast any more spells.

Whenever you sleep, you get back all of your HD and MD.

### Level Up
You level when you spend 1000 sp per current level & spend 1 week per current level training with a tutor of at least 2 levels above current level.
You can supplement this number with xp from monsters slain, at 10xp per HD.

# Inventory

You may carry Ready (equipped, on your body or in your hands) 6 + CON items in slots.
Readied armor (shields, helms, etc) gives you bonus dice of block, 1:1 per slot.
Readied melee weapons give bonus dice of damage, 1:1 per slot.
You might insist that there's a hand limit or something, so that 3 daggers is 1 dagger too many; use your best judgment.
Missile weapons are the same as melee, but require you to also be carrying Ammunition (a 1-slot penalty).
Armor, (but not shields or helms) and any items past this Ready limit are Encumbering.

## Starting equipment

Choose Armor or Instruments -- see later for details on that choice.
Roll Luck; fill that many slots of inventory with your choice.

| Armors | Slots | Block | Notes |
|---|---|---|---|
| None | 0 | 0b | Naked! Or clothes, robes, etc |
| Leather | 1 | 1b | Or hide armor, winter clothing, heavy robes, or pauldrons |
| Scale | 2 | 2b | Lamelar, chain shirt, or reinforced leather |
| Chain | 3 | 3b | Maille or breastplate |
| Half plate | 4 | 4b | Banded, splint, or plates-and-mail |
| Full plate | 5 | 5b | Full gothic platemail |
| Helm | 1 | 1b | Doesn't stack with chain or better |

Choose a category: Melee Weapons (includes Shield), Ranged Weapons (comes with Ammunition), or Tricks -- see later for details.
Roll Luck; fill that many slots of inventory with your choice.

| Weapon Type | Slots | Damage/Block | Examples |
|---|---|---|---|
| Melee, Simple | 1 | 0d | Dagger, club, whip |
| Melee, Crude | 2 | 1d | Staff |
| Melee, Light | 1 | 1d | Shortsword, hatchet, mace, javelin |
| Melee, Heavy | 2 | 2d | Longsword, battleax, flail, spear |
| Melee, V. Heavy | 3 | 3d | Halberd, greatsword, maul, lance |
| Shield, Small | 1b | - | Buckler, targe, round wooden |
| Shield, Large | 2b | - | Kite, tower, large steel |
| Thrown (3) | 1 | 0d | Darts, sling + stones |
| Ammunition (3) | 1 | - | arrows, bolts, etc. |
| Ranged, Light | 1 | 1d | (Req Ammunition) Shortbow, hand crossbow, slingshot |
| Ranged, Heavy | 2 | 2d | (Req Ammunition) Longbow, crossbow, pistol |
| Ranged, V. Heavy | 3 | 3d | (Req Ammunition) Arbalest, Rifle |

Roll or choose Luck times below:
| d66 Gear | 1 | 2 | 3 | 4 | 5 | 6 |
|---|---|---|---|---|---|---|
| 1 | Musk (1) | Chisel/Drill | Grease | Tongs | Rasp | Pole, 10' |
| 2 | Trap | Crowbar | Hacksaw | Hooded/Bullseye Lantern (6) | Iron Rations (5) | Tinderbox |
| 3 | Bedroll | Net | Hammer | Large Sack | Rope, 50' | Glowstone (1) |
| 4 | Caltrops (1) | Glass Marbles (1) | Salt/Garlic (1) | Lockpicks | Steel Wire | Acid vial (1) |
| 5 | Chain 10' | Glue | Horn | Manacles | Shovel | Poison vial (1) |
| 6 | Chalk | Grappling Hook | Wooden/Iron spikes | Medicine (3) | Mirror, steel | Strong wine (3) |

After everything:
* If you don't have any light sources, you may take "torches (3)".
* If you don't have any food, you may take "soft rations (3)".
* If you don't have any weapons, you can take one of: dagger, club, whip, staff, darts (3), or sling (& stones 3).
* You are flat broke.

Go adventure!

## Uses & breakage
Consumable items come in bundles of (usually) 3; sometimes 1 for bulkier items, sometimes more for finer items.
Mark a use of a consumable item like a potion or a flask of oil when you consume the whole thing.
Permanent items have 3 Uses if not otherwise state before they break.
For other items:
* Test ammunition at most once each fight when the DM asks: test luck, marking 1 use on 0 successes.
* Mark weapons and armor when you take injuries

When you mark the last use of a permanent weapon, test if it's destroyed, just like an injury using the listed durability instead of luck.

| Material | Durability |
|---|---|
| Cloth, paper, rope | -1 |
| Leather | 0 |
| Bone, wood | 1 |
| Clay, stone | 2 |
| Bronze | 3 |
| Iron, Steel | 4 |

Repair items at 10% of their cost per Use.

# Combat

* Melee: roll STR + weapon dice vs STR + armor dice + shield dice.
* Missile: roll INT + weapon dice vs REFL + armor dice + shield dice.

If someone is unawares, they can't use their STR, REFL, or shield.

## Injury
Every hit of damage takes away a HD or, if there are none left, makes a roll on the Injury table.
Roll 1d per remaining hit +1d per previous roll on the table today vs LUCK + 1d if helmet (or chain or better)

| Injury Hits | Result |
|---|---|
| 0 | Momentary stun |
| 1 | & take incoming damage as slots of injury |
| 2 | & knocked out |
| 3 | & dying |
| 4 | & dead |
| 5+ | & flagrantly dead |

You can mark armor uses to reduce this scale of injury 1:1.

Slots of injury are just like any other readied item.
They go away with medical attention and time, at least 1 month.

## Encumbrance & movement
Every 250 coins counts as 1 slot.

| Armor + un-readied items | Penalty (swim, sneak, etc) | Speed |
|---|---|---|
| 0-1 | n/a | 12"/rd |
| 2-3 | disadvantage | 9"/rd |
| 4-6 | 2x disadvantage | 6"/rd |
| 7+ | autofail | stagger a few steps |

# Magic Things

There are several interlocking systems:
* Tricks are things like potions, oils, bombs, drugs, spell-scrolls, etc. They allow a one-time effect when used correctly.
  * Spells are special tricks that are more powerful than equivalent tricks, but require difficult Casting before use.
* Instruments are things like fire wands, a ray gun, a spell book, or a holy relic. They are durable items which consume their own uses over time.

## Instruments
If you selected instruments at character generation, your luck roll determined the tier of instrument you begin with.
It takes up 1 or 2 slots and gives +1d or +2d to Cast.
Its tier is also its number of Uses.

| Luck roll/Tier | Example |
|---|---|
| 0 | Wooden symbol, simple yew wand, drum |
| 1 | Silver symbol, athame, amulet, clay flute |
| 2 | Live wood staff, lute, saint's hair |
| 3 | silver flute, orb, tome |
| 4 | magic wand, saint's bone |
| 5 | Enchanted staff, holy crown |

...which has an affinity with...

| Roll | School |
|---|---|
| 1 | Consecration: Subtle magics of detection, protection, healing, and fate |
| 2 | Evocation: Powerful magics that manipulate elemental concepts like 'fire' and 'iron' |
| 3 | Viridity: Spiritual and natural powers relating to plants, animals, life, and nature |
| 4 | Phantasm: Illusion, emotion, psychic and shadow manipulation |
| 5 | Diabolism: Necromancy, consorting with devils, summoning creatures, madness |
| 6 | Artifice: Scientific & meta-magics; alchemy, enchantment |

> Alice got a lucky 3 hits on her luck check, scoring a 1 slot mineral orb with 3 uses, and spells of consecration.

## Tricks

These include spells, potions, oils, etc.
They're effectively single use.
Wizards can use their MD to purchase spells during the adventure as needed via their Instruments.

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
