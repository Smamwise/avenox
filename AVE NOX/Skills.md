---
tags:
  - rules
---
# Skills 

## D6  and expertise

**Base chance of success:** All skills begin with a 1-in-6 chance of success.\
**Expertise points:** PCs gain expertise points to improve their chance of success with their skills. Each point allocated to a skill improves the chance of success by 1-in-6. Multiple points may be allocated to a skill, further increasing the chance of success.

For example, if 2 points are allocated to a skill, the chance of success is raised to 3-in-6 (from the base 1-in-6 chance of success).

**At 1st level:** At character creation, a thief has 4 expertise points to allocate. A barbarian has 4 expertise points to allocate.\
**Gaining levels:** A thief gains 2 additional expertise points to allocate. A barbarian has 1 additional expertise point to allocate every 3 levels. I.E. on levels 3, 6, 9, 12.\
**Maximum chance of success:** No skill may be raised above 5-in-6.

## Descriptions

### Referee rolls

Player rolls, referee checks if succceeds from a list of pre rolled dice numbers. For example, PC has HN 3-in-6. Player rolls a 5. Referee checks the first 3 numbers in list, marks them out and if the players 5 is in those 5 numbers the PC succeeds.

- **Hear noise (HN):** In a quiet environment (e.g. not in combat), a thief may attempt to listen at a door or to hear the sounds of something (e.g. a wandering monster) approaching.
- **Hide in shadows (HS):** Requires the thief to be motionless. Attacking or moving while hiding is not possible. 
- **Move silently (MS):** A thief may attempt to sneak past enemies unnoticed. 
- **Hide in undergrowth (HD):** Requires the barbarian to be motionless—attacking or moving while hiding is not possible.
- **Listen at door:** Detect subtle sounds beyond a door. One chance: This attempt may only be made one time at any door by a character.
- **Find room trap:** Adventurers may choose to search a 10’ × 10’ area for room traps. See #Searching. Chance of finding: If a character is searching in the right location, there is a 1-in-6 chance of finding a room trap.
- **Find treasure trap:** Characters with the ability to find treasure traps (as noted in their class description) may choose to search items (e.g. chests, locks) for traps.  See #Searching. Chance of finding: The chance of finding treasure traps, if a character is searching in the right location, is noted in the character’s class description.
- **Find secret door:** Some doors are hidden or concealed. Adventurers may choose to search a 10’ × 10’ area for secret doors. See #Searching. Chance of finding: If a character is searching in the right location, there is a 1-in-6 chance of finding a secret door.
- **Find or remove treasure traps (TR):** A roll is required to find a treasure trap and then another to remove it. This may be attempted only once per trap. 

### Player rolls

- **Climb sheer surfaces (CS):** A roll is required for each 100’ to be climbed. If the roll fails, the thief falls at the halfway point, suffering falling damage.
- **Open locks (OL):** Requires thieves’ tools (see Equipment, p94). A thief can only try this skill once per lock. If the roll fails, the thief may not try the same lock again before gaining an experience level. 
- **Pick pockets (PP):** If the victim is above 5th level, the thief ’s roll is penal- ised by 5% for every level above 5th. There is always at least a 1% chance of failure. A roll of more than twice the percentage required for success means that the attempted theft is noticed. The referee should determine the reaction of the victim (possibly using the reaction table under Encounters, p228).
- **Forage in the wild:** Foraging for herbs, fruits, nuts, etc. can be performed alongside normal movement (see Overland Travel). The party has a 1-in-6 chance per day of finding enough food for 1d6 human-sized beings.
- **Hunt in the wild:** Hunting must be engaged in as the sole activity for a day—no travelling or resting is possible. When hunting, there is a 1-in-6 chance of encountering animals which may be suitable for eating (if they can be caught!). This is in addition to the normal chance of random encounters (see Wandering Monsters).
- **Open stuck door (based on STR):** Force open a stuck door.
- **Lore:** Knowing lore pertaining to monsters, magic items, or heroes of folktale or legend. This ability may be used to identify the nature and powers of magic items.

### Searching

The following stipulations apply to searching for secret doors, room traps, and treasure traps.

**Time:** Searching takes one turn.
**Referee rolls:** The referee should always roll for the character searching, so that the player does not know if the roll failed or if there are simply no hidden features present.
**One chance:** Each character can only make one attempt to search a specific area or item.

## Matematiikka

Kaikille 1. tason ja max tason skilleille

$SkillPrcnt*6/100 = Skill D6$

Esim. 

CS lvl 1 87% = $87*6/100=5$

CS lvl max 99% = $99*6/100=5$

Summaa kaikkien skillien $SkillD6$ ja vähennä siitä skillien määrä. Näin saa aloitus expertise pointit.
Level up pointit saa laskemalla summatut d6 käännetyt skillit ja vähentämällä max lvl skilleistä 1 level skilleistä, tämä jaetaan max level-1.
Max skilli on 5.

Level 1 expertise points = $Lvl1ConvD6-SkillCnt = lvl1ExpPoints$

Level up expertise point gain = $\displaystyle \frac{LvlMaxConvD6-Lvl1ConvD6}{MaxLvl-1}=LvlupExpPoints$

### Thief

Skills 8
Max level 14

| Skill                              | Level 1 | Level Max | D6 Converted level 1 | D6 Converted level max |
| ---------------------------------- | ------- | --------- | -------------------- | ---------------------- |
| Climb sheer surfaces (CS)          | 87      | 99        | 87*6/100=5           | 99*6/100=5             |
| Find or remove treasure traps (TR) | 10      | 99        | 10*6/100=0.6         | 99*6/100=5             |
| Hear noise (HN)                    | 2       | 5         | 2 (d6 skill)         | 5 (d6 skill)           |
| Hide in shadows (HS)               | 10      | 99        | 10*6/100=0.6         | 99*6/100=5             |
| Move silently (MS)                 | 20      | 99        | 20*6/100=1.2         | 99*6/100=5             |
| Open locks (OL)                    | 15      | 99        | 15*6/100=0.9         | 99*6/100=5             |
| Pick pockets (PP)                  | 20      | 125       | 20*6/100=1.2         | 99*6/100=5             |
| Read Languages                     | 0       | 80        | 0*6/100=0            | 80*6/100=4.8           |
| **TOTAL**                          |         |           | **11.5**             | **39.8**               |

Lvl 1 d6 sum = 11.4
level14 d6 sum = 39.8

Aloitus expertise pointit $11.5-8=3.5=4$
Level up pointit = $\displaystyle \frac{39.8-11.5}{14-1}=2.17$ =2

### Barbarian

Skills 3
Max level 14

| skill     | level1 | level14 | lvl1 d6 | level14 d6 |
| --------- | ------ | ------- | ------- | ---------- |
| cs        | 87     | 99      | 5       | 5          |
| hd        | 10     | 60      | 0.6     | 3.6        |
| ms        | 20     | 50      | 1.2     | 3          |
| **TOTAL** |        |         | **6.8** | **11.6**   |

Lvl 1 d6 sum = 6.8
level14 d6 sum = 11.6

Aloitus expertise pointit $6.8-3=3.8=4$
Level up pointit = $\displaystyle \frac{11.6-6.8}{14-1}=0.369$ = 1 expertise point 3 levelin välein.

### Mage

Skills 5
Max lvl 14

| skill     | level1 | level14 | level1 d6 | level14 d6 |
| --------- | ------ | ------- | --------- | ---------- |
| dm        | 75     | 99      | 4.5       | 5          |
| oc        | 30     | 95      | 1.8       | 5          |
| rf        | 20     | 95      | 1.2       | 5          |
| rm        | 50     | 99      | 3         | 5          |
| su        | 20     | 95      | 1.2       | 5          |
| **TOTAL** |        |         | **11.7**  | **25**     |

lvl1 d6 sum 11.7
lvl14 d6 sum 25

Aloitus expertise pointit $11.7-5=6.7=7$
Level up pointit = $\displaystyle \frac{25-11.7}{14-1}=1.023$ = 1 expertise point / level up.