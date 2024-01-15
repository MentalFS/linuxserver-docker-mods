# Mods for Linuxserver.io containers

Here are some [Linuxserver Docker mods](https://github.com/linuxserver/docker-mods/).


## Usage

Add `ghcr.io/mentalfs/linuxserver-mods:<tag>` to your `DOCKER_MODS` environment variable, for example `DOCKER_MODS=ghcr.io/mentalfs/linuxserver-mods:freshrss-extensions`. You can add multiple mods by using `|` as delimiter.


## Mods

| Tag                                                    | Short description                                                                                            |
|--------------------------------------------------------|--------------------------------------------------------------------------------------------------------------|
| [freshrss-extensions](freshrss-extensions/README.md)   | Installs the official FreshRSS extensions from [their central repository][freshrss-extensions]               |
| [freshrss-redditimage](freshrss-redditimage/README.md) | Installs the [RedditImage][freshrss-redditimage] FreshRSS extension by [aledeg](https://github.com/aledeg)   |
| [freshrss-redditsub](freshrss-redditsub/README.md)     | Installs the [RedditSub][freshrss-redditsub] FreshRSS extension by [balthisar](https://github.com/balthisar) |

## Mod collections

These are multiple mods packed into one image for convenience. Add them to `DOCKER_MODS` just like any other mod, for example `DOCKER_MODS=ghcr.io/mentalfs/linuxserver-mods:freshrss-all`.

| Tag                                                    | Mods                                                                   |
|--------------------------------------------------------|------------------------------------------------------------------------|
| `freshrss-all`                                         | [freshrss-extensions], [freshrss-redditimage] and [freshrss-redditsub] |

[freshrss-extensions]:  https://github.com/FreshRSS/Extensions
[freshrss-redditimage]: https://github.com/aledeg/xExtension-RedditImaged
[freshrss-redditsub]:   https://github.com/balthisar/xExtension-RedditSub
