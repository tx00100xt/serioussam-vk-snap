[![serioussamc-vk](https://snapcraft.io//serioussam-vk/badge.svg)](https://snapcraft.io/serioussam-vk)
<!--
[![Snap Status](https://build.snapcraft.io/badge/tx00100xt/serioussam-vk-snap.svg)](https://build.snapcraft.io/user/tx00100xt/serioussam-vk-snap)
-->
<h1 align="center">
  <img src="https://raw.githubusercontent.com/tx00100xt/SeriousSamClassic-VK/main/SamTFE/serioussam.png" alt="SeriousSamClassic-VK">
  <br />
  SeriousSamClassic-VK
</h1>

<p align="center"><b>This is a snap for SeriousSamClassic-VK</b>

<!-- Uncomment and modify this when you are provided a build status badge
<p align="center">
<a href="https://build.snapcraft.io/user/snapcrafters/fork-and-rename-me"><img src="https://build.snapcraft.io/badge/snapcrafters/fork-and-rename-me.svg" alt="Snap Status"></a>
</p>
-->

<!-- Uncomment and modify this when you have a screenshot
![my-snap-name](screenshot.png?raw=true "my-snap-name")
-->


[![Get it from the Snap Store](https://snapcraft.io/static/images/badges/en/snap-store-white.svg)](https://snapcraft.io/serioussam-vk)

   
  SeriouSamClassic-VK is a family of enhanced ports of the Serious-Engine for running on modern operating systems.
  It runs on Windows, Linux, FreeBSD, macOS and adds new features not found in the games as originally
  published by Croteam.

## Version
1.10.6d

## Installation
([Don't have snapd installed?](https://snapcraft.io/docs/core/install))

### From the store
This snap is now in the store, simply run

    $ sudo snap install serioussam-vk --beta

### Manually
Clone this repo and run

    $ snapcraft

in the git repo (serioussam-vk-snap). Then install the produced snap with

    $ snap install *.snap --dangerous

## Game data

  This package only provides the engine, you need a valid copy of the (proprietary) game data to launch the game.
  When you first start the game, you will be asked to place your game data along the following paths:

    ~/snap/serioussam-vk/current/.local/share/Serious-Engine/serioussam

    ~/snap/serioussam-vk/current/.local/share/Serious-Engine/serioussamse

  You can place game data in these paths before starting the game. Then the game will start immediately.

## Running SeriousSamClassic-VK
Run it from shell:

    $ serioussam-vk

or

    $ serioussam-vk.se

or simply run the desktop entry, called:  
  
**Serious Sam The First Encounter**,  
**Serious Sam The Second Encounter**.

## Running SeriousSamClassic-VK with XPLUS modification
Run it from shell:

    cd ~/.
    wget https://archive.org/download/sam-tfe-xplus/SamTFE-XPLUS.tar.xz
    wget https://archive.org/download/sam-tse-xplus/SamTSE-XPLUS.tar.xz
    tar -xJvpf SamTFE-XPLUS.tar.xz -C ~/snap/serioussam-vk/current/.local/share/Serious-Engine/serioussam
    tar -xJvpf SamTSE-XPLUS.tar.xz -C ~/snap/serioussam-vk/current/.local/share/Serious-Engine/serioussamse

Next, run the modification from the game menu

## Known Issues

* There is no multiplayer compatibility between Windows and *nix systems.

## Screenshots
<h1 align="center">
  <img src="screenshot1.png" alt="Screenshot 1 here!">
  <br/>
</h1>
<p align="center">SeriousSamClassic-VK running on Linux with XPLUS Mod. Metropolis</p>

<h1 align="center">
  <img src="screenshot2.png" alt="Screenshot 2 here!">
  <br/>
</h1>
<p align="center">SeriousSamClassic-VK running on Linux with XPLUS Mod. Alley Of Sphinxes</p>

<h1 align="center">
  <img src="screenshot3.png" alt="Screenshot 3 here!">
  <br/>
</h1>
<p align="center">SeriousSamClassic-VK running on Linux with XPLUS Mod. Alley Of Sphinxes</p>

<h1 align="center">
  <img src="screenshot4.png" alt="Screenshot 1 here!">
  <br/>
</h1>
<p align="center">SeriousSamClassic-VK running on Linux with XPLUS Mod. Sierra de chiapas</p>

<h1 align="center">
  <img src="screenshot5.png" alt="Screenshot 2 here!">
  <br/>
</h1>
<p align="center">SeriousSamClassic-VK running on Linux with XPLUS Mod. Land of the Damned</p>

<h1 align="center">
  <img src="screenshot6.png" alt="Screenshot 3 here!">
  <br/>
</h1>
<p align="center">SeriousSamClassic-VK running on Linux with XPLUS Mod. The Grand Cathedral</p>

## Upstream Project
https://github.com/tx00100xt/SeriousSamClassic-VK

<a href="https://github.com/tx00100xt/tx00100xt/blob/main/gpg-personal.pub" target="_blank"> <img alt="" src="https://img.shields.io/badge/gpg%20personal-CDC41982C027BAAA-blue?style=for-the-badge&labelColor=090909"></a> <a href="mailto:t.x00100x.t@yandex.ru" target="_blank"> <img alt="Yandex" src="https://img.shields.io/badge/-mail.yandex-090909?style=for-the-badge&logo=data:image/svg+xml;utf8;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGVuYWJsZS1iYWNrZ3JvdW5kPSJuZXcgMCAwIDI0IDI0IiB2aWV3Qm94PSIwIDAgMjQgMjQiPjxwb2x5Z29uIGZpbGw9IiNERjI1MUYiIHBvaW50cz0iMTEuODE3IDEzLjAxNyA3Ljk4MyAyLjI1IDUuMzY3IDIuMjUgMTAuNTcgMTYuMjE0IDEwLjU3IDI0IDEyLjk3NSAyNCAxMi45NzUgMTYuMzAzIDE4LjYzMyAwIDE2LjIyOCAwIDExLjgxNyAxMy4wMTciLz48cG9seWdvbiBmaWxsPSIjQzIyMDFCIiBwb2ludHM9IjcuOTgzIDIuMjUgNS4zNjcgMi4yNSAxMC41NyAxNi4yMTQgMTAuNTcgMjQgMTEuODMyIDI0IDExLjgzMiAxMi45NzIgMTEuODE3IDEzLjAxNyA3Ljk4MyAyLjI1Ii8+PC9zdmc+"></a>

## Licenses
Serious Engine is licensed under the GNU GPL v2 (see LICENSE file).

See https://raw.githubusercontent.com/tx00100xt/SeriousSamClassic-VK/main/LICENSE

## Remaining tasks

  - [x] Fork the [Snapcrafters template](https://github.com/snapcrafters/fork-and-rename-me) repository to your own GitHub account.
    - If you have already forked the Snapcrafter template to your account and want to create another snap, you'll need to use GitHub's [Import repository](https://github.com/new/import) feature because you can only fork a repository once.
  - [x] Rename the forked Snapcrafters template repository
  - [x] Update the description of the repository
  - [x] Update logos and references to `[Project]` and `[my-snap-name]`
  - [x] Create a snap that runs in `devmode`
  - [x] Register the snap in the store, **using the preferred upstream name**
  - [x] Add a screenshot to this `README.md`
  - [x] Publish the `devmode` snap in the Snap store edge channel
  - [x] Add install instructions to this `README.md`
  - [x] Update snap store metadata, icons and screenshots
  - [x] Convert the snap to `strict` confinement, or `classic` confinement if it qualifies
  - [x] Publish the confined snap in the Snap store beta channel
  - [x] Update the install instructions in this `README.md`
  - [x] Post a call for testing on the [Snapcraft Forum](https://forum.snapcraft.io) - [link to the post](https://forum.snapcraft.io/t/call-for-testing-for-serioussamclassic-vk/38863)
  - [ ] Make a post in the [Snapcraft Forum](https://forum.snapcraft.io) asking for a transfer of the snap name from you to snapcrafters - [link]()
  - [ ] Ask a [Snapcrafters admin](https://github.com/orgs/snapcrafters/people?query=%20role%3Aowner) to fork your repo into github.com/snapcrafters, and configure the repo for automatic publishing into edge on commit
  - [ ] Add the provided Snapcraft build badge to this `README.md`
  - [ ] Publish the snap in the Snap store stable channel
  - [ ] Update the install instructions in this `README.md`
  - [ ] Post an announcement in the [Snapcraft Forum](https://forum.snapcraft.io) - [link]()
  - [ ] Submit a pull request or patch upstream that adds snap install documentation - [link]()
  - [ ] Submit a pull request or patch upstream that adds the `snapcraft.yaml` and any required assets/launchers - [link]()
  - [x] Add upstream contact information to the `README.md`  
  - If upstream accept the PR:
    - [ ] Request upstream create a Snap store account
    - [ ] Contact the Snap Advocacy team to request the snap be transferred to upstream
  - [ ] Ask the Snap Advocacy team to celebrate the snap - [link]()

<!--
## The Snapcrafters

| [![Your Name](https://gravatar.com/avatar/bc0bced65e963eb5c3a16cab8b004431/?s=128)](https://github.com/yourname/) |
| :---: |
| [Your Name](https://github.com/yourname/) |
--> 

<!-- Uncomment and modify this when you have upstream contacts
## Upstream

| [![Upstream Name](https://gravatar.com/avatar/bc0bced65e963eb5c3a16cab8b004431?s=128)](https://github.com/upstreamname) |
| :---: |
| [Upstream Name](https://github.com/upstreamname) |
-->
