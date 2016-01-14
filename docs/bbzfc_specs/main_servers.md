# Main servers

[bbzfc specs](../bbzfc_specs.md) **>>** [Technical specifications](technical_specifications.md) **>>** [Servers](servers.md) **>>** `Main servers`

---

A **Main Server** is a central access point to a **Tank Battle Portal**. It has an easy to remember domain name
(for example [tank-battle.net](http://tank-battle.net). When a user starts up a game client, he specifies the
**Tank Battle Portal** he wants to join, by specifying it's domain name. If a portal doesn't have a domain name
associated with it, it can still be accessed by it's IP address.

Also, the **Main Server** is accessible via a standard web browser by it's domain name. So, by going to portals
web-site, you can access it's online web resources. The administrator might want to use the default home page with
links to the **Forum**, the **Leagues**, and **Registration**. Or a complex web application can be created to match
the administrator's needs. The main point is that much of the **Main Server** functionality will be accessible via a
RESTful API, and using it the administrator can create as complex a web application to interact with the portal as he
wants.

The **Main Server** is designed in such a way to be able to handle all necessary portal tasks:

- web services
  - registration site
  - forum site
  - leagues site
- user management
- game world management
- match management
- chat
- etc.

However, as the user count increases, there will be a point when a **Main Server** simply will not be able to handle
everything by itself. This is where the **Trusted Helper Servers** come in. If the administrator has access to multiple
servers (dedicated hardware, virtual machines, etc.), and they are connected to the Internet, he can configure the
**Main Server** to use these extra servers as **Trusted Helper Servers**.
