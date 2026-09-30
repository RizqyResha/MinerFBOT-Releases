## v1.2.0

# MinerF Bot v1.2.0

## Highlights

- Added unified Float and Net fishing orchestration with Net-priority checks, retry handling, and Float fallback.
- Added Trade Skill confirmation and configurable roster switching.
- Added explicit, consent-gated mouse handover and pointer repositioning through the Action Dispatcher.
- Spaced workflow diagram nodes for clearer separation.
- Added Auto Roster Switch to rotate configured characters based on Life Energy thresholds.

## Validation notes

- Float success and Net-priority/retry orchestration were observed in a bounded live run. Net mini-game success was not achieved; gameplay acceptance remains unverified.
- Mouse handover changes have not received final live validation. Explicit per-run consent and fail-closed safety checks remain required.

## Release assets

- `MinerFBot-Setup-1.2.0.exe`
- `MinerFBot-Setup-1.2.0.exe.sha256`

## v1.0.2

# MinerF Bot v1.0.2

## Highlights

- Fixed the client footer version label to use the desktop bridge version.
- Updated the Windows installer and release metadata to `v1.0.2`.
- Preserved SHA-256 verification before update installation.

## Release assets

- `MinerFBot-Setup-1.0.2.exe`
- `MinerFBot-Setup-1.0.2.exe.sha256`

## v1.0.1

# MinerF Bot v1.0.1

## Highlights

- Maintenance release for validating the in-app update flow.
- Updated the Windows installer and release metadata to `v1.0.1`.
- Preserved SHA-256 verification before update installation.

## Release assets

- `MinerFBot-Setup-1.0.1.exe`
- `MinerFBot-Setup-1.0.1.exe.sha256`

## v1.0.0

# MinerF Bot v1.0.0

## Highlights

- Initial desktop release for MinerF Bot.
- Added Windows installer generation for `win-x64`.
- Added desktop update checks against the public release feed.
- Added SHA-256 verification before update installation.
- Added safe update installation while the application is stopped.
- Improved UI dependency installation with offline-friendly npm retries.

## Release assets

- `MinerFBot-Setup-1.0.0.exe`
- `MinerFBot-Setup-1.0.0.exe.sha256`
