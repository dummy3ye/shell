# Community Release Log

Branch: `community-release`
Fork: `dummy3ye/shell`
Maintained by: @dummy3ye

Tracks `upstream/main` and stack fixes/features that upstream is stalled on.
Each entry records the upstream PR and how it got in.

## Pulled PRs

### 2026-09-10

- **#1912** feat(dashboard): add speed test action and vector gauge to NetworkCard
  - cherry-picked `1c8e528a`

- **#1951** fix(picker): handle missing Hypr IPC state
  - cherry-picked `b78dc659`

- **#1959** fix(lock): preserve localized PAM error messages
  - cherry-picked `78aa798f`

### 2026-09-10

- **#1945** feat(services): add Intel iGPU utilization from fdinfo (own PR)
  - merged from `feat/services-intel-gpu-busy` via `a993e4d2`

## Rules

- Always sync from `upstream/main` before stacking new picks.
- Pick high-value community PRs that have been open/ignored upstream.
- Log every new pull here with the cherry-picked commit.