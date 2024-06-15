# Symfony Docker based

Started with [dunglas/symfony-docker](https://github.com/dunglas/symfony-docker), many thanks to them!

A [Docker](https://www.docker.com/)-based installer and runtime for the [Symfony](https://symfony.com) web framework,
with [FrankenPHP](https://frankenphp.dev) and [Caddy](https://caddyserver.com/) inside!

![CI](https://github.com/dunglas/symfony-docker/workflows/CI/badge.svg)

## Getting Started

1. If not already done, [install Docker Compose](https://docs.docker.com/compose/install/) (v2.10+)
2. Run `docker compose build --no-cache` to build fresh images
3. Run `docker compose up --pull always -d --wait` to set up and start a fresh Symfony project
4. Open `https://localhost` in your favorite web browser and [accept the auto-generated TLS certificate](https://stackoverflow.com/a/15076602/1352334)
5. Run `docker compose down --remove-orphans` to stop the Docker containers.

## Docs

1. [Options available](docs/main.md)

## License

Symfony Docker is available under the MIT License, so is this repo!

## Credits

[dunglas/symfony-docker](https://github.com/dunglas/symfony-docker) Created by [Kévin Dunglas](https://dunglas.dev), co-maintained by [Maxime Helias](https://twitter.com/maxhelias) and sponsored by [Les-Tilleuls.coop](https://les-tilleuls.coop).

Original idea for this repo: [Daniel Rubio Fernández](https://github.com/Dani2033)
Collaborator for this repo: [Oriol Cobo Vadillo](https://github.com/Sukek)