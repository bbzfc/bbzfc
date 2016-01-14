# Cheat prevention

[bbzfc specs](../bbzfc_specs.md) **>>** [Technical specifications](technical_specifications.md) **>>** [Clients (gamers)](clients_gamers.md) **>>** `Cheat prevention`

---

Three approaches will be used to prevent users from cheating inside the game:

1. The server will be authoritative in that it will check player movements, and actions. So if the client is doing
something fishy, the server will be able to notice this, and take immediate action. All important client's game actions
 will be routed through the server, so others will not be affected by someone cheating.
2. As the age-old saying goes, for every defense there is an offense. So, ways to circumvent the cheating mechanism
might be found. A system will be implemented to check for known cheats based on heuristic analysis of the current game
state.
3. A neural network will be trained to analyze game play, and find suspicious player behavior.
