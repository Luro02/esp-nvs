# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.1.3] - 2025-12-14

### Bug Fixes

- Write_aligned fails when buf.len() < T::WRITE_SIZE


## [0.1.2] - 2025-12-10

### Bug Fixes

- Bool get returning always true

### Other

- Tune git-cliff config so there are two newlines between versions


## [0.1.1] - 2025-11-21

### Bug Fixes

- Fix broken debug logs in tests
- Fix overwriting blobs multiple times

### Miscellaneous Tasks

- Fix lint and typo in tests


## [0.1.0] - 2025-11-21

### Features

- Add trace logs to facilitate debugging on actual hardware

### Bug Fixes

- Expose key internal representation
- Ensure that the flash access is aligned
- Invalid item indices in NVS initialization

### Other

- Add defmt feature to linter recipe
- Add git-cliff config
