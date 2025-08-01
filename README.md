<a href="https://discord.gg/WhZmm46APN"><img alt="Discord" src="https://img.shields.io/discord/852538978946383893?style=for-the-badge&logo=discord&label=Discord&labelColor=%231940ED&color=%233FCB9B"></a>

# Traefik Docker

Dockerized Traefik instance configured for internal use within the XRAY infrastructure. Serves as a reverse proxy and routing layer for managing service traffic, TLS termination, and container-based service discovery across the XRAY platform.

## Getting Started

### Prepare Installation

``` console
git clone \
  https://github.com/xray-network/traefik-docker.git \
  && cd traefik-docker
```
  
### Docker Up

``` console
docker compose up -d
```
