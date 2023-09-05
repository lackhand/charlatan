# dungeon d6

A simple hack of old school dungeon crawling games based off of competent heroes and terrifying danger.

Core mechanic: roll a pool of 6 sided dice and count the number of results that meet a minimum.
* `Die`/`Dice`: a cube with faces numbered 1-6. It would be nice to have 6 to play with, though 6/player would be even better.
* `Value`: the number of showing pips on a die. Higher is better.
* `Target`: A number between 2-6 (or rarely higher); a die with lower `value` than the `target` is discarded. This sets the _difficulty_ of the task.
* `Count`: The number of dice meeting or exceeding the target. This sets the _margin of success_.
* Rolling 0 dice: roll 2 dice and immediately discard the higher before evaluating count or crits.
* `Exploding` `Crits`: 6s always form a _crit_ and explode (adding additional dice to the pool which are rolled immediately, which can also explode on a 6). Once no further dice are rolled, the `value` of all dice showing a six is read as `5 + count`
	- Example: Alice rolls `[1, 3, 6, 6]`. We know this is a crit and we're at +2d; she rolls `[1, 6]` which is a further crit, on which she rolls `[3]`. We're done exploding; we know that there were 3 total dice showing a six, and so the total roll was `value` 8 & `count` 3.
* `Enormous Pools`: When you would roll >6 dice, discard 6 of them and assume you rolled [1,2,3,4,5,6] on them.
* `Negative Pools`: Every single dice in a pool of negative size automatically rolls a 1.

Core statistic: Tier, broken into Level, broken into Experience point. Level 1 is tier 0; each tier requires +as many levels as its number; each level requires +100 experience points per its number to leave (thus the total accrued) & gives the listed bonus.
* Tier -1
	* Level 0: n/a exp; Background
* Tier 0
	* Level 1: 0 xp; +1 slot
* Tier 1
	* Level 2: 100 xp; +1 save
	* Level 3: 300 xp; +1 slot
* Tier 2
	* Level 4: 600 xp; +1 feature
	* Level 5: 1k xp; +1 save
	* Level 6: 1.5k xp; +1 slot
* Tier 3
	* Level 7: 2.1k xp; +1 feature
	* Level 8: 2.8k xp; +1 save
	* Level 9: 3.6k xp; +1 feature
	* Level 10: 4.5k xp; +1 slot
* Tier 4
	* Level 11: 5.5k xp; +1 save
	* Level 12: 6.6k xp; +1 feature
	* Level 13: 7.8k xp; +1 save
	* Level 14: 9.1k xp; +1 feature
	* Level 15: 10.5k xp; +1 slot
etc.

Features: Features are descriptive text about your character, like a Background, a Title, a skill, a knack, etc. When a feature is relevant, your tier is considered 1 higher.

Slots: Your slots allow character skill differentiation:
* Attack: +1 attack per round
* Spell: Prepare +1 spell per day
* Skill: Pick another background, or increase mastery in one background (is this different enough from feature levels?)
* ???

Saves: Your saves are your character's numeric attributes. They're used as part of resistance.
* Melee: Act with violence; resist attacks.
* Strength: Act with force; lift or climb or swim; resist paralysis or petrification.
* Instinct: Act with speed and awareness; avoid detection, surprise, & missiles.
* Cunning: Act with caution and skill. Avoid mistakes.
* Health: vs poison, polymorph, fatigue or death.
* Will: Impose or resist ego & emotion; resist many spells.

Points:
* Hit: During each rest, your character rolls 1d per level and keeps a number equal to tier

Obstacles: Obstacles have a tier. A locked door, a sheer cliff, a toxin, a needle; an angry goblin, a rampaging chimera, a raging fire.

Core mechanic: Declare.
To do something, you say that your character does it. If its within your tier (+1 if you have a relevant title, +1 if you have a relevant equipment, +1 if you have a ), you succeed. If there's a question of how well, take 1 die per tier, discard 1 die per tier

Core mechanic: Resist. 
