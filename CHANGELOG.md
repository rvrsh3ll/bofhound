# Changelog
## [v0.1.1] - 8/11/2022
### Fixed
- Bug where domain trusts queried more than once would appear duplicated in the BH UI

## [v0.1.0] - 6/9/2022
### Added
- Parsing support for Group Policy Objects
- Parsing support for Organizational Unit objects
- Parsing support for Trusted Domain objects

### Fixed
- Bug causing crash when handling non-base64 encoded SchemaIDGUID/nTSecurityDescriptor attributes

## [v0.0.1] - 5/9/2022
### Added
- Prepped for initial release and PyPI package