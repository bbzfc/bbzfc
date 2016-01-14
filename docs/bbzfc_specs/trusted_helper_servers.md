# Trusted helper servers

[bbzfc specs](../bbzfc_specs.md) **>>** [Technical specifications](technical_specifications.md) **>>** [Servers](servers.md) **>>** `Trusted helper servers`

---

For the **Tank Battle Portal** to deliver a true
[MMOG](https://en.wikipedia.org/wiki/Massively_multiplayer_online_game) experience, the **Main Server** must delegate
almost all of it's work to dedicated **Trusted helper servers**. By **Trusted** it is meant that they are
controlled by the same administrator, and that they are running uncompromised pristine code base of the **bbzfc**
project. The greater the number of players using the portal, the more trusted servers will be required to allow
for lag-free online gameplay.

The following are some of the possible tasks that trusted servers will be able to do:

- various databases management and access can be split between multiple trusted servers
- individuals **Game Worlds** with matches can be split between multiple trusted servers
- it will be possible to host a large **Game world** with thousands of players between multiple trusted servers.
this can be realistically achieved with real-time flow of NPC objects and players between the different servers.
- chat subsystems
- online services (forum, league, etc.)
- user management
