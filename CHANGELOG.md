# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

```markdown
## [Unreleased] - YYYY-MM-DD

### Added
### Changed
### Deprecated
### Fixed
### Security
```

## [Unreleased] - YYYY-MM-DD

### Added
### Changed
- Migrated from deprecated `make-bowerbird-deps` and `make-bowerbird-libs` to unified `make-bowerbird-core`
- Converted all dependencies to use modern kwargs-based API (`bowerbird::core::git-dependency`)
- Simplified dependency bootstrap process with new bowerbird-loader pattern
### Deprecated
- Removed `bowerbird-libs` dependency (now consolidated into bowerbird-core)
### Fixed
- Wrapped the generation of the pre-push hook in an `ifndef` to avoid running the
  command multiple times during recursive make
### Security


## [0.1.0] - 2024-06-07

### Added
- Migrated the githooks targets to a separate repo.
- Added bowerbird dependencies for help and test.
- Migrated the test runner over to bowerbird test.
### Changed
- Explicitly disabled shell trace commands when creating the pre-push hook"
