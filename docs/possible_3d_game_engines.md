# List of possible 3D game engines

This document will list possible game engines to use for the client part of **bbzfc** project.


## Engine criteria

- Because the end-user of **bbzfc** can setup a **Tank Battle Portal** and charge money for it's use, we need to select
a game engine with an appropriate license. Although some engines do have an open source license, they charge you money
if the product you make with the engine starts earning you money. An example of engine to avoid is
[Unity - Game Engine](https://unity3d.com/). Therefore, to be on the safe side, only engines with a MIT license will be
considered. Also, engines with open source code base, but with the fine print reading "you owe us a % of gross revenue
resulting from any commercial products built using the engine", will not be considered.
- The engine should be written in either C or C++. The engine should have support for including it in a C/C++ project
(game).
- The engine should be cross-platform to some degree. At least Linux, and Windows support.
- The engine should use the modern programmable graphics pipeline.


## Possible engines

The list is ordered by engine's age. Newer engines go towards the bottom.

1. [OGRE - Open Source 3D Graphics Engine](http://www.ogre3d.org/)
2. [Torque 3D](http://torque3d.org/)
3. [Urho3D - Cross-platform 2D and 3D game engine](http://urho3d.github.io/)
