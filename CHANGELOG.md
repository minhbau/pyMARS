# Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/)
and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]


## [1.0.0] - 2019-06-21

### Added

- Added path flux analysis, so methods now include DRG, DRGEP, PFA, and sensitivity analysis
- Adds test suite for all current methods
- Adds Travis CI and AppVeyor continuous integration
- Added testing on Windows systems via Azure Pipelines
- Added printing support for chemically activated and Chebyshev reactions, and non-Troe falloff
- Adds Travis-based package deploy to PyPI and Anaconda
- Adds initial documentation site

### Changed

- Major code restructuring.
- Now supports Python 3.6+

### Fixed

- Fixed bugs in setup.py script and path imports 
- Fixed model printing of Plog reactions

## [0.0.1] - 2017-04-01

### Added

- Added preliminary project files (README, CODE_OF_CONDUCT, etc.) without any actual source code


[Unreleased]: https://github.com/Niemeyer-Research-Group/pyMARS/compare/v1.0.0...HEAD
[1.0.0]: https://github.com/Niemeyer-Research-Group/pyMARS/compare/v0.1.0...v1.0.0
[0.1.0]: https://github.com/Niemeyer-Research-Group/pyMARS/compare/v0.0.1...v0.1.0