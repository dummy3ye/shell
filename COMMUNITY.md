# Community Release Log

Branch: `community-release`
Fork: `dummy3ye/shell`
Maintained by: @dummy3ye

## Pulled PRs

### 2026-09-10

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