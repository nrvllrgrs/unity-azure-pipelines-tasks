# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.0]

- Added option for batch mode

## [1.1.0]

### Added

- Added timestamp to generated log files
- Added log output while running the task
- Added output variable `logsOutputPath` pointing to the directory containing all generated logs

### Changed

- Performance and optimization changes

## Removed

- Removed `specifyLogFile` option. A log file is now always created and used to stream log to the DevOps console
- Removed `logFileName` option. The file's name is now always `UnityTestLog.log` with a timestamp included
- Removed `editorLogFilePath` output variable. Please use `logsOutputPath` instead
- Removed custom command lines mode. Please use the new `Unity CMD` task instead

## [1.0.1]

### Fixed

- Fixed missing *.js files error

## [1.0.0]

Initial release