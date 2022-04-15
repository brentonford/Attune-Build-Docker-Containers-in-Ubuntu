# Deploy and Build Docker Containers for Raspberry Pi-hole

This blueprint builds Portainer, Watchtower, and Pi-hole using Docker Compose and requires that you've already got the [Docker Engine and Docker Compose](https://www.servertribe.com/attune-hub/install-docker-compose-linux/) deployed on your device.

This has been tested on Raspberry Pi 4 with Ubuntu Server 20.04.2 LTS 64-bit.

## Portainer Container

[Portainer](https://www.portainer.io/) is an open source tool for managing containerized 
applications.

## Watchtower Container

[Watchtower](https://containrrr.dev/watchtower/) is an application that will monitor your 
running Docker containers and watch for changes to the images that those containers were 
originally started from.

## Pi-hole Container

[Pi-hole](https://registry.hub.docker.com/r/pihole/pihole/) is a DNS sinkhole that protects 
your devices from unwanted content, without installing any client-side software.