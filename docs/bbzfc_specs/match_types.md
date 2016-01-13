# Match types

[bbzfc specs](../bbzfc_specs.md) **>>** [Technical specifications](technical_specifications.md) **>>** [Game mechanics](game_mechanics.md) **>>** `Match types`

---

Match types introduce or change game objectives. There will be two basic categories which will subdivide the match
types:

1. Every man for himself.
2. Team play.


## Every man for himself

Under this category, the following match types will exist:

1. **Free play**. Destroy as many enemy tanks as possible, and don't get destroyed yourself.
2. **Rabbit chase**. Get the **Super Flag**, and hold it as long as possible. When you get destroyed, you automatically
loose the **Super Flag**.
3. **King of the hill**. Get inside a specially marked area in a **Game World**, and prevent enemy tanks from entering
this area.

Additionally, games under this category can be infinite, or time controlled. If a game is time controlled, after the
specified amount of time the game ends, and the player's level is updated.

## Team play

Under this category, the following match types will exist:

1. **Free play**. Destroy as many tanks from opposing teams as possible, and don't get destroyed yourself.
2. **Capture the flag**. Get the other team **Team Flag**, and bring it to your base. If you manage to bring it to your
base, all tanks from the opposing team are destroyed.

Like with the **Every man for himself** category, games under this category can be infinite, or time controlled.
However, in timed games, after the game ends, and team's level and scoring information is updated. If it was a
**League** game, the level and the score is recorded in the database for the appropriate teams. If it's a normal match,
the players just get an information screen at the end. When they quit, or join a new **Game World**, the information
is lost.
