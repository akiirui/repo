# Akii's Unofficial User Repository

This repository include some **AUR packages** and some packages **with custom patches**.

All packages build for `[testing]`, ensure enabled `[testing]`.

(This GitHub repo not include PKGBUILD of AUR packages)

### Usage

Add repo to your `pacman.conf`:

```
[akatsuki]
Server = https://repo.akii.art/$arch
```

And add PGP key ([ArchWiki: Adding unofficial keys][archwiki]:

- `0x94E976626C884E53`

The PGP key file also can find on [GitHub][key-github] and [Repository][key-repo].

### Troubleshooting

- Please contact me via [issues][issues].

[archwiki]: https://wiki.archlinux.org/index.php/Pacman/Package_signing#Adding_unofficial_keys
[key-github]: https://github.com/akiirui/repo/blob/main/akatsuki.pub
[key-repo]: https://repo.akii.ml/akatsuki.pub
[issues]: https://github.com/akiirui/repo/issues/new

---

### Packages list

- [akwaita-theme-git][akwaita-theme-git] <sup>AUR</sup>
- [chrome-gnome-shell][chrome-gnome-shell] <sup>AUR</sup>
- [dofi-manager-git][dofi-manager-git] <sup>AUR</sup>
- [fish-git][fish-git] <sup>AUR</sup>
- [google-chrome][google-chrome] <sup>AUR</sup>
- [mpv-handler-git][mpv-handler-git] <sup>AUR</sup>
- [paru-git][paru-git] <sup>AUR</sup>
- [ttf-paratype][ttf-paratype] : Replace [AUR/ttf-paratype](https://aur.archlinux.org/packages/ttf-paratype/), remove fontconfig conf file.
- [v2ray-domain-list-china][v2ray-domain-list-china] <sup>AUR</sup>
- [visual-studio-code-bin][visual-studio-code-bin] <sup>AUR</sup>

[akwaita-theme-git]: https://aur.archlinux.org/packages/akwaita-theme-git/
[chrome-gnome-shell]: https://aur.archlinux.org/packages/chrome-gnome-shell/
[dofi-manager-git]: https://aur.archlinux.org/packages/dofi-manager-git/
[fish-git]: https://aur.archlinux.org/packages/fish-git/
[google-chrome]: https://aur.archlinux.org/packages/google-chrome/
[mpv-handler-git]: https://aur.archlinux.org/packages/mpv-handler-git/
[paru-git]: https://aur.archlinux.org/packages/paru-git/
[ttf-paratype]: https://github.com/akiirui/repo/tree/main/ttf-paratype
[v2ray-domain-list-china]: https://aur.archlinux.org/packages/v2ray-domain-list-china/
[visual-studio-code-bin]: https://aur.archlinux.org/packages/visual-studio-code-bin/

---

### Archived packages

**These packages not update anymore, for archive only.**

- [flat-remix-gnome][flat-remix-gnome]: Replace [AUR/flat-remix-gnome](https://aur.archlinux.org/packages/flat-remix-gnome/)

[flat-remix-gnome]: https://github.com/akiirui/repo/tree/main/flat-remix-gnome
