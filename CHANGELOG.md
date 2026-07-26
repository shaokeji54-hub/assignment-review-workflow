# Changelog

All notable changes to this skill are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.0] - 2026-07-24

### Added

- File classifier at workflow entry: 5-type categorization with branched processing pipelines
- Version quality anchors: minimum standards per version (v1-v4) to prevent quality degradation in batch operations
- Processing mode selection: explicit choice among full-coverage, curated-depth, and mixed-batch at task start
- Visualization advisory field: optional assessment criteria in analysis notes, not a mandatory version round
- Group assignment desensitization rules: multi-person name mapping (A/B/C) with cross-file consistency

### Changed

- Processing pipeline now adapts to file type rather than applying uniform processing to all inputs
- Version iteration governed by quality anchors instead of fixed four-round template

### Fixed

- Classification logic: engineering designs and lab reports now get technical review instead of literary analysis

## [1.0.0] - 2026-07-24

### Added

- Initial skill definition: assignment re-review workflow
- Dual-version output system: academic (A) and non-academic (B) versions
- Four-round iterative deepening framework (v1 through v4)
- Personal information sanitization rules (names, student IDs)
- Standardized file naming convention with version tracking
- Pillow-based image generation guidelines for visual assets
- AGENTS.md configuration for AI-assisted workflow

[1.1.0]: https://github.com/shaokeji54-hub/skills/releases/tag/assignment-review-workflow-v1.1.0
[1.0.0]: https://github.com/shaokeji54-hub/skills/releases/tag/assignment-review-workflow-v1.0.0
