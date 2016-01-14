# System load and scalability

[bbzfc specs](../bbzfc_specs.md) **>>** [Technical specifications](technical_specifications.md) **>>** [Servers](servers.md) **>>** `System load and scalability`

---

The **bbzfc** project will implement a system that will try to achieve linear scalability. Form a mathematical point of
view, you can think of the following function:

    MAX_PLAYERS = c * NUM_SERVERS

where **MAX_PLAYERS** is the maximum number of players supported by a system, **c** is a numerical constant which
is a characteristic of the system, and  **NUM_SERVERS** is the number of servers working in the system.

Obviously, the goal is to achieve a linearly scalable system. How it will turn out in practice - remains to be seen = )
