[![Ask DeepWiki](https://deepwiki.com/badge.svg)](https://deepwiki.com/cima-alfa/docker-web-development)

# Docker Web Dev Preset

## Commands

- `docker compose up -d [--build]` (Start up containers - build as needed)
- `docker compose stop` (Stop all containers)
- `docker compose down` (Remove all containers)
- `docker exec -it <container> sh` (Access container shell)

## Containers

- `web-server` (Apache 2 Alpine)
- `application` (PHP 8.4 FPM Alpine)
- `database` (MySQL 8.4)
- `adminer` (Adminer)
