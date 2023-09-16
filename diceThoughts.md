# dice & danger

A simple hack of old school dungeon crawling games in the vein of Into the Odd and many other hacks.

# This is a d6-based DIY elfgame

* There is a DM and the rest of you are Players with Player Characters
* You'll want about 8 six sided dice per player, pencils, paper, etc.
 * The core mechanic is to roll a die and compare them to a target number.
* The characters have:
  * A level (starts at 1) which gives you per-level Titles & hit dice
  * Slot-based inventory & conditions
  * Attribute scores usually from 0 to 6
  * A yen for treasure (which gives experience) and for danger

Have fun!

# Your Character

Randomly generate your character's attributes, equipment, and details, and then start playing!

## Your Attributes

For each attribute below, roll 3 dice and note how many of their values are 4+; that's your bonus with that attribute.
Your attributes set the difficulty of your saves, and are bonus dice on your attacks and skills; higher is better.

* **Strength.** Use force to overcome an obstacle. Bursting bonds. Lifting a great weight. Running, climbing, jumping, swimming. Resisting paralysis, grappling, or being crushed. Blocking a melee attack.
* **Reflex.** Use instinct or agility to avoid an obstacle. Resist surprise, a missile weapon, a fireball, or a pit trap. Avoid detection or apprehension. Walk a tightrope.
* **Health.** Resist illness, disease, or death. Resist heat, or cold. Endure. Carry more things, or take more conditions.
* **Craft.** Use training & concentration to overcome an obstacle. Doing it right the first time. Making the shot. Perfect even stitches. Picking the lock. Juggle. Being a quick study. Know the answer. Pick a pocket.
* **Will.** Use force of personality to overcome an obstacle. Resist despair, fear, or temptation. Tame a mule, lead an army.

You can now switch the values of two attributes if you want.

### Special Attributes

Some special numbers which work a little like attributes, but are actually set in some other way.

* **Luck.** Initial equipment, wound table outcomes, and decide who the monster goes for. Sum the other 5 attributes above and compare:
  * 0-1: Luck 5
  * 2-3: Luck 4
  * 4-6: Luck 3
  * 7-10: Luck 2
  * 11-15: Luck 1
  * 16+: Luck 0
  > This is only for luck at character generation! Afterwards, it's its own statistic.
* **Armor.** Use whatever you're wearing to defend against attacks.

> _Optional Rule: More Stats._ Depending on the scenario, you might use other stats like _Faith_ or _Reason_; _Authority_ or _Empathy_... 

## Level & Class
You have 0 XP (e**X**perience **P**oints), are Level 1, and are therefore a Novice tier adventurer.

You have 1 HD per level (1 HD now).

Each time you gain a level, roll 1d vs a stat of your choice.
* On a hit, raise the stat by 1.
* Otherwise (or if you prefer), gain a new Title describing your exploits.

Each time you gain a tier (at levels 0, 1, 2, 4, 7, 11, and 16), you will make a class selection.

Choose (or roll) your class, use it to decide your background, and then make your 2 choices (0th & 1st level) from it.
I guess you could take them in two different classes if you wanted.

| lower of 2d | Highest Stat | class |
|---|---|---|
| 1 | Health | Commoner |
| 2 | Strength | Warrior |
| 3 | Reflex | Expert |
| 4 | Craft | Adept |
| 5 | Will | Noble |
| 6 | ??? | ??? |

### Commoner

| Luck | Background |
|---|---|
| 0 | Shepherd: Crook, leather armor, shears, pail |
| 1 | Scullion: Knife, shield, pots, salt |
| 2 | Sailor: Rope, club, chart, sewing kit |
| 3 | Clerk: Recordbook, drab clothing, ink, lens |
| 4 | Farmer: Pitchfork & pet goose, pig, or dog |
| 5 | Tourist: Loud clothing, bag of money, wineskin |
* **Benefit.**
  * +1 inventory slot
  * +1 HD

### Warrior

| Luck | Background |
|---|---|
| 0 | Barbarian: Axe, shield, skulls, fur cloak |
| 1 | Pit Fighter: Leather armor, club, prize belt |
| 2 | Bandit: Leather armor, bow, dagger, green cloak |
| 3 | Guard: Leather armor, spear, bell, badge |
| 4 | Squire: Scale armor, sword, shield, hawk |
| 5 | Soldier: Scale armor, spear, crossbow |
* **Benefit.** Choose one each time:
 * +1d to weapon attacks
 * +1d to weapon defenses
 * +1d vs spellcasters, or chimeras, or giants, etc
 * +2 inventory slot for weapons & armor

### Expert

| Luck | Background |
|---|---|
| 0 | Thief: lockpicks, dagger, black cloak, silent shoes |
| 1 | Spy: disguise, rapier, papers, |
| 2 | Trapper: bow, dagger, green cloak, tough boots |
| 3 | Craftsman: tools, leather armor, some money |
| 4 | Poisoner: poison, dagger, wineskin, rations |
| 5 | Inspector: leather armor, lots of money, crony, 
* **Benefit.** Choose one each time:
  * +2 inventory slot for tools
  * +1d to a background's skills

### Adept

| Luck | Background |
|---|---|
| 0 | Monk: robe, staff, bowl |
| 1 | Sorcerer: robe, dagger, holy symbol |
| 2 | Seer: robe, orb, tome |
| 3 | Witch: robe, crook, herb pouch |
| 4 | Warlock: robe, familiar, sword  |
| 5 | Alchemist: leather apron, flask, tome |
* **Benefit.** Choose one each time:
  * +2 inventory slot for relics & spells, and spellburn.
  * +1d to cast skill
  * +1d to spell attacks
  * +1d to spell defenses

### Noble

| Luck | Backgorund |
|---|---|
| 0 | Bard: lute, fancy clothing, rapier |
| 1 | Priest: vestments, holy symbol, club, oil |
| 2 | Dancer: dagger, bracelets, kerchiefs |
| 3 | Jester: motley garb, puppet, dagger, bells |
| 4 | Merchant: scale, bag of money, lantern |
| 5 | Princess: dress, rapier, tome, bag of money |
* **Benefit.** Choose one each time:
  * +2 inventory slot for treasure & followers
  * +1d to inspire
  * +1d to intrigue

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

## Weapons & Armor

A melee weapon takes 1 slot & gives you +1d (2 slots & +2d if it's heavy).
A ranged weapon has the same rules, and also requires arrows (or stones) (so total 2 slots or 3 slots).
A small or large shield works the same as a melee weapon, but defensively.

| Dmg | Slots | Example Weapons | sp cost |
|-----|---|-----------------|---|
| +0d | 1 | Club, darts, dagger, whip | 1 |
| +0d | 2 | stones/bolts and a sling or hand crossbow | 10 |
| +1d | 1 | sword, axe, mace, rapier | 10 |
| +1d* | 1 | Light shield (to defense) | 10 |
| +1d | 2 | bullets/bolts/arrows and a gonne, light crossbow, or bow | 25 |
| +1d | 2 | staff, spear, flail | 5 |
| +2d | 2 | Lance, halberd, maul, greataxe, greatsword | 25 |
| +2d* | 2 | Heavy shield (to defense) | 50 |
| +2d | 3 | bullets/bolts/arrows and an arquebus, heavy crossbow, or longbow | 50 |

Armor is directly related to slots too:

| AC | Slots | Examples | sp cost |
|---|---|---|---|
| 2 | 0 | Clothing, robes, vestments | 1 |
| 3 | 1 | Leather armor, hide armor | 10 |
| 4 | 2 | Scale armor, chain shirt | 50 |
| 5 | 3 | Chain maille, breastplate | 200 |
| 5&1d | 4 | Half Plate | 1000 |
| 5&2d | 5 | Full Plate | 5000 |
| n/a | 0 | Helmet (+1d vs dismemberment) | 10 |

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

## Things to carry

You don't only carry baggage in slots, but also things.

### Weapons
A weapon gives +1d if it's appropriate.
If it's a heavy melee weapon, give it +2d instead (it takes another inventory slot).
If it's a ranged weapon, give it +1p.
A simple or crude weapon also gets +1p.

A shield gives +1p to the attacker. A tower shield gives -1d instead.

You can weild a light weapon in your offhand; it gives +2b.

* Swords (including knives): Quick, slashy, and finesse weapons
* Axes (including greatswords): Chopping destructive cleavey weapons
* Clubs (maces, flails, staves): Bludgeoning hammers
* Spears (polearms, missiles): Stabby pokey weapons

### Armor
No armor: DC 2 (+1p vs swords)
Leather: DC 3 (+1p vs spears)
Splint: DC 4 (+1p vs axes)
Chain: DC 5 (+1p vs clubs)
Plate: DC 6

Each armor takes 1 more inventory slot than the last.

### Wards
Exactly like armor, but for increasing Aura.
Things like Garlic, Holy Symbols, prayerbooks.

### Artifacts
These are magical objects which carry spells: wands, saints' fingerbones, spellbooks.


# How to Play
Real in-depth procedures for play and explanations of the above.

## Roll dice in play when there's danger (or on a table I guess)

The DM rolls dice to randomize something (a random encounter, or to generate treasure, or the weather, or the monster's mood).
The players roll the rest of the dice; they might do random generation or else roll for:

* A _damage roll_ to discover how well they do something; usually an attack but maybe a long term project.
* A _saving throw_ to mitigate a terrible fate into something more palatable; often a parry or dodge but maybe to avoid missing an opportunity.

More dice in the pool represent more danger. Fewer, more safety.

During a _damage roll_, each die with a face value at or over the _difficulty_ is a _hit_ (the low value "misses" don't matter).
During a _save roll_, each die with a face value at or over the _defense_ is a _hurt_ (the low value "saves" don't matter, either).
These are the same mechanic seen from the opposite sides, which is why the names are so similar; hits or hurts are both _harms_.
Usually, the attacking character sets the number of dice to roll, while the defending character sets the defense, but there are often a few bonus dice tricks here and there, too.

### Damage and Saves are mirror images

We have four titanic warriors that want to fight.
* the PC Alice with dmg 4, def 2
* her equivalent NPC: Alizard Man, with dmg 4, def 2
* Bob with dmg 3, def 3
* his equivalent NPC: Boblina Goblina, with dmg 3, def 3

> Alizard attacks Bob: Bob rolls a save with 4 dice and counts any which result in a 3+ as a hurt.
> Alice attacks Boblina: Alice would roll damage with 4 dice, and count any which result in a 3+ as a hit.
> In both cases odds of harms are: `[(0, <1%), (1, 10%), (2, 30%), (3, 40%), (4, 20%)]`

> Boblina attacks Alice: Alice rolls a save with 3 dice and counts any which result in a 2+ as a hurt.
> Alizard attacks Bob: would roll damage with 3 dice and count any which result in a 2+ as a hurt.
> In both cases odds of harms are: `[(0, <1%), (1, 7%), (2, 35%), (3, 58%)]`

> If Alizard attacks Boblina, I guess the DM plays out both sides, rolling for Boblina. Same if Boblina attacks Alizard.
> If Alice attacks Bob, let Bob roll the save out of courtesy. If Bob attacks Alice, let Alice roll the save.

### Dice method

Lots of things can modify both sides of this roll: adding dice, subtracting dice; giving the attacker or defender the choice of a reroll, etc.
* _Dutiful dice_ (`3d` means "3 dependable and _dutiful_ dice"): These are applied before the roll, and whichever player is entitled to them can choose how to apply them; in this case, to roll either 3 more dice or 3 fewer dice.
  > Bob is a _novice warrior_, so he gets 1d to his damage rolls in melee.
  > Bob is armed with a _scimitar_, so he gets an extra 1d to his damage rolls (2d so far).
  > Alizard is also a _novice lizard_, so gets 1d to his saves -- which the DM uses to reduce Bob's attack to 1d.
* _Quisling dice_ (`2q` means "2 treacherous, _quisling_ dice"): This are just like dutiful dice, but the other character in the roll gets to choose how to use them. 
  > Bob's arm is _injured_ and so he has 1q to his attacks from that. This brings Bob's attack down to 0d total.
  > But! Alizard is _slow_, and so he has 1q to his _armor saves_ from _that_! Bob uses this die to brings his attack back up to 1d!

Cancel out all of the dutiful and quisling dice, and then roll against the defender's DC.
> Bob rolls his 1d against Alizard's scaly hide (DC 4) and rolls a `[5]` -- a `hit`!

* _Bonus rerolls_ (`4b` means "4 blessed bonus dice"): Whichever player is entitled to these can pick (up to this number) of dice to reroll after seeing their value.
  > Bob has the title of _Swordmaster_, so gets 1b from that.
  > Bob's scimitar is the _Sirensong_ which gives 1b against lizards.
  > Bob is also _strong_, 1b more. Bob's bonus rerolls are at 3b so far.
  > Alizardman is using a _crude shield_, so gets 1b -- which subtracts from Bob's rerolls.
  > Bob has 2b rerolls so far.
* _Penalty rerolls_ (`2p` means "2 puny penalty dice"): Just like bonus rerolls, but the other character gets to choose how to use them.
  > Bob is _dazed_ (1p), leaving Bob with just 1p.
  > Alizard doesn't have any penalties.

Cancel out all of the bonus and penalty rerolls, and then if any remain, whoeever has the balance can pick which dice to reroll.
Remember how many dice were already hits before rerolling; whoever has control of the rerolls can decide if this can cause the number of hits to change!
> Bob has a bonus die, but he already hit. We're not using critical hits, so we don't bother with it this time.

> _Optional rule: Don't roll nine dice_. If you would ever roll 9+ dice, just assume that six of them resulted in `[1, 2, 3, 4, 5, 6]` and roll six fewer, until you're rolling a reasonable number of dice.

> _Optional rule: Critical 6s explode_. After the rerolls, any dice that show a `6` explode: note how many hits have happened so far, and then roll more dice for each 6. Those sixes explode, too.

> _Optional rule: All at once_. If you're good at math and hate fun, you can do the rerolls by canceling `d` & `q` leaving some number of `d`, canceling `b` & `p` leaving some number of `r`erolls, rolling `d+r` dice, and letting the appropriate player pick which `d` dice to keep. But it's more fun to narrate it all.

## Extreme DCs

Roll DCs 1 or lower and 6 or higher as these values instead:

| Original defender's DC | New DC |
|------------------------|--------|
| -1 | 2&3q |
| 0 | 2&2q |
| 1 | 2&1q |
| 2-5 | 2-5 |
| 6 | 5&1b |
| 7 | 5&2b |
| 8 | 5&3b |

# Bestiary

TODO

# Treasure

TODO

# Levels & Tiers


# XP & Level & Tier
You have 0 e**X**perience **P**oints.
This makes you a level 1, _novice_ tier character.

You gain the next level every `level * 1000 XP`.
You get XP for retrieving treasure (1XP per sp of treasure recovered), defeating monsters (10XP per level of foe), and for achieving goals (variable).
You gain a new tier at certain character levels; when y

| Tier | Title | At Level |
|------|-------|----------|
| 1 | Novice | 1 |
| 2 | Apprentice | 2 |
| 3 | Journeyman | 4 |
| 4 | Master | 7 |
| 5 | Grandmaster | 11 |
| 6 | Demigod | 16 |

At each new tier (including at level one), select one of the following benefits:
* Warrior: 

## Titles

A good title is an exploit ("slayer of goblins"), a background or skill ("apothecary"), a trick or knack ("master of the seven palms"), or a boast ("silent-stepping").

Sometimes, it deepens a connection to a particular literal-title ("swordmaster of Navarre"), person ("Lover of Brienne"), place ("cimmerian"), thing ("captain of the sparhawk"), or office ("paladin of justice").

A wizard or kung fu master might name their new techniques, implicitly claiming mastery over them: "fire mage", but also "seven serpent touch" or "ooze hammer".
A gun-nut might name their very favorite thing ("I call her Vera").




| Total XP | Level | Tier |
|----------|-------|------|
|      0   | 1     | Novice (1) |
|   1000   | 2     | Apprentice (2) |
|   3000   | 3     | Apprentice (2) |
|   6000   | 4     | Journeyman (3) |
|  10000   | 5     | Journeyman (3) |
|  15000   | 6     | Journeyman (3) |
|  21000   | 7     | Master (4) |
|  28000   | 8     | Master (4) |
|  36000   | 9     | Master (4) |
|  45000   | 10    | Master (4) |
|  55000   | 11    | Grandmaster (5) |
|  66000   | 12    | Grandmaster (5) |
|  78000   | 13    | Grandmaster (5) |
|  91000   | 14    | Grandmaster (5) |
| 105000   | 15    | Grandmaster (5) |
| 120000   | 16    | Demigod (6) |
| 136000   | 17    | Demigod (6) |
| 153000   | 18    | Demigod (6) |
| 171000   | 19    | Demigod (6) |
| 190000   | 20    | Demigod (6) |
| 210000   | 21    | Demigod (6) |
