# freshrss-redditimage Docker mod

A [Linuxserver Docker mod](https://github.com/linuxserver/docker-mods/) that installs the [RedditImage](https://github.com/aledeg/xExtension-RedditImage) FreshRSS extension by [aledeg](https://github.com/aledeg).


## Usage

Add `ghcr.io/mentalfs/linuxserver-mod:ifreshrss-redditimage` to your `DOCKER_MODS` environment variable, for example `DOCKER_MODS=ghcr.io/mentalfs/linuxserver-mods:freshrss-redditimage`. You can add multiple mods by using `|` as delimiter.


## Description

On startup the extension will be pulled or updated from git. It won't be updated until the next restart, which will most likely happen regularly anyway.
