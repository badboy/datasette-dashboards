# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.1] - 2022-12-22
### Added
- Support for Python 3.11
- Update dependencies

## [0.2.0] - 2022-04-30
### Added
- Support for Python 3.10
- Renovatebot configuration

### Changed
- Mention the metric library in README.md (thanks @hydrosquall) (PR #20)
- Pin dev dependencies in Pipfile
- Update dependencies

### Removed
- Support for Python 3.6 (end of life)

## [0.1.6] - 2021-06-19
### Added
- Add dashboard filters feature

## [0.1.5] - 2021-05-23
### Fixed
- Fix query URI encoding in AJAX calls
- Fix Python packaging `setup.py`

## [0.1.4] - 2021-05-10
### Added
- Add standalone chart view from dashboard

### Changed
- BREAKING: `charts` property is now a dictionary
- BREAKING: removed `alias` property for charts
- BREAKING: dashboard layout is now using chart key identifiers from the `charts` property
- Set mobile layout breakpoint to 800px for better readability

## [0.1.3] - 2021-05-01
### Added
- Metric chart component

### Changed
- BREAKING: dashboard layout is now using chart identifiers using the `alias` property

## [0.1.2] - 2021-04-29
### Added
- Custom dashboard layout
- Markdown component

### Changed
- Design improvements

## [0.1.1] - 2021-04-25
### Fixed
- Add missing packages for test requirements in `setup.py`

### Changed
- BREAKING: update plugin metadata spec to be chart-library agnostic
- Update demo with choropleth map and interactive charts
- Update README.md

### Added
- Respect view-instance and execute-sql permissions
- More unit tests

## [0.1.0] - 2021-04-24
### Added
- Initial release of `datasette-dashboards`

[Unreleased]: https://github.com/rclement/datasette-dashboards/compare/0.2.1...HEAD
[0.2.1]: https://github.com/rclement/datasette-dashboards/compare/0.2.0...0.2.1
[0.2.0]: https://github.com/rclement/datasette-dashboards/compare/0.1.6...0.2.0
[0.1.6]: https://github.com/rclement/datasette-dashboards/compare/0.1.5...0.1.6
[0.1.5]: https://github.com/rclement/datasette-dashboards/compare/0.1.4...0.1.5
[0.1.4]: https://github.com/rclement/datasette-dashboards/compare/0.1.3...0.1.4
[0.1.3]: https://github.com/rclement/datasette-dashboards/compare/0.1.2...0.1.3
[0.1.2]: https://github.com/rclement/datasette-dashboards/compare/0.1.1...0.1.2
[0.1.1]: https://github.com/rclement/datasette-dashboards/compare/0.1.0...0.1.1
[0.1.0]: https://github.com/rclement/datasette-dashboards/releases/tag/0.1.0
