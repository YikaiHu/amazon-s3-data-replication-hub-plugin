# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2020-09-30
### Added
- All files, initial version


## [1.0.1] - 2020-11-16
### Added
- Advanced options to control replication process, such as lambda memory, chunk size etc.
- Support of choosing different destination storage class

### Fixed
- Cloudformation parameters are not grouped and ordered

### Changed
- ECR image is now tagged with version number.


## [1.0.2] - 2020-12-06

### Changed
- Change to use CDK v1.74.0
- Reduce the number of logs generated.

### Added
- Add support of accessing s3 with no-sign-request

## [1.1.0] - 2020-12-06

### Changed
- Use custom provider to handling stack events

### Added
- Add support of triggering replication base on S3 Event.