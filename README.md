# Hydrinity ![CI](https://github.com/Hydrinity/Hydrinity/workflows/CI/badge.svg)
A [Tuinity](http://github.com/Spottedleaf/Tuinity) fork with experimental performance patches and improvements. Hydrinity also ports patches from certain performance mods, such as [Lithium](https://www.curseforge.com/minecraft/mc-mods/lithium), and other Paper forks.

Hydrinity is a fork for my own server, intended to help solve certain performance bottlenecks, and as such, I tend to test all changes in production. That being said, there is no *guarantee* of stability. Try it out at your own risk.

### Configuration
By default, Hydrinity mirrors vanilla behavior. In order to achieve the best performance, it's advised to change a lot of the configuration options. Luckily, I've created an [optimized configuration guide](https://github.com/Hydrinity/Hydrinity/wiki/Recommended-optimized-configuration) for Hydrinity that outlines all options within the configuration.

### Building
```bash
git submodule update --init --recursive
./hydrinity jar
```