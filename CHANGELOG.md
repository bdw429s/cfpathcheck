# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [1.2.1] - 2016-11-05
### Updated
- glob@7.1.1
- lodash@4.16.6
- path-is-absolute@1.0.1
- eslint-plugin-node@3.0.3

### Added
- node v7 support in .travis.yml

## [1.2.0] - 2016-10-03
### Added
- Support for single quotes delimiting `<cfimport>` and `<cfinclude>` attributes.

## [1.1.1] - 2016-08-19
### Updated
- Dynamic paths built with concatenation now supported, and the path winds back to the last slash to find the directory

## [1.1.0] - 2016-08-17
### Added
- Support for `include` statements in `<cfscript>` tags.


## [1.0.0] - 2016-08-17
### Added
- CHANGELOG.md (this file).
- Code Climate badges.
- Some JSDoc annotations.

### Removed
- Node 0.10 support has been removed. cfpathcheck now needs at least node v4.

### Changed
- Finalise the eslint setup

## [0.7.1] - 2016-04-04
### Added
- TravisCI build badge.

## [0.7.0] - 2016-04-04
### Added
- Gruntfile for running tasks

### Changed
- Use new Verbalize API

### Removed
- Node 0.8 support.

## [0.6.1] - 2016-04-04
### Added

- grunt for task running.
- grunt-release for releasing tagged versions.

[1.2.1]: https://github.com/timbeadle/cfpathcheck/compare/1.2.0...1.2.1
[1.2.0]: https://github.com/timbeadle/cfpathcheck/compare/1.1.1...1.2.0
[1.1.1]: https://github.com/timbeadle/cfpathcheck/compare/1.1.0...1.1.1
[1.1.0]: https://github.com/timbeadle/cfpathcheck/compare/1.0.0...1.1.0
[1.0.0]: https://github.com/timbeadle/cfpathcheck/compare/0.7.1...1.0.0
[0.7.1]: https://github.com/timbeadle/cfpathcheck/compare/0.7.0...0.7.1
[0.7.0]: https://github.com/timbeadle/cfpathcheck/compare/0.6.1...0.7.0
[0.6.1]: https://github.com/timbeadle/cfpathcheck/commit/eb0693ee4e67dd1c03b47ec0b5a1c30f693750bd

(Sorry - only started tagging releases at 0.6.1)
