# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- Bump `cert-manager-app` app to 3.3.0.
- Bump `cert-exporter` app to 2.7.0.
- Bump `external-dns` app to 2.40.0.
- Bump `net-exporter` app to 1.17.1.
- Bump `node-exporter-app` app to 1.17.1.
- Bump `observability-bundle` app to 0.8.4.
- Bump `vertical-pod-autoscaler` app to 4.2.0.

### Fixed

- Enable cilium network policies for:
  - cert-manager
  - observability-bundle

## [0.1.2] - 2023-08-09

- Bump `external-dns` app.

## [0.1.1] - 2023-08-08

- Fix build for `default-apps-eks`.

## [0.1.0] - 2023-08-08

- Add `default-apps-eks` files.

[Unreleased]: https://github.com/giantswarm/default-apps-eks/compare/v0.1.2...HEAD
[0.1.2]: https://github.com/giantswarm/default-apps-eks/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/giantswarm/default-apps-eks/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/giantswarm/default-apps-eks/releases/tag/v0.1.0
