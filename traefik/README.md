# Traefik
## Whats Traefik 
> Traefik is a dynamic reverse proxy and load balancer.
> It is commonly used in cloud-native environments.

## Running Traefik

Requires docker requires [Docker Engine](https://docker.com/) 19.03.0+ to run.

Create networks

```sh
docker network create traefik_public
docker network create traefik-socket_proxy
```

```sh
docker compose up 
```

