# freshrss-extensions Docker mod

A [Linuxserver Docker mod](https://github.com/linuxserver/docker-mods/) that installs the official FreshRSS extensions from [their central repository](https://github.com/FreshRSS/Extensions).


## Usage

Add `ghcr.io/mentalfs/linuxserver-mod:freshrss-extensions` to your `DOCKER_MODS` environment variable, for example `DOCKER_MODS=ghcr.io/mentalfs/linuxserver-mods:freshrss-extensions`. You can add multiple mods by using `|` as delimiter.


## Description

On startup the extensions will be pulled or updated from git. They won't be updated until the next restart, which will most likely happen regularly anyway.
