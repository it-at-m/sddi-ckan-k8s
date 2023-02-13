# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).
Versions are prefixed with `sddi-ckan-` due to usage of
[chart-releaser-action](https://github.com/helm/chart-releaser-action).
For releases `< 1.0.0` minor version step indicate breaking changes.

## [sddi-ckan-0.3.1] - 2023-02-09

### Added

- Expose `beaker.session.key` config option
- Add some defaults for enabling/disabling subcharts

### Fixed

- Fixed wrong indent of `session.*` in CKAN `values.yml`

### Security

### Deprecated

## [sddi-ckan-0.3.0] - 2023-02-09

### Added

- Allow configure or auto-generation of [`beaker.session.secret`](https://docs.ckan.org/en/latest/maintaining/configuration.html#beaker-session-secret)

### Change

- Changed CKAN default Docker image to [ckan docker SDDI repo](https://github.com/tum-gis/ckan-docker/)

## [sddi-ckan-0.2.2] - 2023-02-09

### Added

- Exposed `ckan.site_intro_text`, `ckan.site_about` and `ckan.activity_streams_enabled`

### Fixed

- Expose CKAN [smtp_reply_to](https://docs.ckan.org/en/2.9/maintaining/configuration.html#smtp-reply-to) in env var
- Fixed env var `CKAN__DATAPUSHER__FORMATS`

## [sddi-ckan-0.2.1] - 2023-02-08

### Added

- Expose CKAN [smtp_reply_to](https://docs.ckan.org/en/2.9/maintaining/configuration.html#smtp-reply-to)
  in `values.yml`

### Changed

- Docs updates

## [sddi-ckan-0.2.0] - 2023-01-31

### Changed

- Minor docs changes
- Minor changes to default config

## [sddi-ckan-0.1.0] - 2023-01-31

- Initial release to helm repo

### Changed

- Use Solr image with spatial support: `ckan/ckan-solr:2.9-solr8` -> `ckan/ckan-solr:2.9-solr8-spatial`

## [template] - YYYY-MM-DD

### Added

### Changed

### Removed

### Fixed

### Security

### Deprecated

[sddi-ckan-0.3.1]: https://github.com/tum-gis/sddi-ckan-k8s/compare/sddi-ckan-0.3.0...sddi-ckan-0.3.1
[sddi-ckan-0.3.0]: https://github.com/tum-gis/sddi-ckan-k8s/compare/sddi-ckan-0.2.2...sddi-ckan-0.3.0
[sddi-ckan-0.2.2]: https://github.com/tum-gis/sddi-ckan-k8s/compare/sddi-ckan-0.2.1...sddi-ckan-0.2.2
[sddi-ckan-0.2.1]: https://github.com/tum-gis/sddi-ckan-k8s/compare/sddi-ckan-0.2.0...sddi-ckan-0.2.1
[sddi-ckan-0.2.0]: https://github.com/tum-gis/sddi-ckan-k8s/compare/sddi-ckan-0.1.0...sddi-ckan-0.2.0
[sddi-ckan-0.1.0]: https://github.com/tum-gis/sddi-ckan-k8s/releases/tag/sddi-ckan-0.1.0
[template]: https://keepachangelog.com/en/1.0.0/