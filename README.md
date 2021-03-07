# Arch Linux AUR Repository

Automatically built [AUR](https://aur.archlinux.org) packages for
[Arch Linux](https://archlinux.org/).

Each architecture has its own repository:

   * [x86_64](../../releases/tag/x86_64)
   * [aarch64](../../releases/tag/aarch64)
   * [armv7l](../../releases/tag/armv7l)

Please refer to the individual repository links to view available packages and
corresponding `pacman.conf` configuration instructions. Use `uname -m` if you
are unsure of which architecture your system is using.

GitHub Actions [automatically rebuild](../../actions/workflows/repo.yaml) the
packages every Sunday. This process is controlled by the
[repo.yaml](.github/workflows/repo.yaml) file.

Special thanks to:

* [run-on-arch-action](https://github.com/uraimo/run-on-arch-action) for
  simplifying access to ARM platforms during GitHub Actions workflows
* [archlinuxarm-docker](https://github.com/agners/archlinuxarm-docker) for
  weekly builds of Arch Linux ARM images (used by `run-on-arch-action`)
* [build-aur-packages](https://github.com/kopp/build-aur-packages) for a
  similar GitHub Action that is suitable for `x86_64` builds
