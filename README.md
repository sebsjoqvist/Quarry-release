# Quarry updates

This repository exists to serve one file: `appcast.xml`, the update feed that
installed copies of Quarry check.

- `appcast.xml` is published at <https://sebsjoqvist.github.io/Quarry-release/appcast.xml>
  and is written by `tools/release.sh` in the main repository.
- The `.dmg` for each version is attached to the matching GitHub Release, not
  committed here, so this repository stays small.

Both addresses are compiled into every build of Quarry. Renaming this repository
or moving it would leave existing installs checking a URL that no longer answers.
