# dice & danger

A simple hack of old school dungeon crawling games based off of competent heroes and terrifying danger.

# This is a d6-based old skool RPG

* There is a DM and the rest of you are Players with Player Characters
* Player Characters have a slot-based inventory and things like:
* several Titles (text describing true things about yourself and the world)
* Attributes (which represent your resistance to various forms of peril)
* a Level (a measure of experience and power)
* a yen for treasure and for danger

Have fun!

# Dice always represent Danger

An individual die that rolls a high value *hits*; sometimes we say dice that show a low value miss (but technically they just don't count at all).

Players roll _damage_ to discover how well their attack against someone else goes. Each hit deals damage (yay).
Players roll _saves_ to discover how well they avoid someone else's attack. Each hit deals damage (boo).
Players roll all of the dice (except for like the DM rolling on tables I guess).
If one player tries to damage another, let the one who's _saving_ roll (it's just polite).

This doesn't have to be literal;
sometimes a _damage roll_ counts progress on a long term project. 
Sometimes a _save roll_ is "against being spotted by a guard".
It's all the same mechanic: hits from a roll represent change in status quo.

### Dice Notation

(This example is intentionally gnarly.)

> Player: My knight attacks the goblin from ambush with my goblinbane greatsword and favored enmity despite my fatigue and blindness.  
> DM: Ah, but did you consider that the goblin was itself a sneaky ninja who had drunk a potion of stoneskin?
> DM: Please roll your damage!  
> Player: Ok, I roll:  
>     3d +2d +1b +3b +2p +2p vs DC 3 & -1d & +2b  
> That is:  
> * `3d`: Roll a at 3 base **dice** (because I'm _acting_, and _prepared_, and _equipped_)
> * `+2d`: And then 2 more **dice** (because goblinbane greatsword, baybee) -- 5d! woo!
> * `+1b`: And then 1 more **bonus dice** because of Favored enmity; I roll one _more_ dice and discard one of my choice (the lowest)...
> * `+3b`: ... and because that goblin is _surprised_ I roll & discard 3 more bonus dice...
> * `+1p`: ... but stupid fatigue; roll 2 **penalty dice** but discard the _highest_...
> * `+2p`: ... and stupid blindess; total 4 _bonus_ and 3 _penalty_ dice; they cancel before the roll, so I'll just roll at +1b.
> * `vs DC 3`: The goblin's wearing hide armor or something, right? (DM: Yeah!) So any dice that shows a 3, 4, 5 or 6 is a hit. (DM: Yeah!)
> * `& -1d`: Ugh. This discards a base **dice** from my pool?! (DM: Yeah :-3)
> * `& +2b`: Wait, do I get these dice? (DM: No, the goblin is a ninja; they're _its_ bonus dice. They're _penalty dice for your roll_.) Ugh. Ok. So total, I'm rolling total at +1p now from my earlier +1b.
> Anyway, that's all crazy, but that simplifies out to
>    4d-1p vs DC 3
> That was really long! But I guess I had to show my work. Anyway, I rolled...
>    [1, 2, 4, 5, 6]
> but since one of those was the penalty die, I throw out the highest die (`6`).
> That leaves me with the `[4, 5]` as hits -- two hits!
> DM: wow I didn't expect that ;_; . Well, the stoneskin ninja goblin explodes into a red mist.
> Player: You should have expected exactly that! I had 33% odds!
>
> DM: By the way, it didn't come up because you discarded the 6, but if you _keep_ a 6 in your results it explodes.
> Roll more dice at +1d.
> That keeps happening as long as you roll a 6.
> That's called a crit.

### What's the DC? How many dice?

It's always a value from 2 to 6.
If it would be lower, give +1d; higher, give -1d.

When you're rolling a save, it's one of your attributes, and they'll supply the base dice to roll.
When you're rolling damage, it's your _target's_ attributes; you get:
* 1d for acting
* +1d if you're an expert (you have a relevant title)
* +1d if you're prepared (you have the relevant equipment)
* +1d if a friend helps and spends a HD
* +1p if you spend a HD

But you'll doubtlessly modify the dice pool with more dice, bonus and penalty dice, extra or removed hits, and so on.

# The Attributes

The DC for a roll is someone's attribute.
Different kinds of damage use different attributes, or different kinds of tactics to avoid them might suggest different attributes.
Just be consistent, and try to make them all at least a little fun!
* Strength. Use force to overcome an obstacle. Bursting bonds. Lifting a great weight. Running, climbing, jumping, swimming. Resisting paralysis, grappling, or being crushed. Blocking a melee attack.
* Reflex. Use instinct or agility to overcome an obstacle. Resist surprise, a missile weapon, a fireball, or a pit trap. Avoid detection or apprehension. Walk a tightrope.
* Health. Resist illness, disease, or death. Resist heat, or cold. Endure.
* Intelligence. Use training & concentration to overcome an obstacle. Doing it right the first time. Making the shot. Perfect even stitches. Picking the lock. Juggling. Being a quick study. Know the answer.
* Will. Use force of personality to overcome an obstacle. Resist despair, fear, or temptation. Tame a mule, lead an army.

Generate these attributes with the value on 1d+2p.

Some special attributes:
* Luck. Defends against bad odds, bad reaction rolls, etc. Sum the attributes above and compare:
  * 0-1: Luck 4-1h
  * 2-3: Luck 6
  * 4-6: Luck 5
  * 7-10: Luck 4
  * 11-15: Luck 3
  * 16-21: Luck 2
  * 22-28: Luck 3+1h
  * 29-36: Luck 2+1h
* Armor. Defends against weapons; based on armor (but not shield!). Starts at 2.
* Faith. Defends against spells; based on alignment and deeds. Starts at 2.

# Level

A starting adventurer is level 1.
There was a level 0 before that.
There will be many other levels afterwards.
The levels are grouped into Tiers, too:
* Tier 1 (level 0-1): Novice. 
* Tier 2 (level 2-3): Apprentice
* Tier 3 (level 4-6): Journeyman
* Tier 4 (level 7-10): Master
* Tier 5 (level 11-15): Grand Master
* Tier 6 (level 16-21): World Champion
* Etc.

Each level gives the player a new title: a bit of descriptive text describing themselves & their exploits.

Each level up to 6 gives +1 Hit Defense.
Each level 7-36 gives +1 Hit Defense every 6 levels (7, 13, etc).
Theoretically I guess each 36 levels thereafter would give +1 Hit Defense. And so on.

Each time they attain a new tier, the player chooses one more of their titles; when it applies it gives +1d more than it used to.

## Titles

A good title is an exploit ("slayer of goblins"), a background or skill ("apothecary"), a trick or knack ("master of the seven palms"), or a boast ("silent-stepping").

Sometimes, it deepens a connection to a particular literal-title ("swordmaster of Navarre"), person ("Lover of Brienne"), place ("cimmerian"), thing ("captain of the sparhawk"), or office ("paladin of justice").

A wizard or kung fu master might name their new techniques, implicitly claiming mastery over them: "fire mage", but also "seven serpent touch" or "ooze hammer".
A gun-nut might name their very favorite thing ("I call her Vera").

# Inventory

A human-sized character can wear or have within reach 6 items + 1 item per point of health.
Small worn items like rings or normal clothes don't count against this limit.

Everything else they carry is stowed in bags and boxes but its weight quickly accrues to attempts to sneak, swim, or tightrope-walk:
* 0-1 items: +0p from weight
* 2-3 items: +1p from weight
* 4-6 items: +2p from weight
* 7-10 items: +3p from weight
* 11-15 items: +4p from weight
* and so on

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

# Bestiary

TODO

# Treasure

TODO
