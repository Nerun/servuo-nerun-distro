# RunUO is over!!!
RunUO is abandoned. Official team abandoned it after version 2.3. Mark Sturgill, after take the reins for a while, officially abandoned it at version 2.6, with a few updates to 2.7 beta (commit 991). So, and now? Mark Sturgill have recommended move to ServUO. I also recommend. **You will not need Nerun's Distro for ServUO**, it already have a Create World gump plus XMLSpawner by default.

[ServUO community](https://www.servuo.com/)
    
[ServUO GitHub](https://github.com/ServUO/ServUO)

---

# NERUN's DISTRO

## About
Nerun's Distro is an addon for ServUO centered on the settlement of the game, using the Premium Spawner engine. Easy to use, this addon includes spawns for an _almost_ 100% spawned world: Felucca, Trammel, Ilshenar, Malas, Tokuno and Ter Mur. Tutorials in english and portuguese. Includes other scripts:

* CEO's Yet Another Arya Addon Generator v3.0
* Custom Regions in a Box 4.0
* Joeku's Automatic Speed Booster;
* Joeku's Staff Runebook;
* Joeku's Toolbar;
* Static Exporter;
* Talow's Stairs Addon v1.0;
* Termax's Staff Orb;
* Zen Archer's Spawn Editor v2.

## Content
There are one folder:

    ../distro


## Installation

Copy everything inside "Distro" folder and paste it all inside your ServUO folder (overwrite).

## Usage
1. Use command _\[spawner_, it's the easiest beginning.
2. Then click _Apocalypse now_.
3. Now click _Let there be light_.
4. Now Select _Spawns by Expansion_. There are 3 options: Classic Spawns (pre-ML era), Mondain's Legacy and KR, SA and HS era.
5. Read tutorial inside 7-ZIP file for more details and learn how to become an "advanced user".

## Troubleshooting with Linux and Mono
ALWAYS use the latest Mono version, and ALWAYS download it from [Mono Official Download page](https://www.mono-project.com/download/stable/).

DON'T use Mono version in Debian repositories, it's OLD! Use anything above version 5.10!

Sometimes you can have problems when running ServUO after properly compile the server. If you receive any error message related to a "libz" missing, install these libraries:

    zlib1g
    zlib1g-dbg
    zlib1g-dev

In Debian Linux it's easy, just go to terminal and:

    sudo aptitude install zlib1g zlib1g-dbg zlib1g-dev
