# Client authentication

[bbzfc specs](../bbzfc_specs.md) **>>** [Technical specifications](technical_specifications.md) **>>** [Clients (gamers)](clients_gamers.md) **>>** `Client authentication`

---

## E-mail based accounts

- The client will provide their e-mail, and password for authentication.
- The system will perform authentication via a SSL connection.
- If something is wrong, the client will have 5 tries to re-authenticate.
- After 5 failed authentication attempts, the system will not allow authentication attempts from the client's machine
for 60 minutes.
- After 15 failed consecutive authentication attempts for a specific e-mail address, that account will be locked down
permanently and an e-mail will be sent to the account's e-mail with instructions on how to unlock the account.

## 3rd party based accounts

- All authentication is handled by the 3rd party service.
