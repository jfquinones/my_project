# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Fixed

- Patch

## 0.1.1 - 2023-05-05

- Patch some github workflows

### Changed

- Using {{echo "{name}={value}" >> $GITHUB_OUTPUT}} instead of {{echo "::save-state name={name}::{value}"}} in github workflows because it will be deprecated
- The version of actions/checkout was changed from @v2 to @v3 because NodeJS12 will not be supported anymore soon

## 0.1.0 - 2023-05-05

### Added

- First Release
