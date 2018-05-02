# Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

This CHANGELOG follows the format located [here](https://github.com/sensu-plugins/community/blob/master/HOW_WE_CHANGELOG.md)

## [Unreleased]

## [0.0.1] - 2018-05-02
### Security
- updated `yard` dependency to `~> 0.9.11` per: https://nvd.nist.gov/vuln/detail/CVE-2017-17042 which closes attacks against a yard server loading arbitrary files (@majormoses)

### Breaking Changes
- bumped dependency of `sensu-plugin` to 2.x you can read about it [here](https://github.com/sensu-plugins/sensu-plugin/blob/master/CHANGELOG.md#v200---2017-03-29) (@majormoses)
- dropped ruby 2.0 support (@majormoses)

### Added
- Basic Skel to be used to make new plugin repo setup easier.
- PR template
- Rubocop config
- basic testing setup

[Unreleased]: https://github.com/sensu-plugins/sensu-plugins-routeros/compare/0.0.1...HEAD
[0.0.1]: https://github.com/sensu-plugins/sensu-plugins-routeros/compare/42104a9443c472f5f96a028535488f4b5d3efe88...0.0.1
