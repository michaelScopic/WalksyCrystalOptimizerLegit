# Walksy's Crystal Optimizer Legit

![icon](https://github.com/michaelScopic/WalksyCrystalOptimizerLegit/assets/67214805/96114b0e-da4e-417c-abed-7dc279acddb1)

Fork of [Walksy's Crystal Optimizer](https://github.com/Walksy/WalksyCrystalOptimizer) but without the AC feature because it's considered cheating.

I have no clue how to program in Java, so if this works maybe God does exist.

Short video showing the difference between the original optimizer and mine:

https://github.com/michaelScopic/WalksyCrystalOptimizer/assets/67214805/81ea7a01-3438-4d68-ba60-9ed50d2b854b

## Building from source (optional)

If you want to compile from source because  you just want to build it or if you don't trust my precompiled package, here's how to do it.

To build this mod from source you need a couple of things.

- `git`
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
