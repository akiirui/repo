# Akii's Unofficial User Repository

This repository include some **AUR packages** and some packages **with custom patches**.

All packages build for `[testing]`, ensure enabled `[testing]`.

(This GitHub repo not include PKGBUILD of AUR packages)

### Usage

Add repo to your `pacman.conf`:

```
[akatsuki]
Server = https://repo.akii.ml/$arch
```

And add PGP key ([ArchWiki: Adding unofficial keys](https://wiki.archlinux.org/index.php/Pacman/Package_signing#Adding_unofficial_keys)):

* 0x327233920548825E

The PGP key file also can find on [GitHub](https://github.com/akiirui/repo/blob/master/akatsuki.pub) and [Repository](https://repo.akii.ml/akatsuki.pub).

### Troubleshooting

* Please contact me via [issues](https://github.com/akiirui/repo/issues/new).

### Packages list

- [google-chrome](https://aur.archlinux.org/packages/google-chrome/) <sup>AUR</sup>
- [fish-git](https://aur.archlinux.org/packages/fish-git/) <sup>AUR</sup>
- [flat-remix-gnome-theme](https://github.com/akiirui/repo/tree/master/flat-remix-gnome-theme) : `Blue-Dark-fullPanel` only, conflicts with [flat-remix-gnome](https://aur.archlinux.org/packages/flat-remix-gnome/) <sup>AUR</sup>
    - Removed split packages, because upstream created too many color variants
    - Other color variant, edit PKGBUILD **L28** to you want and `makepkg` by yourself
- [ibus](https://github.com/akiirui/repo/tree/master/ibus) : No `python2` and `gtk2` (`pacman -S akatsuki/ibus akatsuki/libibus` to install)
- [libass-git](https://aur.archlinux.org/packages/libass-git/) <sup>AUR</sup> : Fix mpv select wrong fonts weight
- [otf-cascadia-code-git](https://aur.archlinux.org/packages/otf-cascadia-code-git) <sup>AUR</sup>
- [ttf-cascadia-code-git](https://aur.archlinux.org/packages/ttf-cascadia-code-git) <sup>AUR</sup>
- [ttf-paratype](https://aur.archlinux.org/packages/ttf-paratype/) <sup>AUR</sup>
- [visual-studio-code-bin](https://aur.archlinux.org/packages/visual-studio-code-bin/) <sup>AUR</sup>
