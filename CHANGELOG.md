# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- Added enum to `order:status` as defined in the README before.

## [v1.1.0] - 2023-01-06

### Changed

- All timestamps must be in UTC ([#1095](https://github.com/radiantearth/stac-spec/issues/1095))

### Deprecated

- Deprecated `order:expiration_date` in favor of `expires`

### Fixed

- Clarify that `order:date` is the submission time
- Clarify that all timestamps must be formatted according to RFC3339.
- Clarify the relation to common metadata and timestamps extension by giving guidance on how to use the fields.

## [v1.0.0] - 2022-08-18

- Initial release of the STAC Order Extension.

[Unreleased]: <https://github.com/stac-extensions/order/compare/v1.2.0...HEAD>
[v1.1.0]: <https://github.com/stac-extensions/order/compare/v1.0.0...v1.1.0>
[v1.0.0]: <https://github.com/stac-extensions/order/tree/v1.0.0>
