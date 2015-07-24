# Change Log
As with most npm modules, this project adheres to
[Semantic Versioning](http://semver.org/).

## [Unreleased][unreleased]
### Fixed
- Fix copyright and update maintainers in package.json.
- Fix links in HISTORY.md.

## [0.1.0] - 2015-07-24
### Added
- Silent mode (`-s`, `--silent`) which disables printing unimportant messages (#3, jadejs/jade#1905).

### Changed
- Hierarchy mode (`-H`, `--hierarchy`) is made the default.
- Both versions of Jade and the CLI are printed with `-V` or `--version`.
- Unescaped Unicode line and paragraph separators (`U+2028` and `U+2029`) is now allowed in the `-O` option only when the input is considered to be JSON (#5, jadejs/jade#1949).
- Non-JSON object files are allowed for the `-O` option as long as it can be parsed with the `eval()` function.

### Deprecated
- Since the hierarchy mode (`-H`, `--hierarchy`) is made the default, the
  option is now redundant and will be removed in 1.0.0.

### Fixed
- Capitalization in help message is kept consistent.
- Fix grammar error in the help message (by @didoarellano).
- Fix watch mode in more than one level of dependency hierarchy (jadejs/jade#1888).

## 0.0.1 - 2015-06-02
### Added
- Initial release.

[unreleased]: https://github.com/jadejs/jade-cli/compare/0.1.0...master
[0.1.0]: https://github.com/jadejs/jade-cli/compare/0.0.1...0.1.0
