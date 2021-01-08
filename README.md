# Design Document
## Section 0 Introduction

Development name: DM Tools

Actual name: tbd

Proposed domain name: www.dm-tools.com

Purpose: A collection of easy to use content generation tools for Dungeon Masters.

Target: Dungeon Masters for Dungeons & Dragons 5th edition.

## Section 1 Random NPC Generator

Generator Map: https://www.gloomaps.com/hmVsVHW6jV

### Proccess

The generation proccess begins with a user selecting a type of of NPC to generate or selecting a random type.

**Standard:** 
- Generate a name (process for this tbd)
- Roll an occupation from this list http://dndspeak.com/2019/01/100-npc-jobs/
- Roll 1 or 2 distinguishing features from the NPC Appearance table (DMG pg.89)
- Roll 1 or 2 talents from the NPC Talents table (DMG pg.90)
- Roll 1 or 2 quirks from the NPC Mannerisms table (DMG pg.90)
- Determine personality using the NPC Interaction Traits table (DMG pg.90)
- Roll a high and low ability score on the NPC Abilities table (DMG pg. 89)
- Roll for useful knowledge the NPC might have
  - Create a d100 table
- Determine alignment
  - Roll a d20 (generate a random number)
  - Lawful Good is 1 and 2
  - Neutral Good is 3 through 5
  - Chaotic Good is 6 through 9
  - Lawful Neutral is 10 and 11
  - True Neutral is 12 and 14
  - Chaotic Neutral is 15 and 16
  - Lawful Evil is 17 and 18
  - Neutral Evil is 19
  - Chaotic Evil is 20
- Roll an ideal on the NPC Ideals table (DMG pg.90)
- Roll a bond on the NPC Bonds table (DMG pg.91)
- Roll a flaw on the NPC Flaws and Secrets table (DMG pg.91)
- Determine carried wealth
  - Roll a d100 (generate a random number)
  - The NPC will carry the rolled number in Silver Pieces
- Determine carries trinkets
  - Create a d100 table
  
**Merchant:**
- Generate a standard NPC
- Determine a price modifier
  - Between 75% and 150%
- Determine haggling rules
  - DC for successful haggling between 10 and 20
  - Price reduction for successful haggling
- Generate a store catalogue
  - 10 to 20 tools and trade goods
  - 10 to 20 pieces of mundane armor
  - 10 to 20 mundane weapons
  - 2 to 10 consumables
  - 2 to 10 common magic items
  - 1 to 8 uncommon magic items
  - 0 to 5 rare magic items
  - 0 to 3 very rare magic items
  - 0 to 1 legendary magic items
  - Apply standard and haggled price modifiers to list
  
**Adventurer:**
- Generate name (proccess tbd)
- Roll 1 or 2 distinguishing features from the NPC Appearance table (DMG pg.89)
- Roll 1 or 2 talents from the NPC Talents table (DMG pg.90)
- Roll 1 or 2 quirks from the NPC Mannerisms table (DMG pg.90)
- Determine personality using the NPC Interaction Traits table (DMG pg.90)
- Determine alignment
  - Roll a d20 (generate a random number)
  - Lawful Good is 1 and 2
  - Neutral Good is 3 through 5
  - Chaotic Good is 6 through 9
  - Lawful Neutral is 10 and 11
  - True Neutral is 12 and 14
  - Chaotic Neutral is 15 and 16
  - Lawful Evil is 17 and 18
  - Neutral Evil is 19
  - Chaotic Evil is 20
- Roll a background from Player's Handbook (https://www.dndbeyond.com/sources/phb/personality-and-background#Backgrounds)
  - If the background has an "archetype", such as the Charlatan's Favorite Scheme, roll for that
- Roll a personality trait from the background's Personality Trait table
- Roll an ideal from the background's Ideal table
  - Account for alignment
- Roll a bond from the background's Bond table
- Roll a flaw from the background's Flaw table
- Determine the adventurer's class
  - Limited by their background
- Choose class archetype and features
- Assign ability scores
  - Use a standard distribution
    - Use different distributions for different total levels
  - Assign ability scores based on class
- Determine carried wealth
  - Roll a d100 (generate a random number)
  - The adventurer will carry the rolled number in Gold Pieces
    - Multiply by level
- Generate inventory
  - Level 0 through 5
    - Use standard starting equipment
  - Level 6 through 10
    - Add 2 to 3 common magic items
    - Add 1 to 2 uncommon magic items
    - Add 0 to 1 rare magic items
  - Level 11 through 15
    - Add 2 to 3 uncommon magic items
    - Add 1 to 2 rare magic items
    - Add 0 to 1 very rare magic items
  - Level 16 through 20
    - Add 2 to 3 rare magic items
    - Add 1 to 2 very rare magic items
    - Add 0 to 1 legendary magic items

**Villain:**
- Generate an adventurer
  - Add villanous class options
- Roll for a scheme on the Villain's Scheme table (DMG pg.94)
- Roll for methods on Villain's Methods table (DMG pg.95)
- Roll for weakness on Villain's Weakness table (DMG pg.96)
