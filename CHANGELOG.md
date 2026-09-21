# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [SchemaVer](https://snowplow.io/blog/introducing-schemaver-for-semantic-versioning-of-schemas/).

## [1-0-3] - 2026-09-21

### Added
- "forever" flavor to supported game flavors

## [1-0-2] - 2025-12-08

### Added
- "titan" flavor to supported game flavors
- `$id` field to schema for canonical reference

## [1-0-1] - 2025-06-09

### Added
- "mists" flavor to supported game flavors

### Changed
- Reorganized repository structure (moved schema.json and examples to root)

## [1-0-0] - 2024-05-07

### Added
- Initial specification release
- Support for "mainline", "classic", "bcc", "wrath", and "cata" flavors
- JSONSchema draft 2020-12 validation

### Changed
- Made "classic" and "bcc" normative flavors (removed flavor aliases)
- Made `nolib` field required in releases
- Made `interface` field required in metadata
- Metadata items no longer allow additional properties
