# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).


## [Unreleased][unreleased]

### Changed
- The otp module has been renamed oath.

### Removed
- The otp::c (oath::c) module is not public anymore.


## [0.5.1] - 2015-08-07
This release fixed a buffer overflow in the C-bindings tests. Because this issue did not influence the Rust part of the code in any way, the crate has not be updated.


## [0.5.0] - 2015-08-06

### Added
- C-bindings for OTP validation.

### Changed
- Errors are now represented by an enumeration instead of strings ;
- the C unit test suite has been rewritten.

### Fixed
- An integer overflow has been fixed in code length calculation.


## [0.4.2] - 2015-08-04
This release is a cleanup release. No public interface has been changed.


## [0.4.1] - 2015-08-03

### Added
- C-bindings are now part of this library and therefore no longer distributed in a separated project.


## [0.4.0] - 2015-08-01

Last version without a changelog.
