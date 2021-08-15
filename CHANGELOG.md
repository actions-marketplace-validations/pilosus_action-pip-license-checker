# Change Log

All notable changes to this project will be documented in this file.
This change log follows the conventions of [keepachangelog.com](http://keepachangelog.com/).

## [Unreleased]
### Fixed
- Nothing here yet

## [v0.2.0] - 2021-08-14
### Added
- Support `pip-license-checker` v0.21.0 with breaking changes,
  see [original CHANGELOG](https://github.com/pilosus/pip-license-checker/blob/main/CHANGELOG.md).
- Input `external` field to provide CSV files with package and license names.
- Input `no-external-csv-headers` field for external CSV files without header line.

## [v0.1.2] - 2021-07-11
### Fixed
- Output license check result for debugging
- Example usage extended with printing nicely formatted report
- Input `requirement` description fixed (default value)

## [v0.1.1] - 2021-07-10
### Added
- Changelog
- Readme disclaimer section

### Fixed
- Multiline output string formatting fixed as per the [workaround](https://github.community/t/set-output-truncates-multiline-strings/16852)

## v0.1.0 - 2021-07-10
### Added
- MVP


[Unreleased]: https://github.com/pilosus/pip-license-checker/compare/v0.2.0...HEAD
[v0.2.0]: https://github.com/pilosus/pip-license-checker/compare/v0.1.2...v0.2.0
[v0.1.2]: https://github.com/pilosus/pip-license-checker/compare/v0.1.1...v0.1.2
[v0.1.1]: https://github.com/pilosus/pip-license-checker/compare/v0.1.0...v0.1.1