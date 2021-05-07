# Initium for Wayback Archiver

> "initium" in Latin,  Wayback Archiver documentation repo

This repository is a *work in progress*.

Indiscriminate Censor's Hand is the starting point of the Wayback Archiver.
It aims to make the Wayback Machine easier to use and focus on information dissemination.

This organization is a place to bring together all of the Wayback Archiver repositories,
and to work together on making it better. This repository is the center of that organization.

## Table of Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->


- [How it works](#how-it-works)
- [Repositories](#repositories)
  - [Code-free repositories](#code-free-repositories)
  - [Wayback Archiver](#wayback-archiver)
  - [Modules](#modules)
- [Registries](#registries)
- [License](#license)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## How it works

![](./assets/arch.svg)

## Repositories

The [Wayback Archiver](https://github.com/wabarc) organization on GitHub contains many different repositories.
For the most part, these fall into three categories:

1. Wayback, wayback webpages to the Wayback Machine, and the decentralized web;
2. Archiver, archiving and store webpages to third-party repositories;
3. Various non-code repositories.

![](./assets/dependency-graph.svg)

### Code-free repositories

- The [initium][initium] documentation repo, which you're in right now.
- [project-template][project-template] which is a template for creating a code repository.
- The [artwork][artwork] for open-licensed wabarc-related artwork.

### Wayback Archiver

- [wayback][wayback] - The main repo for wayback and publish the messages.
- [archiver][archiver] - Archiving webpages from the published messages by `Wayback Bot`.
- [playback][playback] - Playback archived URLs from Internte Archiver, archive.today and beyond.

### Modules

- [archive.org][archive.org] - A Golang package for request [Internet Archive](https://archive.org/) to archive webpages.
- [archive.is][archive.is] - A Golang package for request [Archive.today](https://archive.today/) to archive webpages.
- [broker][broker] - Distribute webpages to the third party repository.
- [cairn][cairn] - A JavaScript library for snapshot webpages written in TypeScript. The most important module used by *archiver*.
- [distributor][distributor] - GitHub actions for distributing webpages using *broker*.
- [imgbb][imgbb] - A command-line tool and Go package interface for upload images to [ImgBB](https://imgbb.com).
- [ipfs-pinner][ipfs-pinner] - Pin file to IPFS pinning service, required by [wbipfs](https://github.com/wabarc/wbipfs).
- [memento][memento] - A Golang and Command-Line Interface to Time Travel Service (Memento), required by [playback][playback].
- [packer][packer] - Part of the module required by *archiver* using to pack webpages to file, inherits from [archiver][archiver].
- [screenshot][screenshot] - Capture webpage and save as image using chromedp.
- [telegra.ph][telegra.ph] - A command-line tool and Go package interface for wayback webpage to [Telegraph](https://telegra.ph).
- [wbipfs][wbipfs] - A Golang package and CLI tool to transfer file to IPFS.

Other repositories include:

- [snapshot][snapshot] - A Golang package and CLI for snapshot webpages using chromedp.
- [prattein][prattein] - Website for `Wayback Bot` published messages, alias Telegram channel.
- [sitemap][sitemap] - Generate sitemap for [prattein][prattein].
- [on-heroku][on-heroku] - Which is a script tool to deploy *wayback* service as heroku app.
- [on-github][on-github] - Host *wayback* service on GitHub using Actions.
- [heroku-schedule][heroku-schedule] - Scheduling for the Heroku app using GitHub Actions.
- [helper][helper] - Helper functions for Golang projects.
- [logger][logger] - Logger for Golang projects.
- [golang-chromium][golang-chromium] - Docker image bundling Golang and Chromium.
- [githooks][githooks] - Git hooks for development.
- [heva][heva] - Create/update Heroku Config Vars.

## Registries

Wayback Archiver accounts are also maintained on these registries:

- [GitHub @wabarc](https://github.com/wabarc)
- [GitLab @wabarc](https://gitlab.com/wabarc)
- [npm @wabarc](https://www.npmjs.com/org/wabarc)
- [DockerHub @wabarc](https://hub.docker.com/u/wabarc)

## License

This repository is only for documents. All of these are licensed under the Creative Commons Zero v1.0 Universal license, see the [LICENSE](https://github.com/wabarc/initium/blob/main/LICENSE) file for details.

[archive.is]: https://github.com/wabarc/archive.is
[archive.org]: https://github.com/wabarc/archive.org
[archiver]: https://github.com/wabarc/archiver
[artwork]: https://github.com/wabarc/artwork
[aur]: https://github.com/wabarc/aur
[broker]: https://github.com/wabarc/broker
[cairn]: https://github.com/wabarc/cairn
[distributor]: https://github.com/wabarc/distributor
[flutter-bundle]: https://github.com/wabarc/flutter-bundle
[githooks]: https://github.com/wabarc/githooks
[golang-chromium]: https://github.com/wabarc/golang-chromium
[helper]: https://github.com/wabarc/helper
[heroku-schedule]: https://github.com/wabarc/heroku-schedule
[heva]: https://github.com/wabarc/heva
[imgbb]: https://github.com/wabarc/imgbb
[initium]: https://github.com/wabarc/initium
[ipfs-pinner]: https://github.com/wabarc/ipfs-pinner
[logger]: https://github.com/wabarc/logger
[memento]: https://github.com/wabarc/memento
[on-cloudflare]: https://github.com/wabarc/on-cloudflare
[on-github]: https://github.com/wabarc/on-github
[on-heroku]: https://github.com/wabarc/on-heroku
[packer]: https://github.com/wabarc/packer
[playback]: https://github.com/wabarc/playback
[prattein]: https://github.com/wabarc/prattein
[project-template]: https://github.com/wabarc/project-template
[screenshot]: https://github.com/wabarc/screenshot
[sitemap]: https://github.com/wabarc/sitemap
[snapshot]: https://github.com/wabarc/snapshot
[telegra.ph]: https://github.com/wabarc/telegra.ph
[wayback]: https://github.com/wabarc/wayback
[wbipfs]: https://github.com/wabarc/wbipfs
