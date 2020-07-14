# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2020-07-14

Initial release after fork.

### Changed

- Updated all packages
- Updated build process
- Decode strings using UTF-8 if possible (https://github.com/schmich/instascan/pull/248/files)
- Reuse decodeCallback (https://github.com/schmich/instascan/pull/230)
- Avoid asking for permissions twice (https://github.com/schmich/instascan/pull/213)
- Fixed video not playing on iOS 11 and above (https://github.com/schmich/instascan/pull/207)
- Correctly select camera when starting scanner (https://github.com/schmich/instascan/pull/183)
