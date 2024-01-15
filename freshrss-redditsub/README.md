# freshrss-redditimage Docker mod

A [Linuxserver Docker mod](https://github.com/linuxserver/docker-mods/) that installs the [RedditSub](https://github.com/balthisar/xExtension-RedditSub) FreshRSS extension by [balthisar](https://github.com/balthisar).


## Usage

Add `ghcr.io/mentalfs/linuxserver-mod:freshrss-redditsub` to your `DOCKER_MODS` environment variable, for example `DOCKER_MODS=ghcr.io/mentalfs/linuxserver-mods:freshrss-redditsub`. You can add multiple mods by using `|` as delimiter.


## Description

On startup the extension will be pulled or updated from git. It won't be updated until the next restart, which will most likely happen regularly anyway.
