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

| Package | Description |
| :------ | :---------- |
| file-roller | Support for Zstandard <sup>[[1](https://gitlab.gnome.org/GNOME/file-roller/blob/master/NEWS)]</sup> (`pacman -S akatsuki/file-roller` to install)|
| fish-git [<sup>AUR</sup>](https://aur.archlinux.org/packages/fish-git/) | |
| flat-remix-gnome [<sup>AUR</sup>](https://aur.archlinux.org/packages/flat-remix-gnome/) | |
| flat-remix-gtk [<sup>AUR</sup>](https://aur.archlinux.org/packages/flat-remix-gtk/) | |
| libass-git [<sup>AUR</sup>](https://aur.archlinux.org/packages/libass-git/) | Fix mpv select wrong fonts weight |
| nautilus | Fix [Hyphen in filename is misleading](https://gitlab.gnome.org/GNOME/nautilus/issues/1177) (`pacman -S akatsuki/natuilus` to install) |
| rime-data [<sup>AUR</sup>](https://aur.archlinux.org/packages/rime-data/) | Replace [community/brise](https://www.archlinux.org/packages/community/x86_64/brise/) <sup>out-of-date</sup> |
| ttf-paratype [<sup>AUR</sup>](https://aur.archlinux.org/packages/ttf-paratype/) | |
| visual-studio-code-bin [<sup>AUR</sup>](https://aur.archlinux.org/packages/visual-studio-code-bin/) | |
