# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Added

- `remote_options` context manager for managing Ray remote options for a task - [#54](https://github.com/PrefectHQ/prefect-ray/pull/54)

### Changed

### Deprecated

### Removed

### Fixed

### Security

## 0.2.0

Released September 8th, 2022

### Added
- `pickle5` requirement for Python < 3.8 users - [#30](https://github.com/PrefectHQ/prefect-ray/pull/30).

### Fixed
- Updated `RayTaskRunner` to be compatible with the updated `TaskRunner` interface in the Prefect Core library (v2.3.0) - [#35](https://github.com/PrefectHQ/prefect-ray/pull/35)

## 0.1.4

Released on August 2nd, 2022.

### Added
- `pickle5` requirement for Python < 3.8 users - [#30](https://github.com/PrefectHQ/prefect-ray/pull/30).

## 0.1.3

Released on July 26th, 2022.

### Changed

- Dropping x86_64 requirement so ray can be automatically installed - [#29](https://github.com/PrefectHQ/prefect-ray/pull/29).
- Examples to better exemplify parallelism - [#29](https://github.com/PrefectHQ/prefect-ray/pull/29).

## 0.1.2

Released on July 20th, 2022.

### Changed

- Updated tests to be compatible with core Prefect library (v2.0b9) and bumped required version - [#20](https://github.com/PrefectHQ/prefect-ray/pull/20)

## 0.1.1

Released on July 8th, 2022.

### Changed

- Updated `RayTaskRunner` to be compatible with core Prefect library (v2.08b) - [#18](https://github.com/PrefectHQ/prefect-ray/pull/18)

## 0.1.0

Released on June 7th, 2022.

### Added

- Migrated `RayTaskRunner` from core Prefect library - [#7](https://github.com/PrefectHQ/prefect-ray/pull/7)
- Expanded documentation and corrections to docstrings [#9](https://github.com/PrefectHQ/prefect-ray/pull/9)
