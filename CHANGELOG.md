# Changelog

All changes that are relevant to `cargo-sweep` users should be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- No longer give a hard error when a custom toolchain gives an error [#67](https://github.com/holmgr/cargo-sweep/pull/67)
- Don't print colors when stdout is not a terminal [#69](https://github.com/holmgr/cargo-sweep/pull/69)
- Make `-r/--recursive` traverse beyond Cargo directories [#78](https://github.com/holmgr/cargo-sweep/pull/78)
- Reduce non-verbose output to make it less noisy [#81](https://github.com/holmgr/cargo-sweep/pull/81)
- Refactor and add `-m` as a short flag for `--maxsize` [#87](https://github.com/holmgr/cargo-sweep/pull/87)
- Only show toolchain list once when using `--installed` [#88](https://github.com/holmgr/cargo-sweep/pull/88)
- Support multiple projects as input via CLI [#101](https://github.com/holmgr/cargo-sweep/pull/101)

### Fixed

- When rustc fails, show stderr if stdout is empty [#63](https://github.com/holmgr/cargo-sweep/pull/63)
- Kibibytes are now printed as `KiB`, not `kiB` [#69](https://github.com/holmgr/cargo-sweep/pull/69)
- Exit with non-zero status on failure [#72](https://github.com/holmgr/cargo-sweep/pull/72)
- Keep stamp file on dry run [#100](https://github.com/holmgr/cargo-sweep/pull/100)

## **0.6.2** and prior

Not documented, `CHANGELOG.md` was introduced after **0.6.2**.
