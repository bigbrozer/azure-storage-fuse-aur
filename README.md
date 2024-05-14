# Azure Storage Blobfuse AUR package

This is an AUR package for [Azure/azure-storage-fuse](https://github.com/Azure/azure-storage-fuse).

* **Package**: [azure-storage-fuse<sup>AUR</sup>](https://aur.archlinux.org/packages/azure-storage-fuse)

## Build

To build the package, ensure you have make dependencies (`makedepends`) installed first.

Build the package with:

```sh
make
```

## Release

> You will need `pipx install nvchecker` before !

1. Run `make check-updates` to verify newer versions.
2. Bump related `pkgver` in `PKGBUILD`.
3. Run `make`.
4. Run `make take-updates`.
5. Commit and push.
