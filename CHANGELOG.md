# Change Log
All notable changes to this project will be documented in this file.

## [Unreleased]

### Added
- Property support for builders, i.e `textfield(customer.nameProperty)`

### Changed
- Rest client now uses PoolingHttpClientConnectionManager to support multiple threads
- HttpResponse.consume() never throws exception
- Build final name changed to `tornadofx-${version}` (https://github.com/edvin/tornadofx/issues/5) 

## [1.2.2] - 2015-02-08
- Recompiled for Kotlin RC