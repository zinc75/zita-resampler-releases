# zita-resampler release snapshots

The files of the release archives of [zita-resampler](https://kokkinizita.linuxaudio.org/linuxaudio/), one commit per release, exactly as published. This is not a fork and not a mirror. zita-resampler is developed and maintained by Fons Adriaensen at https://kokkinizita.linuxaudio.org/linuxaudio/: nothing is developed or maintained here, and this repository is not affiliated with the project. It only keeps snapshots of the releases.

zita-resampler is a C++ library for resampling audio, by Fons Adriaensen, with the NEON code by Nicolas Belin (`AUTHORS`). It is under the GPL 3 or later (`COPYING`). Questions and contributions belong to its author: https://kokkinizita.linuxaudio.org/linuxaudio/.

## Why this repository exists

[Jack Apps Collection for macOS](https://github.com/zinc75/jack-apps-collection-macos) links zita-resampler statically into `zita-n2j`, and each application ships the licence and the source of what it contains. The author publishes release archives and has no Git repository, so there is no commit to reference for a release. The collection therefore needs a Git repository where the release is a commit, to reference it as a submodule. This repository keeps that copy, and it keeps the source available if the download site goes away.

## What is in it

Each tag points to a commit whose files are those of the release archive, nothing added and nothing changed. The commit message gives the address of the archive and its SHA-256; the author publishes no checksum and no signature. The archive is also attached to the release of the same name. This `README` is the only addition: it is in `.github/`, on top of the tagged commits, and is not part of any release.
