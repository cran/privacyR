# privacyR NEWS

## Version 1.0.0 (2024-11-09)

### Changes
- Fixed README.md to remove reference to DISCLAIMER file (CRAN compliance)
- Disclaimer text now only in README.md
- First stable release

## Version 0.1.1 (2024-11-07)

### Changes
- Package renamed from shadowR to privacyR to avoid CRAN name conflict
- Fixed LICENSE format for CRAN compliance
- Updated CDC HIPAA URL reference
- Added DISCLAIMER to .Rbuildignore

## Version 0.1.0 (Initial Release)

### Features
- Initial release of privacyR package
- `anonymize_id()` function for anonymizing patient identifiers
- `anonymize_names()` function for anonymizing patient names
- `anonymize_dates()` function with shift and round methods
- `anonymize_locations()` function with remove and generalize methods
- `anonymize_dataframe()` function for anonymizing entire data frames
- Comprehensive test suite using testthat
- Vignette with detailed examples and best practices
- Full roxygen2 documentation

