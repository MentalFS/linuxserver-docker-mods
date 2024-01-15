# Mods for Linuxserver.io containers

Here are some [Linuxserver Docker mods](https://github.com/linuxserver/docker-mods/).


## Usage

Add `ghcr.io/mentalfs/linuxserver-mod:<tag>` to your `DOCKER_MODS` environment variable, for example `DOCKER_MODS=ghcr.io/mentalfs/linuxserver-mods:freshrss-extensions`. You can add multiple mods by using `|` as delimiter.


## Mods

| Tag                                                    | Short description                                                                                                                           |
|--------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------|
| [freshrss-extensions](freshrss-extensions/README.md)   | Installs the official FreshRSS extensions from [their central repository](https://github.com/FreshRSS/Extensions)                           |
| [freshrss-redditimage](freshrss-redditimage/README.md) | Installs the [RedditImage](https://github.com/aledeg/xExtension-RedditImage) FreshRSS extension by [aledeg](https://github.com/aledeg)      |
| [freshrss-redditsub](freshrss-redditsub/README.md)     | Installs the [RedditSub](https://github.com/balthisar/xExtension-RedditSub) FreshRSS extension by [balthisar](https://github.com/balthisar) |

