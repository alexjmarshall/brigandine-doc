# Combat

## Hit Dice

Combatants have a pool of d6s called Hit Dice (HD). These dice serve as both your health track and your resource for attacking and defending. During combat, your dice circulate through four pools:

- **Reserve**: Ready and available to use.
- **Exchange**: Dice committed to your current attack or defense.
- **Spent**: Used this round. These refresh at the start of your next turn.
- **Lost**: Removed by damage. These require healing to recover.

## Initiative and the First Turn

Both sides roll **1d6** for initiative (reroll ties).

- **The Winner**: Takes the first turn with their full **reserve** available.
- **The Loser**: Starts on the defensive. The have only half their **reserve** (round up) available until their first turn.

## The Turn Structure

On your turn as the **Attacker**:

1. **Refresh**: Move all **spent** dice back to your **reserve**.
2. **Exchanges**: Conduct one or more exchanges of blows. You may keep attacking as long as you have dice in your **reserve**.
3. **End**: When you decide to stop or run out of dice, your opponent takes their turn and becomes the new attacker.

---

## The Anatomy of an Exchange

Every exchange follows this sequence:

1. **Attack Commitment**: The Attacker decides how many dice to commit, representing their aggression and measure.
2. **Defense Declaration**: The Defender sees the Attacker’s dice and declares their **maneuver** and how many dice they commit.
3. **Attacker’s Maneuver:** Seeing the defense, the Attacker chooses their **maneuver**.
4. **Resolution**: Roll dice (5+ is a success), compare results, and apply damage.
5. **The Aftermath**: All dice in the **exchange** move to the **spent** pool.

---

## Maneuvers

Any die rolling a 5 or 6 counts as a **success**.

### Attacker Maneuvers

- **Simple Attack**: Roll your **exchange** dice to deal damage.
- **Feint**: Your initial commit was a decoy (hopefully provoking a **parry**). Move those dice to **spent**. Launch a follow-up attack from **reserve**. Your max commitment for this follow-up attack is the number of dice the defender committed.
- **Dodge**: Your initial commit was evasive footwork. Move those dice to **spent**. Roll a new set of dice from **reserve**. On **2+ successes**, you take no damage. Otherwise, the enemy’s damage lands unopposed.

### Defender Maneuvers

- **Parry**: Roll your **exchange** dice. Each success cancels one attacker success.
- **Counter**: Launch an attack into the attacker. Their damage lands first, and hits your **exchange** dice first. Roll any you have left for damage against them.
- **Dodge**: Same as the Attacker version.

---

## Maneuver Matchups

**Damage** = Successes + Weapon Bonus − Armor (minimum 0). You must have at least 1 success to deal damage.

| Matchup                   | Result                                                                                                                                                                     |
| :------------------------ | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Attack vs. Parry**      | Attacker must roll more successes than the Defender to deal damage.                                                                                                        |
| **Attack vs. Counter**    | Damage destroys Defender’s **exchange** dice first. Excess damage spills into **reserve**, then **spent**. The Defender strikes back with any surviving **exchange** dice. |
| **Attack vs. Dodge**      | Attacker rolls. Dodger rolls Reserve dice. **2+ successes** = No damage. **0-1 successes** = Full damage.                                                                  |
| **Feint vs. Parry**       | Both initial pools are **spent**. Attacker makes a Follow-up (capped by Defender's committed dice). Any success deals damage.                                              |
| **Feint vs. Counter**     | Follow-up is intercepted. Counter rolls first against the Follow-up pool. Surviving Follow-up dice then hit Defender.                                                      |
| **Dodge vs. Counter**     | If Dodger gets 2+ successes, the Counter is wasted. Otherwise, Counter deals full damage.                                                                                  |
| **Dodge vs. Dodge/Parry** | A stalemate. No damage; all **exchange** dice become **spent**.                                                                                                            |

---

## Taking Damage

When you take damage, move dice to the **lost** pool in this order:

1. **Exchange** (Dice currently in the exchange).
2. **Reserve** (Dice you have left to use).
3. **Spent** (Dice already used this round).

> **Defeat:** Once your total Hit Dice hits zero, you are defeated.
