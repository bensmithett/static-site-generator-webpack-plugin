# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Changed
- Nothing yet.

## [2.0.0] - 2015-12-07
### Added
- Support for custom file names other than `index.html`

## [1.3.0] - 2015-12-01
### Added
- Support for ES2015 modules generated by Babel 6+.
- Validation that a render function is exported.

## [1.2.1] - 2015-11-27
### Fixed
- Ensure errors earlier in the compilation process are displayed correctly.

## [1.2.0] - 2015-10-06
### Added
- `webpackStats` to `locals` for advanced inspection of webpack's output.

### Fixed
- Windows support for webpack-dev-server
- Stack traces in error messages

## [1.1.2] - 2015-08-24
### Fixed
- Removed leading slashes from HTML paths so webpack-dev-server serves them correctly.

## [1.1.1] - 2015-08-24
### Fixed
- Show error message correctly for missing assets.

## [1.1.0] - 2015-08-19
### Added
- Support for named assets, allowing the use of hashed file names.
- Proper error handling so webpack dev server can recover from errors correctly.

## 1.0.0 - 2015-04-13
### Added
- Basic asynchronous path rendering

[Unreleased]: https://github.com/markdalgleish/static-site-generator-webpack-plugin/compare/v2.0.0...HEAD
[2.0.0]: https://github.com/markdalgleish/static-site-generator-webpack-plugin/compare/v1.3.0...v2.0.0
[1.3.0]: https://github.com/markdalgleish/static-site-generator-webpack-plugin/compare/v1.2.1...v1.3.0
[1.2.1]: https://github.com/markdalgleish/static-site-generator-webpack-plugin/compare/v1.2.0...v1.2.1
[1.2.0]: https://github.com/markdalgleish/static-site-generator-webpack-plugin/compare/v1.1.2...v1.2.0
[1.1.2]: https://github.com/markdalgleish/static-site-generator-webpack-plugin/compare/v1.1.1...v1.1.2
[1.1.1]: https://github.com/markdalgleish/static-site-generator-webpack-plugin/compare/v1.1.0...v1.1.1
[1.1.0]: https://github.com/markdalgleish/static-site-generator-webpack-plugin/compare/v1.0.0...v1.1.0
