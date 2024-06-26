# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.2.0] - 2024-05-24

### Changed

- Move all `.global` values to `.global.ingressSLA`.

### Fixed

- Allow root level additional properties in schema.
- Allow additional properties under `.global` in schema.
- Set default `prometheus-blackbox-exporter` selector to include `clusterID` in the `app.kubernetes.io/instance` label.

## [0.1.0] - 2024-05-24

- First release.

[Unreleased]: https://github.com/giantswarm/ingress-sla-app/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/giantswarm/ingress-sla-app/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/giantswarm/ingress-sla-app/releases/tag/v0.1.0
