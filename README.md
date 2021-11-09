# drone-gitea-traefik-docker-blogpost
Blogpost on Drone Server and Drone Runner for Gitea on Docker

## Blog Post

Published blogpost on this repo:
- https://containers.fan/posts/setup-drone-server-and-drone-runner-for-gitea-on-docker/

## About

A note taken from [readme.drone.io](https://readme.drone.io/server/provider/gitea/)

> Please note we strongly recommend installing Drone on a dedicated instance. We do not recommend installing Drone and Gitea on the same machine due to network complications, and we definitely do not recommend installing Drone and Gitea on the same machine using docker-compose.

I have split up the components in gitea and drone, but for the ones just want to tinker around, a complete `docker-compose.yml` is in the root repository.
