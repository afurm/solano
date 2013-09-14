
# Changelog


## Version History

v1.12.0 - Change `tddium run` to not enable CI for the suite by default (Use `tddium run --enable-ci` for the old behavior.)
v1.11.1 - Allow `tddium suite --delete` to take the branch name as a parameter.
v1.11.0 - Add --delete option to `tddium suite` command.  s/account/organization/g.
v1.10.0 - Allow specifying host, port, protocol, and noverify from CLI and environment variables
v1.9.1 - Properly route new suite creation to organizations (if the user belongs to multiple)
v1.9.0 - Support for Tddium Organizations: http://blog.tddium.com/2013/06/09/new-feature-organizations/
v1.8.1 - REE compatibility fixes
v1.8.0 - Send the latest commit on session creation
v1.7.6 - Fixes for bundler version detection
v1.7.5 - Honor bundler_version set in tddium.yml
v1.7.4 - Handle https repo URLs
v1.7.3 - Fix ssh config output format.
v1.7.2 - Re-release on github.com:solanolabs/tddium.git