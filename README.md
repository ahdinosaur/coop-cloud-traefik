# Traefik

[![Build Status](https://drone.autonomic.zone/api/badges/coop-cloud/traefik/status.svg)](https://drone.autonomic.zone/coop-cloud/traefik)

> https://docs.traefik.io

<!-- metadata -->
* **Category**: Utilities
* **Status**: ?
* **Image**: [`traefik`](https://hub.docker.com/_/traefik), ❶💚, upstream
* **Healthcheck**: Yes
* **Backups**: No
* **Email**: N/A
* **Tests**: ❷💛
* **SSO**: ? (Keycloak)
<!-- endmetadata -->

## Basic usage

1. Set up Docker Swarm and [`abra`]
2. `abra app new traefik`
3. `abra app YOURAPPDOMAIN config` - be sure to change `DOMAIN` to something that resolves to
   your Docker swarm box
4. `abra app YOURAPPDOMAIN deploy`

[`abra`]: https://git.autonomic.zone/autonomic-cooperative/abra
