# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.3.0] - 2026-11-04
### Added
- Detect VimL files from a `ft=vim` modeline on the first line ([#20](https://github.com/SalGnt/Sublime-VimL/issues/20)).

### Fixed
- Single-quoted strings spanning multiple lines with `\` continuation ([#11](https://github.com/SalGnt/Sublime-VimL/issues/11)).
- Variable names ending in `a` or `map` (e.g. `data`, `bitmap`) highlighted as commands ([#22](https://github.com/SalGnt/Sublime-VimL/issues/22)).

## [1.2.0] - 2025-01-27
### Added
- Highlight for `exrc` and `_exrc` files ([#21](https://github.com/SalGnt/Sublime-VimL/pull/21)).
- Highlight for `.nvimrc` files ([#21](https://github.com/SalGnt/Sublime-VimL/pull/21)).

## [1.1.0] - 2021-10-01
### Added
- Highlight for `_vimrc` and `_gvimrc` files ([#17](https://github.com/SalGnt/Sublime-VimL/issues/17), [#18](https://github.com/SalGnt/Sublime-VimL/pull/18)).

## [1.0.2] - 2021-06-05
### Fixed
- "Toggle Comment" not working as expected ([#15](https://github.com/SalGnt/Sublime-VimL/issues/15), [#16](https://github.com/SalGnt/Sublime-VimL/pull/16)).

## [1.0.1] - 2021-05-23
### Added
- Highlight for `vimrc` and `gvimrc` files ([#14](https://github.com/SalGnt/Sublime-VimL/pull/14)).

## [1.0.0] - 2021-01-06
### Added
- Sublime Text .sublime-syntax definition ([#13](https://github.com/SalGnt/Sublime-VimL/pull/13)).

### Removed
- TextMate .tmLanguage definition ([#13](https://github.com/SalGnt/Sublime-VimL/pull/13)).

## [0.1.5] - 2020-12-27
### Added
- Support for `syntax` keyword ([#12](https://github.com/SalGnt/Sublime-VimL/pull/12)).

### Changed
- Improve regex syntax pattern ([#12](https://github.com/SalGnt/Sublime-VimL/pull/12)).

## [0.1.4] - 2018-10-04
### Added
- Highlight for `.vimrc` files ([#9](https://github.com/SalGnt/Sublime-VimL/pull/9)).

### Fixed
- Hexadecimal numbers highlight conflict with autoload function ([#7](https://github.com/SalGnt/Sublime-VimL/issues/7), [#8](https://github.com/SalGnt/Sublime-VimL/pull/8)).

## [0.1.3] - 2016-08-12
### Added
- Support for `try ... catch ... finally ... endtry` ([#5](https://github.com/SalGnt/Sublime-VimL/pull/5)).
- Support for `:ab` ([#6](https://github.com/SalGnt/Sublime-VimL/pull/6)).

## [0.1.2] - 2015-02-25
### Changed
- Make regular expression strings more accurate ([#4](https://github.com/SalGnt/Sublime-VimL/pull/4)).

### Fixed
- Highlight problem on quoted strings ([#2](https://github.com/SalGnt/Sublime-VimL/pull/2), [#3](https://github.com/SalGnt/Sublime-VimL/issues/3), [#4](https://github.com/SalGnt/Sublime-VimL/pull/4)).

## [0.1.1] - 2015-02-25
### Added
- First release.


[Unreleased]: https://github.com/SalGnt/Sublime-VimL/compare/1.3.0...HEAD
[1.3.0]: https://github.com/SalGnt/Sublime-VimL/compare/1.2.0...1.3.0
[1.2.0]: https://github.com/SalGnt/Sublime-VimL/compare/1.1.0...1.2.0
[1.1.0]: https://github.com/SalGnt/Sublime-VimL/compare/1.0.2...1.1.0
[1.0.2]: https://github.com/SalGnt/Sublime-VimL/compare/1.0.1...1.0.2
[1.0.1]: https://github.com/SalGnt/Sublime-VimL/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/SalGnt/Sublime-VimL/compare/0.1.5...1.0.0
[0.1.5]: https://github.com/SalGnt/Sublime-VimL/compare/0.1.4...0.1.5
[0.1.4]: https://github.com/SalGnt/Sublime-VimL/compare/0.1.3...0.1.4
[0.1.3]: https://github.com/SalGnt/Sublime-VimL/compare/0.1.2...0.1.3
[0.1.2]: https://github.com/SalGnt/Sublime-VimL/compare/0.1.1...0.1.2
[0.1.1]: https://github.com/SalGnt/Sublime-VimL/releases/tag/0.1.1
