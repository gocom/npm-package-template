# Changelog

The changelog will also contain upcoming versions. Refer to tags, GitHub releases or npm registry for the latest
release.

## 0.2.1

* Fix `SKIP_PUBLISH` environment variable referencing in `npm-publish.yml`.

## 0.2.0

* Support trusted publishing from GitHub Actions CI.
* Update Node.js from 22 to 24.
* Tag the version with `prerelease` tag when publishing pre-releases from the CI. This fixes npm 11 compatibility, which no longer automatically sets tag for pre-releases.
* Updated `SonarSource/sonarqube-scan-action` action to version 6.
* Add `SKIP_PUBLISH` environment variable support to CI. Configuring it in the repository settings with value `true` will disable package publishing.

## 0.1.0

* Initial release.
