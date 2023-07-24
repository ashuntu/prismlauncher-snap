# PrismLauncher Snap

Snap for the [PrismLauncher][prismlauncher] [Minecraft][minecraft] launcher. This Snap is *unofficial* and not supported directly by the PrismLauncher team, MultiMC, or Microsoft/Mojang.

[**See PrismLauncher's README for more information.**][prismlauncher]

## User: Install

```
snap install prismlauncher
```

## Developer: Build, Install, and Run

1. Clone the repository: `git clone https://github.com/ashuntu/prismlauncher-snap`
2. Enter the repository: `cd prismlauncher-snap`
3. Run `snapcraft`
4. Run `snap install prismlauncher_*.snap --dangerous` to install
5. Run `snap run prismlauncher` to run PrismLauncher (you'll be able to see logs this way), or click the .desktop icon in your application launcher

*Use `snap refresh prismlauncher --amend` to revert to the store version of the Snap after installing a `--dangerous` Snap.*



[minecraft]: https://minecraft.net
[prismlauncher]: https://github.com/PrismLauncher/PrismLauncher