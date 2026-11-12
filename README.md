# fontconfig

fontconfig 2.15.0: finding and listing fonts for Qt and other programs (looks in the fonts-dejavu and xorg font folders)

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install fontconfig
```

| | |
|---|---|
| Version | 2.15.0 |
| Licence | MIT |
| Upstream | https://www.fontconfig.org |
| Needs | [`xorg`](https://github.com/Artfical/tpkg-xorg), [`expat`](https://github.com/Artfical/tpkg-expat), [`fonts-dejavu`](https://github.com/Artfical/tpkg-fonts-dejavu) |
| Needs tOS build | 618 or newer |
| Size | 219496 bytes (765506 unpacked) |
| SHA-256 of the `.tpkg` | `46a65baf7d29ec9c23bfd1a14a59db880c346fa60c910f1f207481beec0482f2` |

## Commands it adds

| Command | Runs |
|---|---|
| `fc-list` | `bin/fc-list` |
| `fc-match` | `bin/fc-match` |
| `fc-cache` | `bin/fc-cache` |

## Download

The package file (`fontconfig-2.15.0.tpkg`) and the sources it was built from are the assets of the
[v2.15.0 release](https://github.com/Artfical/tpkg-fontconfig/releases/tag/v2.15.0).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `fontconfig-2.15.0.tar.xz`

Check a download: `sha256sum fontconfig-2.15.0.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: MIT. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
