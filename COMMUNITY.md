# Community Release Log

Branch: `community-release`
Fork: `dummy3ye/shell`
Maintained by: @dummy3ye

## Pulled PRs

### 2026-09-11

- **#1995** fix(services): diff network usage per interface to prevent speed spikes
  - cherry-picked from `pr-1995`
- **#1971** feat(nexus): add custom accent colour picker
  - cherry-picked from `pr-1971`

> #1951 and #1957 have since been merged upstream; retained via upstream sync.

### 2026-09-10

- **#1978** feat(bar): add interactive calendar popout with event management
  - cherry-picked `84bd7ecf`

- **#1919** fix(nexus): add filter to show/hide un-named bluetooth devices
  - cherry-picked `2949fe47`
- **#1906** feat(nexus): remember externally-picked wallpapers in a recent list
  - cherry-picked `335058b2`
- **#1901** feat(dashboard): add top apps performance widget and settings toggle
  - cherry-picked `4daab0c1`

- **#1983** fix(nexus): contain wheel events in NavLocations to keep search bar fixed
  - cherry-picked `62fa626b`
- **#1983** fix: use untyped wheel handler syntax in NavLocations
  - `3d69a07a`

- **#1962** feat(launcher): add wallpaper picker shortcut
  - cherry-picked `edb78885`

- **#1959** fix(lock): preserve localized PAM error messages
  - cherry-picked `78aa798f`

- **#1957** fix(dashboard): wrap long weather conditions
  - cherry-picked `aef26376`

- **#1951** fix(picker): handle missing Hypr IPC state
  - cherry-picked `b78dc659`

- **#1945** feat(services): add Intel iGPU utilization from fdinfo
  - merged `a993e4d2`

- **#1912** feat(dashboard): add speed test action and vector gauge to NetworkCard
  - cherry-picked `1c8e528a`

- **#1899** fix(services): update more accurately the capslock state
  - cherry-picked `29e50e8a`

- **#1894** feat(services): integrate battery charge control threshold
  - cherry-picked `701ecd6f`

## Rules

- Always sync from `upstream/main` before stacking new picks.
- Log every new pull here with the cherry-picked commit.