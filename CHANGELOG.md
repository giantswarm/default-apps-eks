# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- Bump `observability-bundle` app to 1.2.1.

## [0.5.0] - 2024-02-05

## [0.4.0] - 2024-01-23

## Changed

- Add `cluster-autoscaler`.
- Use a YAML object for the apps configuration, so that defaults are not overwritten when users pass custom values.
- Change icon to square version.

## [0.3.1] - 2023-10-27

## Changed

- downgrade `vertical-pod-autoscaler`.

## [0.3.0] - 2023-10-27

### Changed

- Remove `hostNetwork` setting for `metrics-server`.
- Fetch AWS account ID automatically.

## [0.2.0] - 2023-10-12

### Added

- Added `chart-operator-extension` version `v1.1.1` that contains e.g. `ServiceMonitors` for `chart-operator`.

### Changed

- Bump `cert-manager-app` app to 3.4.0.
- Bump `cert-exporter` app to 2.7.0.
- Bump `external-dns` app to 2.42.0.
- Bump `metrics-server` app to 2.4.0.
- Bump `net-exporter` app to 1.18.0.
- Bump `node-exporter-app` app to 1.17.1.
- Bump `observability-bundle` app to 0.8.7.
- Bump `vertical-pod-autoscaler` app to 4.2.0.

### Fixed

- Enable cilium network policies for:
  - cert-manager
  - observability-bundle
- Fix metrics-server by setting `hostNetwork: true`

## [0.1.2] - 2023-08-09

- Bump `external-dns` app.

## [0.1.1] - 2023-08-08

- Fix build for `default-apps-eks`.

## [0.1.0] - 2023-08-08

- Add `default-apps-eks` files.

[Unreleased]: https://github.com/giantswarm/default-apps-eks/compare/v0.5.0...HEAD
[0.5.0]: https://github.com/giantswarm/default-apps-eks/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/giantswarm/default-apps-eks/compare/v0.3.1...v0.4.0
[0.3.1]: https://github.com/giantswarm/default-apps-eks/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/giantswarm/default-apps-eks/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/giantswarm/default-apps-eks/compare/v0.1.2...v0.2.0
[0.1.2]: https://github.com/giantswarm/default-apps-eks/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/giantswarm/default-apps-eks/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/giantswarm/default-apps-eks/releases/tag/v0.1.0
