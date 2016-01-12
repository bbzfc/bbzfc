# Match types

[bbzfc specs](../bbzfc_specs.md) **>>** [Technical specifications](technical_specifications.md) **>>** [Game mechanics](game_mechanics.md) **>>** `Match types`

---

Match types introduce or change game objectives. There will be two basic categories which will subdivide the match
types:

1. Every man for himself.
2. Team play.


## Every man for himself

Under this category, the following match types will exist:

1. Free play.
2. Rabbit chase.
3. King of the hill.

Additionally, games under this category can be infinite, or time controlled. If a game is time controlled, after the
specified amount of time the game ends, and the player's level is updated.

## Team play

Under this category, the following match types will exist:

1. Free play.
2. Capture the flag.

Like with the **Every man for himself** category, games under this category can be infinite, or time controlled.
However, in timed games, after the game ends, and team's level and scoring information is updated. If it was a
**League** game, the level and the score is recorded in the database for the appropriate teams. If it's a normal match,
the players just get an information screen at the end. When they quit, or join a new **Game World**, the information
is lost.
