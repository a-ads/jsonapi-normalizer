# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [2.0.2] - 2026-05-30

### Added
- `meta` objects are now preserved. A top-level `meta` is exposed on the normalized output, and per-resource `meta` is included on each entity.

## [2.0.1] - 2018-07-21

### Fixed
- An ES6 module is now properly exported.

## [2.0.0] - 2018-07-21

### Changed
- **Breaking change**: The `results` key now only contains entities that were returned inside the JSONAPI `data` field. (#12)

[2.0.2]: https://github.com/stevenpetryk/jsonapi-normalizer/compare/v2.0.1...v2.0.2
[2.0.1]: https://github.com/stevenpetryk/jsonapi-normalizer/compare/v2.0.0...v2.0.1
[2.0.0]: https://github.com/stevenpetryk/jsonapi-normalizer/compare/v1.2.0...v2.0.0
