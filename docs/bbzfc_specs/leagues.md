# Leagues

[bbzfc specs](../bbzfc_specs.md) **>>** [Technical specifications](technical_specifications.md) **>>** [Clients (gamers)](clients_gamers.md) **>>** `Leagues`

---

[Leagues](https://en.wikipedia.org/wiki/Sports_league) is a concept that is common to many sports and many online games.
**bbzfc** project will have a built-in League system. The main idea is that a League will allow for reoccurring organized
game matches between a constant (or very close to this) set of registered players.


## The Main Server League online resource

This online service will be reachable by a standard web-browser. It will information about:

- currently operational leagues
- League specific information
- current matches
- statistics on league players
- history records of League matches
- archive of discontinued Leagues

Registered clients (registered with the League's Main Server) can login into this service and:

- Request to join a League.
- Leave a League.
- Create a new League.
- Manage game matches for a League (if they are the administrator of that League).
- Stop a functional League (if they are the administrator of that League).

A separate Forum for Leagues will not be provided. All League discussions should go to the general Forum of the
**Main Server**, or a separate Forum managed by the League administrator on their own,


## League matches

The **Main Server** will automatically instantiate planned League matches. It will manage them, and record
the outcomes to the database. All results will be automatically made available on the League online resource.

A League game match will automatically start if all conditions are met (for example, time of game match start, number of
players, specific player list, etc.).

It is the responsibility of specific players signed up for a League to turn up in time for a game match.

Also, the League administrator might set up specific rules to handle cases when certain League players do not
show up for game matches.
