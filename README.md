# Akii's Unofficial User Repository

This repository include PKGBUILD from Akatsuki maintained and some useful packages.

All packages build for `[testing]`, ensure enabled `[testing]`.

(This GitHub repo not include PKGBUILD of AUR packages)

### Usage

Add repo to your pacman.conf

```
[akatsuki]
Server = https://repo.akii.ml/$arch
```

And add PGP key ([ArchWiki: Adding unofficial keys](https://wiki.archlinux.org/index.php/Pacman/Package_signing#Adding_unofficial_keys))

* [0x327233920548825E](http://pool.sks-keyservers.net/pks/lookup?search=0x327233920548825E&fingerprint=on&op=index)

### Troubleshooting

* Please contact me via [issues](https://github.com/akiirui/repo/issues/new).

### Packages list

- `file-roller` : [Support for Zstandard](https://gitlab.gnome.org/GNOME/file-roller/blob/master/NEWS) (`pacman -S akatsuki/file-roller` to install)
- `fish-git` [<sup>AUR</sup>](https://aur.archlinux.org/packages/fish-git/)
- `flat-remix-gnome-theme` : Split package, conflicts with [AUR/flat-remix-gnome](https://aur.archlinux.org/packages/flat-remix-gnome/)
    - **These packages not change your GDM theme**, Have patch to remove **popup-menu border** in `prepare()`.
    - `flat-remix-gnome-theme` : Regular variant
    - `flat-remix-gnome-theme-dark` : Dark variant
    - `flat-remix-gnome-theme-darkest` : Darkest variant
    - `flat-remix-gnome-theme-miami` : Miami variant
    - `flat-remix-gnome-theme-miami-dark` : Miami Dark variant
- `flat-remix-gtk-theme` : Split package, conflicts with [AUR/flat-remix-gtk](https://aur.archlinux.org/packages/flat-remix-gtk/)
    - `flat-remix-gtk-theme` : Regular variant
    - `flat-remix-gtk-theme-dark` : Dark variant
    - `flat-remix-gtk-theme-darker` : Darker variant
    - `flat-remix-gtk-theme-darkest` : Darkest variant
- `libass-git` [<sup>AUR</sup>](https://aur.archlinux.org/packages/libass-git/) : Fix mpv select wrong fonts weight
- `rime-data` [<sup>AUR</sup>](https://aur.archlinux.org/packages/rime-data/) : Replace [community/brise](https://www.archlinux.org/packages/community/x86_64/brise/) <sup>out-of-date</sup>
- `transmission-gtk` : [Fix window width](https://github.com/transmission/transmission/pull/1069) (`pacman -S akatsuki/transmission` to install)
- `ttf-paratype` [<sup>AUR</sup>](https://aur.archlinux.org/packages/ttf-paratype/)
- `visual-studio-code-bin` [<sup>AUR</sup>](https://aur.archlinux.org/packages/visual-studio-code-bin/)
