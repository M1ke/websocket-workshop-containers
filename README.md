# PHP Yorkshire 2019 - Real Time Workshop

## Pre-installation requirements

To use this repo:

* git
* docker
* docker-compose (for convenience you might alias this to `dc` in your shell)

For the workshop itself:

* Firefox or Chromium (any derivative)
* `tail` (seriously surprised if you're missing this)
* IDE or similar (you'll be reading the main README a lot so markdown highlighting will help!)

## Pre-conference container build

Run `docker-compose build` to get the containers downloaded and built - best to handle this
before you set off for the conference to avoid any internet issues that may slow down or
break your builds. The build will contain 5 containers, quite similar to one another, and should
take maybe 10 minutes.
