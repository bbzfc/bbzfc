# Player level

[bbzfc specs](../bbzfc_specs.md) **>>** [Technical specifications](technical_specifications.md) **>>** [Game mechanics](game_mechanics.md) **>>** `Player level`

---

The player level for a client (gamer, player) will be specific to a **Main Server**. The player level will be an a
positive integer between 0 and Infinity. It will be calculated with the following formula:

    NumHours >= e^Level

where **NumHours** is the total number of hours the player played on the **Main Server** (any match type, and game
world, etc.), **e** is the [Euler's Number](https://en.wikipedia.org/wiki/E_%28mathematical_constant%29), and **Level**
is the player's level. Basically, as you spend more and more time playing **bbzfc**, the slower your level increases.

On a **Main Server** the following statistics for each player will be kept:

- Player level.
- Player kills/deaths ratio.
- Total number of games played (for each of the 5 types).
- Leagues the player played in.

The main logic behind the **Player Level** is that **Game Worlds** can be configured to allow play between similarly
skilled players. The main belief is that players that played a similar number of hours, are similarly skilled = )
