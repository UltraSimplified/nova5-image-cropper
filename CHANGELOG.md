# Release Notes
## [v2.3.2](https://github.com/ultrasimplified/nova5-image-cropper/compare/v2.3.1...v2.3.2)

### Fixed

- `resize()` now scales images down keeping their aspect ratio, and never enlarges them. It called Intervention Image 3 with the v2 constraint callback, which v3 ignores, so uploads were forced to the given width at their original height - stretched rather than scaled.

> Released 2026/10/20

## [v.2.3.1](https://github.com/ultrasimplified/nova5-image-cropper/compare/v2.3.0...v2.3.1)

### Added

— Enabled indexWidth attribute to override image display

## [v2.3.0](https://github.com/ultrasimplified/nova5-image-cropper/compare/2.2.3...v2.3.0)

### Added

- Reintroduced convert function - pass a filetype ('png', 'jpeg', 'webp') to convert the uploaded image to the desired format

> Released 2024/12/27

### 2.2.3 Added

- Minor updates to code for PHP 8.4 / Nova 5 compatibility
- Update intervention/image to v.3.1

> Released 2024/12/26

### Derived from the excellent work of Clément Tessier and Stef van Esch

## [v1.1.0](https://github.com/ctessier/nova-advanced-image-field/compare/v1.0.2...v1.1.0)

## [v2.1.1](https://github.com/ctessier/nova-advanced-image-field/releases/tag/v2.1.0)
