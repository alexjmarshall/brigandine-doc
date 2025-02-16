# Basics

**Rounding:** Always round down. _Exception:_ Damage and hit points have a minimum of 1.

**Units of Measurement:** Distances are in feet (ft) or yards (yd). Weight is in pounds (lb).

## Ability Modifiers

**Standard Modifier :** Add to skill checks and saving throws. Unless stated otherwise, "ability mod" refers to the standard modifier.

| Ability Score | Standard Mod |
| :-----------: | :----------: |
|       3       |      -3      |
|      4–5      |      -2      |
|      6–7      |      -1      |
|     8–13      |      0       |
|     14–15     |      +1      |
|     16–17     |      +2      |
|      18       |      +3      |

**Full Modifier:** Calculated as `ability score – 10`. Use this modifier instead for ability checks.

| Ability Score | Full Mod |
| :-----------: | :------: |
|       3       |    -7    |
|       4       |    -6    |
|       5       |    -5    |
|      ...      |   ...    |
|      16       |    +6    |
|      17       |    +7    |
|      18       |    +8    |

**Note:** Both sequences continue in each direction: 1 standard modifier per 2 ability points, and 1 full modifier for every ability point.

## Core Rolls

**Ability Check:** `d20 + full ability mod`

- Handles simple tasks that rely on raw ability.

**Skill Check:** `d20 + ability mod + skill bonus`

- Resolves tasks that benefit from training and experience.

**Saving Throw:** `d20 + ability mod + save bonus`

- Made in reaction to a trap, spell or special attack as a last chance to avoid harm.

A roll succeeds if it meets or exceeds the target number:

- Armor Class (AC) for attacks with weapon skills
- Difficulty Class (DC) for saving throws and other checks

## Determining Difficulty Class

**Save vs. Special Attack:** `12 + ½ the monster's Hit Dice (HD)`

- _Example:_ A Basilisk's petrifying gaze (HD 6) has a DC of `12 + 3 = 15`.

**Save vs. Spell:** `12 + spellcasting ability mod + spell level `

- _Example:_ A Mage with Intelligence 16 (+2) casts _confusion_ (level 4). The DC is `12 + 2 + 4 = 18`.

**Skill and Ability Checks:** Determine based on the task's difficulty, or use a typical value for the Dungeon Level. If unsure, use a DC of 15.

| Task Difficulty | Dungeon Level | DC  |
| --------------- | :-----------: | :-: |
| Very Easy       |       0       |  9  |
| Easy            |      1–3      | 12  |
| Medium          |      4–7      | 15  |
| Hard            |     8–12      | 18  |
| Very Hard       |      13+      | 21  |
