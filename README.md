# Arch Linux AUR Repository

Automatically built [AUR](https://aur.archlinux.org) packages for
[Arch Linux](https://archlinux.org/) x86_64 architecture.

Releases are provided in the following repository:

   * [x86_64](../../releases/tag/x86_64)

Please refer to the above repository link to view available packages and
corresponding `pacman.conf` configuration instructions. Use `uname -m` if you
are unsure of which architecture your system is using.

If you are using ARM architectures please refer to the
[Arch Linux AUR ARM Repository](https://github.com/benalexau/archarm-aur-repo).

GitHub Actions [automatically rebuild](../../actions/workflows/repo.yaml) the
packages every Sunday. This process is controlled by the
[repo.yaml](.github/workflows/repo.yaml) file.

Thanks to
[build-aur-packages](https://github.com/kopp/build-aur-packages)
for a similar GitHub Action.
