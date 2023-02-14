A fork of Knave (, er, and Maze Rats) for Vance-like and other ungentlemanly wizards.

> My goals are to write some automation to make it more reasonable to run at the table, as well as to support _very slightly_ more character customization than raw Knave. This should maintain compatibility with old school content. It aims to retain the classless nature of the original. 

# Licensing

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>

I owe a deep debt to [Ben Milton](https://questingbeast.itch.io/)'s [Maze Rats](https://questingbeast.itch.io/maze-rats) & [Knave](https://questingbeast.itch.io/knave); I am taking advantage of the _Creative Commons Attribution 4.0 International License_ under which both are released: Ben Milton did this all first and did it better.

In return, I release this content under the same license, referring to this product as `lackhand's Charlatan`.

# Testbed for autoroll tables

| 1d20 | Some results |
|------|--------------|
| 1-5  | Cry |
| 6-10 | Moan |
| 11-15 | Giggle |
| 16-20 | Retch |

# The Game

## Character Generation

### Abilities

Player characters have 4 **Abilities**:

* **FORTitude**: Strength, power, toughness. Number of Item slots.
* **REFLex**: Senses, stealth, agility, speed, perception, & intuition.
* **WILL**: Force of personality, discipline, & spirit. Number of Feel slots.
* **INTelligence**: Concentration, recollection, skill, training. Number of Think slots.

Roll 3 six sided dice (called "3d") and keep the lowest for your Fort Bonus (so `3`, `5`, `2` is a Fort Bonus of 2). Repeat for the other abilities in order.
After you've finished rolling, you may optionally swap two Ability Bonuses with each other.

Each Ability's Defense is (always) its Bonus + 10 (so in the example, a Fort Defense of 12); record that now and keep it up to date.

### Equipment

> As in the original, if you choose to shop instead of randomly generate, start with 3d6x20 coins. Also, elevated from the original into a built in rule, you choose armor _or_ magic.

The maximum item slots a character can carry equals their Fortitude Defense. Some items might bundle (like arrows into a quiver, or 100 coins) or take up more than one slot (heavy chainmail armor, or a two-slotted two-handed weapon). A character with as many item slots filled as their fortitude defense is **encumbered**.

Characters start with 2 **rations** and 1 **weapon** or **tool** of their choice.

The player can choose: Begin with 1 random _arcana_ or else a chance of _armor_ and _accessories_.


| 1d20 | Armor |
|------|-------|
| 1-3  | None |
| 4-14 | Gambeson (1) |
| 15-19 | Brigandine (2) |
| 20 | Chain (3) |

| 1d20 | Accessories |
|------|-------------|
| 1-13 | None |
| 14-16 | Helmet (1) |
| 17-19 | Shield (1) |
| 20 | Helmet (1) & Shield (1) |

Armor works like an ability, with a bonus equal to the number of item slots of worn armor & accessories (so with none it would be +0/10; with chain, helmet & shield +5/15).

Then roll for 2 pieces of _dungeoneering gear_ and 1 piece of _general gear I_ and 1 piece of _general gear II_:

| 1d20 | Dungeoneering Gear | General Gear I | General Gear II |
|------|--------------------|----------------|-----------------|
| 1 | Rope, 50ft | Air Bladder | Incense |
| 2 | Pulleys | Bear trap | Sponge |
| 3 | Candles, 5 | Shovel | Musical Instrument |
| 4 | Chain, 10ft | Bellows | Perfume |
| 5 | Chalk, 10 | Greasepot | Horn |
| 6 | Crowbar | Saw | Bottle |
| 7 | Tinderbox | Bucket | Soap |
| 8 | Grappling hook | Caltrops | Spyglass |
| 9 | Hammer | Chisel | Tarpot |
| 10 | Waterskin | Drill | Twine |
| 11 | Lantern | Fishing rod | Fake jewels |
| 12 | Lamp oil | Marbles | Blank book |
| 13 | Padlock | Glue | Card deck |
| 14 | Manacles | Pick | Dice set |
| 15 | Mirror | Hourglass | Cookpots |
| 16 | Pole, 10ft | Net | Face paint |
| 17 | Sack | Tongs | Whistle |
| 18 | Tent | Lockpicks | Lens | 
| 19 | Spikes, 5 | Metal File | Quill & ink |
| 20 | Torches, 5 | Nails | Handbell |

### Additional Scores

At the end of each period of rest, reset your **current** and **maximum** **Hit Points** to a roll 1d6 per point of Fort Bonus + 1d6 per level, keeping a number of dice equal to your level.

Your **healing rate** is 1d6+Fort Bonus.

Your **exploration speed** is 120' per exploration turn, and **combat speed** is 40' per round.

Invent or roll the rest of your character's traits such as their physique, skin, hair, clothing, virtue, vice, speech, background, and alignment using the tables that follow.

> TODO. The background _is_ included; where else would the nonweapon proficiencies come from?
> You can choose to place your background or other lore(s) into a Think slot; if you do, when it's relevant you roll with advantage.
> "Lores" are just backgrounds that start with "an expert in XXX" -- elf lore, etc!

| 1d20 | Background I | Background II | Lores |
|------|--------------|---------------|-------|
| 1 | Alchemist | Farmer | Plant & Animal |
| 2 | Beggar | Drover | Necromantic |
| 3 | Butcher | Nomad | Goblin |
| 4 | Burglar | Barber | Anatomy & Medicine |
| 5 | Charlatan | Carpenter | Troll, orc, giant etc |
| 6 | Cleric | Tinker | Dragon & ancient history |
| 7 | Cook | Blacksmith | Dwarves & geology |
| 8 | Cultist | Weaver | Fey & elves |
| 9 | Gambler | Fisher | History & Nobility |
| 10 | Herbalist | Dancer | Diabolical |
| 11 | Magician | Brewer | Celestial |
| 12 | Mariner | Poet | Aberrations & oozes |
| 13 | Mercenary | Knight | Constructs & Elementals |
| 14 | Merchant | Noble | Architecture & engineering |
| 15 | Outlaw | Miner | x |
| 16 | Perfomer | Scout | x |
| 17 | Pickpocket | Guard | x |
| 18 | Smuggler | Armorer | x |
| 19 | Student | Courtier | x |
| 20 | Tracker | Spy | x |



<details>

  <summary>Infrastructure (README hides!)</summary>
  
  <script
    type="text/javascript">
    (function() {
      function rnd(min=1, max=20) {
        return Math.floor(Math.random() * (max - min + 1)) + min;
      }
      const knownDice = {
        'd6': () => rnd(1, 6),
        'd20': () => rnd(1, 20),
        '1d20': () => rnd(1, 20),
        '1d6': () => rnd(1, 6),
      };
      function parseDice(expr) {
        return knownDice[expr.trim()];
      }
      function parseEntry(entry) {
        entry = entry.trim();
        let hyphenI = entry.indexOf('-');
        if (hyphenI < 0) {
          let value = parseInt(entry);
          if (isNaN(value)) return null;
          return [value, value];
        }
        let left = entry.substr(0, hyphenI).trim();
        left = parseInt(left);
        let right = entry.substr(hyphenI+1).trim();
        right = parseInt(right);
        return [left,right];
      }

      function makeRoller(table, index=1, oddsCol=0) {
        const headings = table.getElementsByTagName("th");
        const dice = parseDice(headings[oddsCol].innerHTML);
        if (!dice) return null;

        let data = [];
        for (let row of table.getElementsByTagName("tr")) {
          let cols = row.getElementsByTagName("td");
          if (cols.length <= 0) continue;
          let minmax = parseEntry(cols[oddsCol].innerHTML)
          if (!minmax) continue;
          data.push([minmax[0], minmax[1], cols[index].innerHTML]);
        }
        return function() {
          let roll = dice();
          for (let [min, max, value] of data) {
            if (min <= roll && roll <= max) {
              return `${roll}: ${value}`;
            }
          }
          return `No match for ${value}`;
        };
      }
      function insertRollers(table) {
        const headings = table.getElementsByTagName("th");
        for (let i = 1; i < headings.length; ++i) {
          const roller = makeRoller(table, i);
          if (!roller) {
            console.log("Can't make roller for", table, i, "=", headings[i]);
            continue;
          }

          let title = headings[i].firstChild;
          if (title.nodeType != Node.TEXT_NODE) {
            console.log("Unsuitable title type", table, i, "=", title);
            continue;
          }
          title = title.data;

          headings[i].innerHTML = '';
          headings[i].name = title;
          headings[i].roller = roller;

          const rollbutton = document.createElement("button");
          rollbutton.innerHTML = title;
          rollbutton.onclick = function() {
            this.innerHTML = `${title}<br/>${roller()}`;
          };
          headings[i].append(rollbutton);
        }
      }
    
      (function onLoad() {
        const tables = document.getElementsByTagName("table")
        for (let table of tables) {
          insertRollers(table);
        }
      })();

    })()
  </script>

</details>
