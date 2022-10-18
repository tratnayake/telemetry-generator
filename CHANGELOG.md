# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.4] - 2012-10-18
### Added
Test a no-op
## [0.1.3] - 2012-10-18
### Added
* Update Dockerfile to make use of correct path for the `builder` binary (`s%/go/bin/opentelemetry-collector-builder%builder`)
## [0.1.2] - 2012-10-18
### Added
* Update the Dockerfile to build properly. s%github.com/open-telemetry/opentelemetry-collector-builder@v0.60.0%go.opentelemetry.io/collector/cmd/builder@v0.60.0

## [0.1.1] - 2012-10-18
### Added
* Make use of the proper {{github.ref_name}} value to get the proper image tag.

## [0.1.0] - 2012-10-18
### Added
* Initial support for versioning, adding and pushing tags.
* Included Github workflow for building and pushing an image.
