# Flags

[bbzfc specs](../bbzfc_specs.md) **>>** [Technical specifications](technical_specifications.md) **>>** [Game mechanics](game_mechanics.md) **>>** `Flags`

---

A flag is a stationary object in a **Game World**. It looks like a real-world flag = ) A tank can pick up a flag by
driving over it. Some flags can be dropped when the player decides is best, some flags can only be exchanged for other
flags, and some flags have a timer for their effect (after the timer ticks to zero, the flag is automatically dropped).
When a flag is dropped, it disappears and appears in a different location in the **Game World**.

The following flags will exist in the **bbzfc** game:

- **Wings Flag**. The tank can fly.
- **Thin Flag**. When facing the tank from the front (or the back), others will see it as a thin vertical line. Hard to
hit from the front (or the back).
- **Burrow Flag**. The tank goes under the ground, and you only see it's top. You can't kill a burrowed tank with a
bullet or a laser. You can kill a burrowed tank with a guided missile, or by driving on top of it.
- **Laser Flag**. The tanks shoots a straight infinite laser. Time between laser shots is much larger than between
normal bullets.
- **Guided Missile Flag**. The tank shoots a guided missile instead of normal bullets. How it works: first you lock on
to a visible target, then you release the missile. Time between missile shots is much larger than between normal
bullets.
- **Invisible Flag**. Tank is invisible out of the window. Tank is visible on the radar.
- **Stealth Flag**. Tank is invisible on the radar. Tank is visible out of the window.
- **Shockwave Flag**. Tank sends out a spherical shockwave. The shockwave kills all tanks in it's path. The radius of
the shockwaves effect is small (approximately four tank lengths).
- **Useless Flag**. Use it wisely = )

Additionally, the following flags will exist automatically based on specific **Match Types**:

- **Super Flag**. Used in **Rabbit chase**.
- **Team Flag**. Used in **Capture the flag**.

The original flag set will remain until the end of time. No new flags will be added to **bbzfc**. No flags will be
removed from **bbzfc**.

Different **Game Worlds** can be with different sets of available flags. From no flags, to all flag types. This will be
configurable.
