# Real Time Workshop

## Pre-installation requirements

To use this repo:

* git
* docker (17.05 or higher)
* docker-compose (or `docker compose` for newer versions)

For the workshop itself:

* Firefox or Chromium (any derivative)
* `tail` command
* IDE or similar (you'll be reading the main README a lot so markdown highlighting will help!)

## Pre-conference container creation

Best to handle this before you set off for the conference to avoid any internet issues that may slow down or
break your builds.

Run `docker-compose pull` to fetch pre-build container images

Run `docker-compose build` to get the containers downloaded and built - the build will contain 5 containers, quite similar to one another, and should take maybe 10 minutes.
