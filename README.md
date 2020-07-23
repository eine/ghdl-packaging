<p align="center">
  <a title="Read the Docs" href="http://ghdl.rtfd.io"><img src="https://img.shields.io/readthedocs/ghdl.svg?longCache=true&style=flat-square&logo=read-the-docs&logoColor=e8ecef&label=ghdl.rtfd.io"></a><!--
  -->
  <a title="Join the chat at https://gitter.im/ghdl1/Lobby" href="https://gitter.im/ghdl1/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge"><img src="https://img.shields.io/badge/chat-on%20gitter-4db797.svg?longCache=true&style=flat-square&logo=gitter&logoColor=e8ecef"></a><!--
  -->
</p>

This repository contains guidelines and recipe examples for packagers willing to distribute GHDL through some package manager. See [ghdl/ghdl#901](https://github.com/ghdl/ghdl/issues/901).

## Arch Linux (AUR) [PKGBUILD]

| | community | mcode | LLVM | GCC |
|---|---|---|---|---|
| [!['archlinux-git' workflow Status](https://img.shields.io/github/workflow/status/eine/ghdl-packaging/archlinux-git?longCache=true&style=flat-square&label=git)](https://github.com/eine/ghdl-packaging/actions?query=workflow%3Aarchlinux-git) | [community-git](./archlinux/community-git) | [mcode-git](./archlinux/mcode-git)<br>(upstream: [details](https://aur.archlinux.org/packages/ghdl-mcode-git/), [git](https://aur.archlinux.org/ghdl-mcode-git.git)) | [llvm-git](./archlinux/llvm-git)<br>(upstream: [details](https://aur.archlinux.org/packages/ghdl-llvm-git/), [git](https://aur.archlinux.org/ghdl-llvm-git.git)) | [gcc-git](./archlinux/gcc-git)<br>(upstream: [details](https://aur.archlinux.org/packages/ghdl-gcc-git/), [git](https://aur.archlinux.org/ghdl-gcc-git.git)) |
| [!['archlinux' workflow Status](https://img.shields.io/github/workflow/status/eine/ghdl-packaging/archlinux?longCache=true&style=flat-square&label=latest)](https://github.com/eine/ghdl-packaging/actions?query=workflow%3Aarchlinux) | [community](./archlinux/community)<br>(upstream: [details](https://git.archlinux.org/svntogit/community.git/?h=packages/ghdl), [git](https://git.archlinux.org/svntogit/community.git/tree/trunk/PKGBUILD?h=packages/ghdl)) | [mcode](./archlinux/mcode) | [llvm](./archlinux/llvm-git) | [gcc](./archlinux/gcc)<br>(upstream: [details](https://aur.archlinux.org/packages/ghdl/), [git](https://aur.archlinux.org/ghdl.git)) |

References:

- ghdl/ghdl: [#507](https://github.com/ghdl/ghdl/issues/507), [#1214](https://github.com/ghdl/ghdl/issues/1214)

## MSYS2 (MINGW32/MINGW64) [PKGBUILD]

| | mcode (MINGW32) | LLVM (MINGW64) |
|---|---|---|
| [!['mingw-git' workflow Status](https://img.shields.io/github/workflow/status/eine/ghdl-packaging/mingw-git?longCache=true&style=flat-square&label=git)](https://github.com/eine/ghdl-packaging/actions?query=workflow%3Amingw-git) | [mcode-git](./msys2-mingw/mcode-git) | [llvm-git](./msys2-mingw/llvm-git) |
| [!['mingw-rc' workflow Status](https://img.shields.io/github/workflow/status/eine/ghdl-packaging/mingw-rc?longCache=true&style=flat-square&label=rc)](https://github.com/eine/ghdl-packaging/actions?query=workflow%3Amingw-rc) | [mcode-rc](./msys2-mingw/mcode-rc) | [llvm-rc](./msys2-mingw/llvm-rc) |
| [!['mingw' workflow Status](https://img.shields.io/github/workflow/status/eine/ghdl-packaging/mingw?longCache=true&style=flat-square&label=latest)](https://github.com/eine/ghdl-packaging/actions?query=workflow%3Amingw) | [mcode](./msys2-mingw/mcode) | [llvm](./msys2-mingw/llvm) |

References:

- ghdl/ghdl: [#497](https://github.com/ghdl/ghdl/issues/497)
- msys2/MINGW-packages: [#5757](https://github.com/msys2/MINGW-packages/issues/5757), [#6686](https://github.com/msys2/MINGW-packages/issues/6686), [#6688](https://github.com/msys2/MINGW-packages/issues/6688)

# Fedora [rpm]

- https://src.fedoraproject.org/rpms/ghdl maps to stable (and latest?).
- https://github.com/eine/rpm-ghdl/commits/update maps to master.

References:

- ghdl/ghdl: [#888](https://github.com/ghdl/ghdl/issues/888)

# Debian [deb] [ghdl/ghdl#377](https://github.com/ghdl/ghdl/issues/377)

- ToDo
- https://salsa.debian.org/electronics-team/ghdl/ghdl/

