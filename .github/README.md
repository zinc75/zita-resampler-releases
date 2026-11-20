# zita-resampler release snapshots

The files of the release archives of [zita-resampler](https://kokkinizita.linuxaudio.org/linuxaudio/), one commit per release, exactly as published. This is not a fork and not a mirror. zita-resampler is developed and maintained by Fons Adriaensen at https://kokkinizita.linuxaudio.org/linuxaudio/: nothing is developed or maintained here, and this repository is not affiliated with the project. It only keeps snapshots of the releases.

zita-resampler is a C++ library for resampling audio, written by Fons Adriaensen, who maintains it, with the NEON code by Nicolas Belin (`AUTHORS`). It is under the GPL 3 or later (`COPYING`). Questions and contributions belong to Fons Adriaensen: https://kokkinizita.linuxaudio.org/linuxaudio/.

## Why this repository exists

[Jack Apps Collection for macOS](https://github.com/zinc75/jack-apps-collection-macos) builds zita-resampler and links it statically into its applications. Each application ships the licence and the source of the libraries it contains, so the collection needs to point to the exact source of the release that it uses. It does so with a Git submodule, which needs a commit of a Git repository.

Fons Adriaensen publishes zita-resampler as release archives only, with no Git repository. There is no Git commit that gives the source of a release. This repository fills that gap: each release is one commit, and the collection references the commit of the release it uses. The snapshots also keep the source available if the download site goes away.

## What is in it

Each tag points to a commit whose files are those of the release archive, nothing added and nothing changed. The commit message gives the address of the archive and its SHA-256 (the author publishes no checksum and no signature). The archive is also attached to the release of the same name.

The only addition is this `README`, in `.github/`, on top of the tagged commits: it is not part of any release.
