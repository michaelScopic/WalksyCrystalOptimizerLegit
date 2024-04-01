# Walksy's Crystal Optimizer Legit

![icon](https://github.com/michaelScopic/WalksyCrystalOptimizerLegit/assets/67214805/96114b0e-da4e-417c-abed-7dc279acddb1)

Fork of [Walksy's Crystal Optimizer](https://github.com/Walksy/WalksyCrystalOptimizer) but without the AC feature because it's considered cheating.

I have no clue how to program in Java, so if this works maybe God does exist.


## Preview

Short video showing the difference between the original optimizer and mine:

[COOKING UP BETTER PREVIEW SOON!]

## Installing

To install this mod, you need a few things:

1. Any Minecraft version with at least 1.19
2. [Fabric Mod Loader](https://fabricmc.net/use/installer/) (You will also need the Fabric API of course.)

Download the mod from the [Releases page](https://github.com/michaelScopic/WalksyCrystalOptimizerLegit/releases), and drag it into your mods folder.

Launch the game and kill your opponents! Enjoy.

## Bugs, issues, suggestions, or requests

### Bugs/issues
Bugs/issues can be reported by making an [issue ticket](https://github.com/michaelScopic/WalksyCrystalOptimizerLegit/issues). Please do your best to describe what's happening.

### Suggestions/requests
Suggestions and requests can also be made with the [issue tickets](https://github.com/michaelScopic/WalksyCrystalOptimizerLegit/issues). Please note that I am no where near fluent with Java, so any crazy requests will probably be denied (sorry). 

**I'm not the best at noticing issues on GitHub, so if I don't respond in a timely manner, please DM me on [Discord](https://github.com/michaelScopic#discord).**

## -- EXPERTS ONLY PAST HERE --
## Building from source (optional)

If you want to compile from source because  you just want to build it or if you don't trust my precompiled package, here's how to do it.

To build this mod from source you need a couple of things.

- `git`  (The Git CLI interface [eg: `git clone`, `git pull`, etc])
- Gradle

To install Gradle on Windows, install [Scoop](https://scoop.sh/) and then run `scoop install gradle`.

For MacOS, use [Homebrew](https://brew.sh), and run `brew install gradle`

For Linux, use your package manager. (Eg: `sudo apt install gradle`, `sudo pacman -S gradle`, `sudo dnf install gradle`, etc)

### In your terminal, run these commands:

#### Windows users:
```sh
git clone https://github.com/michaelScopic/WalksyCrystalOptimizerLegit
cd WalksyCrystalOptimizerLegit

gradlew.bat build
```

#### MacOS/Linux users:

```sh
git clone https://github.com/michaelScopic/WalksyCrystalOptimizerLegit
cd WalksyCrystalOptimizerLegit

gradlew build
```

Output `.jar` will be placed in `./build/libs/`.
