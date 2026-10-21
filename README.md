# vendor-packages

Pinned copies of third-party system packages used by Indo Warehouse's Heroku builds, so a build never depends on an upstream mirror being up.

## libheif 1.19.8 (release `libheif-1.19.8`)

Unmodified `.deb` files from the strukturag/libheif PPA for Ubuntu 24.04 (noble, amd64):
`https://ppa.launchpadcontent.net/strukturag/libheif/ubuntu/pool/main/libh/libheif/`

- `libheif1_1.19.8-1~ppa1~ubuntu24.04_amd64.deb`
- `libheif-plugin-libde265_1.19.8-1~ppa1~ubuntu24.04_amd64.deb`
- `libheif-plugin-aomdec_1.19.8-1~ppa1~ubuntu24.04_amd64.deb`

(`~` is replaced by `-` in the asset names.) Each file's SHA-256 matches the PPA's published `dists/noble/main/binary-amd64/Packages` index (checked 2026-10-21); see `SHA256SUMS` on the release.

libheif is licensed under the GNU LGPL v3 (plugins per their upstream licenses); source: https://github.com/strukturag/libheif
