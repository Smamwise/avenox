---
tags:
  - rules
---
# Expertise and D6 skills

**Base chance of success:** All skills begin with a 1-in-6 chance of success.\
**Expertise points:** PCs gain expertise points to improve their chance of success with their skills. Each point allocated to a skill improves the chance of success by 1-in-6. Multiple points may be allocated to a skill, further increasing the chance of success.

For example, if 2 points are allocated to a skill, the chance of success is raised to 3-in-6 (from the base 1-in-6 chance of success).

**At 1st level:** At character creation, a thief has 4 expertise points to allocate. A barbarian has 4 expertise points to allocate.\
**Gaining levels:** A thief gains 2 additional expertise points to allocate. A barbarian has 1 additional expertise point to allocate every 3 levels. I.E. on levels 3, 6, 9, 12.\
**Maximum chance of success:** No skill may be raised above 5-in-6.

## Matematiikka

Kaikille 1. tason ja max tason skilleille

$SkillPrcnt*6/100 = Skill D6$

Esim. 

CS lvl 1 87% = $87*6/100=5$

CS lvl max 99% = $99*6/100=5$

Summaa kaikkien skillien $SkillD6$ ja vähennä siitä skillien määrä. Näin saa aloitus expertise pointit.
Level up pointit saa laskemalla summatut d6 käännetyt skillit ja vähentämällä max lvl skilleistä 1 level skilleistä, tämä jaetaan max level-1.
Max skilli on 5.

## Thief

Skillien lukumäärä = 8 \
Max level = 14

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

Lvl 1 d6 sum = 11.5 \
level14 d6 sum = 39.8

Aloitus expertise pointit $11.5-8=3.5=4$ \
Level up pointit = $\displaystyle \frac{39.8-11.5}{14-1}=2.17$ = 2 expertise point / level up.

## Barbarian

Skillien lukumäärä 3 \
Max level 14

| skill     | level1 | level14 | lvl1 d6 | level14 d6   |
| --------- | ------ | --- | ------- | -------- |
| cs        | 87     | 99  | 5       | 5        |
| hd        | 10     | 60  | 0.6     | 3.6      |
| ms        | 20     | 50  | 1.2     | 3        |
| **TOTAL** |        |     | **6.8** | **11.6** |

Lvl 1 d6 sum = 6.8 \
level14 d6 sum = 11.6

Aloitus expertise pointit $6.8-3=3.8=4$ \
Level up pointit = $\displaystyle \frac{11.6-6.8}{14-1}=0.369$ = 1 expertise point 3 levelin välein.

## Mage

Skillien lukumäärä 5 \
Max lvl 14

| skill     | level1 | level14 | level1 d6 | level14 d6 |
| --------- | ------ | ------- | --------- | ---------- |
| dm        | 75     | 99      | 4.5       | 5          |
| oc        | 30     | 95      | 1.8       | 5          |
| rf        | 20     | 95      | 1.2       | 5          |
| rm        | 50     | 99      | 3         | 5          |
| su        | 20     | 95      | 1.2       | 5          |
| **TOTAL** |        |         | **11.7**  | **25**     |

lvl1 d6 sum 11.7 \
lvl14 d6 sum 25

Aloitus expertise pointit $11.7-5=6.7=7$ \
Level up pointit = $\displaystyle \frac{25-11.7}{14-1}=1.023$ = 1 expertise point / level up.
