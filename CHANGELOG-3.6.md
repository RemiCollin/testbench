# Change for 3.6

This changelog references the relevant changes (bug and security fixes) done to `orchestra/testbench`.

## 3.6.0

Released: 2018-02-08

### Added

* Added `Orchestra\Testbench\Database\MigrateProcessor`, to process realpath database migration instead of using `orchestra/database`.

### Changes

* Update support for Laravel Framework v5.6.
* Added `final`, scalar type-hint and scalar return type to internal methods, common extended methods remain the same for backward compatibilities.
