# Graphiant SDK Python Changelog

All notable changes to the Graphiant SDK Python package will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [25.12.1] - 2025-12-17

### Added
- **CI/CD:**
  - Added Git tag and GitHub release creation to release workflow
  - Added `create_tag` input option to release workflow (default: true)
  - Enhanced PyPI upload error handling with verbose mode and detailed diagnostics
  - Added token validation and length checking in release workflow
  - Release workflow now gracefully handles existing tags and releases (no failure on re-run)
- **Testing:**
  - Added support for Graphiant API credentials in test workflow via GitHub secrets/variables
  - Test workflow now reads `GRAPHIANT_HOST`, `GRAPHIANT_USERNAME`, `GRAPHIANT_PASSWORD` from secrets/variables
  - Integration tests (e.g., `test_sanity.py`) will run when credentials are configured
- **Documentation:**
  - Added CHANGELOG.md references in README.md documentation and support sections

### Changed
- **Version:**
  - Updated package version from 25.11.1 to 25.12.1
  - Updated API documentation reference to `graphiant_api_docs_v25.12.1.json`
- **CI/CD:**
  - Updated release workflow permissions to `contents: write` (required for tag/release creation)
  - Added `fetch-depth: 0` to checkout step for git tag operations
  - Improved PyPI upload error messages with troubleshooting guidance
  - Release workflow now uses GitHub API to check for existing releases before creating new ones
  - Tag creation step now skips creation if tag already exists instead of failing

### Fixed
- Fixed import issues for models not exported from main package:
  - `V1GroupsIdMembersPostResponse` - now imported directly from module
  - `V1AuthPutResponse` - now imported directly from module
- Enhanced error handling in release workflow for better debugging
- Fixed release workflow to prevent failures when tags or releases already exist (idempotent behavior)

## [25.11.1] - 2025-11-11

### Added
- **API Specification:**
  - Major API specification optimization and schema reuse
  - Reduced specification file size from 9.8M to 1.5M (~85% reduction)
  - Enhanced API documentation with more comprehensive descriptions

### Changed
- **Breaking Changes:**
  - Response class names no longer include HTTP status codes
    - `Post200Response` → `PostResponse`
    - `Get200Response` → `GetResponse`
    - `Put202Response` → `PutResponse`
    - `Put204Response` → `PutResponse`
    - `Post201Response` → `PostResponse`
  - Inner classes now use reusable schema names across different endpoints
  - Common schemas share the same inner class names for better code reuse
- **Documentation:**
  - Added comprehensive migration guide from 25.10.2 to 25.11.1
  - Updated README with migration instructions and examples
  - Enhanced documentation for finding endpoint request/response models

### Migration Notes
- See [README.md](README.md#-migration-guide-upgrading-from-25102-to-25111) for detailed migration instructions
- Most response classes have been updated; check API documentation for exceptions
- Inner class names have changed - refer to model documentation files for new names

## [25.10.2] - 2025-10-13

### Changed
- Updated API specification to version 25.10.2

## [25.10.1] - 2025-10-08

### Changed
- Updated API specification to version 25.10.1

## [25.9.2] - 2025-09-25

### Changed
- Updated API specification to version 25.9.2

## [25.9.1] - 2025-09-23

### Changed
- Updated API specification to version 25.9.1

## [25.8.1] - 2025-08-22

### Changed
- Updated API specification to version 25.8.1

## [25.7.1] - 2025-07-18

### Changed
- Updated API specification to version 25.7.1

## [25.6.2] - 2025-06-13

### Changed
- Updated API specification to version 25.6.2

## [25.6.1] - 2025-06-02

### Changed
- Updated API specification to version 25.6.1

---

## Release Notes Format

Each release includes:
- **Added**: New features, endpoints, or capabilities
- **Changed**: Changes in existing functionality
- **Deprecated**: Features that will be removed in future versions
- **Removed**: Removed features or endpoints
- **Fixed**: Bug fixes
- **Security**: Security-related changes

For detailed API changes, refer to the API documentation files in the `docs/` directory.
