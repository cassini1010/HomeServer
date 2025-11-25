# HomeServer

This is a home media server hosted on an old rusty laptop with ubuntu server OS on it. 😅

## docker-compose.yml

This file consist of fully functional, traefik proxy enabled pihole DNS. Run `docker compose up -d` to run the container in a detached mode. Once the docker container starts four applications can be accessed at below URLs

- http://pihole.home

- http://dashboard.home

- http://whoami.home

- http://jellyfin.home

## docker-compose-pihole.yml

This file consist of only the pihole container without the traefik proxy. To access the pihole dashboard go to `http://localhost/admin` as the site is hosted locally on port 80.
