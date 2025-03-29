# Mods for Linuxserver.io containers

Here are some [Linuxserver Docker mods](https://github.com/linuxserver/docker-mods/).


## Usage

Add `ghcr.io/mentalfs/linuxserver-mods:<tag>` to your `DOCKER_MODS` environment variable, for example `DOCKER_MODS=ghcr.io/mentalfs/linuxserver-mods:freshrss-extensions`. You can add multiple mods by using `|` as delimiter.


## Mods

| Tag                     | Short description                                                                               |
|-------------------------|-------------------------------------------------------------------------------------------------|
| [freshrss-extensions]   | Installs the official extensions from the [FreshRSS central repository]                         |
| [freshrss-comicsinfeed] | Installs the [Comics in Feed FreshRSS extension] by [giventofly](https://github.com/giventofly) |
| [freshrss-redditsub]    | Installs the [RedditSub FreshRSS extension] by [balthisar](https://github.com/balthisar)        |

## Mod collections

These are multiple mods packed into one image for convenience. Add them to `DOCKER_MODS` just like any other mod, for example `DOCKER_MODS=ghcr.io/mentalfs/linuxserver-mods:freshrss-all`.

`freshrss-all` 
: [freshrss-extensions], [freshrss-comicsinfeed], [freshrss-redditsub]


[freshrss-extensions]:               freshrss-extensions/README.md
[FreshRSS central repository]:       https://github.com/FreshRSS/Extensions
[freshrss-comicsinfeed]:             freshrss-comicsinfeed/README.md
[Comics in Feed FreshRSS extension]: https://github.com/giventofly/freshrss-comicsinfeed
[freshrss-redditsub]:                freshrss-redditsub/README.md
[RedditSub FreshRSS extension]:      https://github.com/balthisar/xExtension-RedditSub
