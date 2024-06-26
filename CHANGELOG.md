# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.8.1] - 2024-05-29

### Changed

- Update `net-exporter` to 1.19.0.
- Update `external-dns-app` to 3.1.0.
- Update `cert-manager-app` to 3.7.5.
- Update `k8s-dns-node-cache-app` to 2.6.2.
- Update `teleport-kube-agent-app` to 0.9.0.

## [0.8.0] - 2024-04-24

### Changed

- Prefix `baseDomain` with cluster name if its missing for `external-dns` config.

## [0.7.0] - 2024-04-16

### Added

- Add `k8s-dns-node-cache` app.
- Add toleration for `uninitialized` nodes to the kyverno admission controller.

## [0.6.0] - 2024-03-20

### Added

- Included `teleport-kube-agent` app by default on EKS clusters.
- Add `security-bundle` app.
- Add `cilium-servicemonitors` app.

## [0.5.1] - 2024-02-13

### Added

- Include support for schemadocs to generate Chart README file

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

[Unreleased]: https://github.com/giantswarm/default-apps-eks/compare/v0.8.1...HEAD
[0.8.1]: https://github.com/giantswarm/default-apps-eks/compare/v0.8.0...v0.8.1
[0.8.0]: https://github.com/giantswarm/default-apps-eks/compare/v0.7.0...v0.8.0
[0.7.0]: https://github.com/giantswarm/default-apps-eks/compare/v0.6.0...v0.7.0
[0.6.0]: https://github.com/giantswarm/default-apps-eks/compare/v0.5.1...v0.6.0
[0.5.1]: https://github.com/giantswarm/default-apps-eks/compare/v0.5.0...v0.5.1
[0.5.0]: https://github.com/giantswarm/default-apps-eks/compare/v0.4.0...v0.5.0
[0.4.0]: https://github.com/giantswarm/default-apps-eks/compare/v0.3.1...v0.4.0
[0.3.1]: https://github.com/giantswarm/default-apps-eks/compare/v0.3.0...v0.3.1
[0.3.0]: https://github.com/giantswarm/default-apps-eks/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/giantswarm/default-apps-eks/compare/v0.1.2...v0.2.0
[0.1.2]: https://github.com/giantswarm/default-apps-eks/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/giantswarm/default-apps-eks/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/giantswarm/default-apps-eks/releases/tag/v0.1.0
