# Traefik
Traefik service for local network.

## Configuration
See simple configuration in `/config` with Traefik v2.x Docs.

Users to access Traefik API/Dashboard are added using `htpasswd` to 
`./config/usersfile` -

```
htpasswd -B ./config/usersfile username
```
