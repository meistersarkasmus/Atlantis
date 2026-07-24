# Changelog

All notable changes to **Atlantis Firmware** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/)
and this project follows [Semantic Versioning](https://semver.org/).

---

## [Unreleased]

### Added
- *(Nothing yet)*

### Changed
- *(Nothing yet)*

### Fixed
- *(Nothing yet)*

---

## [v1.2] - 2026-07-24

### Added
- Adaptive capacitive touch engine
- Dynamic baseline tracking
- Touch energy smoothing
- Smooth center-out pulse animation
- Home Assistant integration
- WS2812 LED renderer
- ESPHome based firmware architecture

### Changed
- Touch sampling interval reduced to **20 ms**
- LED refresh interval optimized to **30 ms**
- Improved touch responsiveness
- Improved animation smoothness
- Cleaner internal touch processing

### Fixed
- Incorrect touch baseline initialization after startup
- Noise filtering for unstable touch values
- False touch detection caused by invalid startup readings
- Stable baseline adaptation during idle operation

---

## [v1.1]

### Added
- Center-out pulse animation
- Symmetric LED rendering
- Touch energy visualization

---

## [v1.0]

### Added
- Initial adaptive touch engine
- Dynamic baseline tracking
- Capacitive touch detection
