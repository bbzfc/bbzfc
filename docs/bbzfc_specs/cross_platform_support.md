# Cross platform support

[bbzfc specs](../bbzfc_specs.md) **>>** [Technical specifications](technical_specifications.md) **>>** `Cross platform support`

---

There will be three parts to the **bbzfc** project:

1. The client. Using it you can play a game, and you can observe a game.
2. The observer. You can only observe a game.
3. The server infrastructure.

**The client** will target Linux, Windows, and Mac OSX. The game will require some sort of game controller (keyboard and
mouse, or a gamepad). I.e. initially **bbzfc** will be playable only on a PC-based system (the desktop computer, laptop,
embedded devices such as Raspberry PI, etc.).

**The observer** will utilize the latest web technologies to make it available on the largest number of platforms
currently in use. Basically, anything that has a web browser and an Internet connection will be able to connect to a
game server and view a game match.

**The server infrastructure** will solely target Linux. The one system choice for this task is to make the development
easier, and shorten the development time. Linux is available as an option of a virtual system's OS on nearly all current
cloud hosting solutions.

In the future, when **bbzfc** matures, gaming platforms such as Sony's PlayStation or Microsoft's XBOX might be
considered as a way to expand the game's user base.

Also, an API will be exposed for developers who want to develop a native mobile game client with full functionality
support (i.e. gameplay, and observer mode).
