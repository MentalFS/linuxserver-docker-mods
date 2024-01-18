# freshrss-comicsinfeed Docker mod

A [Linuxserver Docker mod](https://github.com/linuxserver/docker-mods/) that installs the [Comics in Feed](https://github.com/giventofly/freshrss-comicsinfeed) FreshRSS extension by [giventofly](https://github.com/giventofly).


## Usage

Add `ghcr.io/mentalfs/linuxserver-mods:freshrss-comicsinfeed` to your `DOCKER_MODS` environment variable, for example `DOCKER_MODS=ghcr.io/mentalfs/linuxserver-mods:freshrss-comicsinfeed`. You can add multiple mods by using `|` as delimiter.


## Description

On startup the extension will be pulled or updated from git. It won't be updated until the next restart, which will most likely happen regularly anyway.
