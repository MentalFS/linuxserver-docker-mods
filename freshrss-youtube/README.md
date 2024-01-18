# freshrss-youtube Docker mod

A [Linuxserver Docker mod](https://github.com/linuxserver/docker-mods/) that installs the [YouTube](https://github.com/kevinpapst/freshrss-youtube) FreshRSS extension by [kevinpapst](https://github.com/kevinpapst).


## Usage

Add `ghcr.io/mentalfs/linuxserver-mods:freshrss-youtube` to your `DOCKER_MODS` environment variable, for example `DOCKER_MODS=ghcr.io/mentalfs/linuxserver-mods:freshrss-youtube`. You can add multiple mods by using `|` as delimiter.


## Description

On startup the extension will be pulled or updated from git. It won't be updated until the next restart, which will most likely happen regularly anyway.
