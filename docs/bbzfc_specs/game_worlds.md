# Game worlds

[bbzfc specs](../bbzfc_specs.md) **>>** [Technical specifications](technical_specifications.md) **>>** [Game mechanics](game_mechanics.md) **>>** `Game worlds`

---

A **Game World** encapsulates the following properties:

- A world map:
  - Configuration of playing field. Infinite or finite.
  - Flag sets.
  - Layout of objects, structures, flags, etc.
  - Terrain.
  - Atmosphere and weather conditions.
  - Time zone (night or day, specific time of day).
- Private or public. If private, there exists a specific set of users that can access the **Game World**.
- Maximum number of players.
- Minimum number of players.
- Teams:
  - Number of different teams.
  - Team names.
  - Team colors.
  - Number of players per team.
- Match type.
- Time control.
- Difficulty level. Maximum and/or minimum **Player Level** of players that can join the game.
- League specific configuration.

A **Game World** is accessible on a **Main Server** (server infrastructure to be discussed in a separate document). If
a desirable **Game World** does not exist, a player can setup a new one with desired configuration. The custom game
world will be accessible through the **Main Server** it was created on.

A **Game World** can use the pre-made maps or custom player created ones.
