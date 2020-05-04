**See [the release process docs](docs/howtos/cut-a-new-release.md) for the steps to take when cutting a new release.**

# Unreleased Changes

[Full Changelog](https://github.com/mozilla/application-services/compare/v0.58.2...master)

## FxA Client
- iOS: Added optional boolean argument `forceRefresh` to ignore caching for `fetchDevices`.
- Added an optional `ttl` parameter to `getAccessToken` to limit the lifetime of the token. ([#3066](https://github.com/mozilla/application-services/pull/3066))
- Android: Added option boolean argument `ignoreCache` to ignore caching for `getDevices`.
- Added an optional `ttl` parameter to `getAccessToken` to limit the lifetime of the token. ([#3066](https://github.com/mozilla/application-services/pull/3066))