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

- [fish-git](https://aur.archlinux.org/packages/fish-git/) <sup>AUR</sup>
- [flat-remix-gnome-theme](https://github.com/akiirui/repo/tree/master/flat-remix-gnome-theme) : Split package, conflicts with [flat-remix-gnome](https://aur.archlinux.org/packages/flat-remix-gnome/) <sup>AUR</sup>
    - These packages **not change your GDM theme**, Have patch to remove **popup-menu border** in `prepare()`
    - flat-remix-gnome-theme : Regular variant
    - flat-remix-gnome-theme-dark : Dark variant
    - flat-remix-gnome-theme-darkest : Darkest variant (Temporarily unavailable)
    - flat-remix-gnome-theme-miami : Miami variant (Temporarily unavailable)
    - flat-remix-gnome-theme-miami-dark : Miami Dark variant (Temporarily unavailable)
- [ibus](https://github.com/akiirui/repo/tree/master/ibus) : No `python2` and `gtk2` (`pacman -S akatsuki/ibus akatsuki/libibus` to install)
- [libass-git](https://aur.archlinux.org/packages/libass-git/) <sup>AUR</sup> : Fix mpv select wrong fonts weight
- [mutter](https://github.com/akiirui/repo/tree/master/mutter) : [Fix center window position](http://gitlab.gnome.org/GNOME/mutter/merge_requests/962) (`pacman -S akatsuki/mutter` to install)
- [transmission-gtk](https://github.com/akiirui/repo/tree/master/transmission-gtk) : [Fix window width](https://github.com/transmission/transmission/pull/1069) (`pacman -S akatsuki/transmission` to install)
- [ttf-paratype](https://aur.archlinux.org/packages/ttf-paratype/) <sup>AUR</sup>
- [visual-studio-code-bin](https://aur.archlinux.org/packages/visual-studio-code-bin/) <sup>AUR</sup>
