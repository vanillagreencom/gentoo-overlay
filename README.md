# VanillaGreen Gentoo overlay

The Gentoo overlay for [VGS](https://github.com/vanillagreencom/vgs), a desktop shell for Hyprland. It holds no package at present.

## Packages

- `gui-apps/vgs-shell`, the package of VGS v1, is retired and removed.
- VGS v2 ships here as `gui-apps/vgs`: a release ebuild, and a live `vgs-9999` ebuild that builds the `main` branch.
- Neither ebuild is published yet. VGS needs Quickshell 0.3.1 and Hyprland 0.56 with Lua configuration, and Gentoo's repositories do not carry that Hyprland.

## Install

Until the ebuilds are published, use the install script or a checkout from the VGS README, and install Quickshell and Hyprland yourself.
