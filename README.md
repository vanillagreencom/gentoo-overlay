# VanillaGreen Gentoo overlay

Quickshell comes from GURU, so enable both repos:

```bash
sudo eselect repository enable guru
sudo eselect repository add vanillagreen git https://github.com/vanillagreencom/gentoo-overlay.git
sudo emaint sync -a
sudo emerge --ask gui-apps/vgs-shell
```
