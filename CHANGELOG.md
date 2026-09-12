# Changelog

All notable changes are documented here.
Format follows keepachangelog.com, versions are semver-ish.

## [0.4.1] - 2026-06-06

### Fixed
- crash on paths containing spaces
- wrong exit code on partial failures

### Changed
- faster directory walking, fewer syscalls

## [0.3.0] - 2026-05-07

### Added
- 4xx fails fast; 429 and 5xx retry with jittered backoff

## [0.2.0] - 2026-05-17

### Added
- 4xx fails fast; 429 and 5xx retry with jittered backoff

## [0.1.0] - 2026-04-15

### Added
- first working version
