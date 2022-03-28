# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.1] - 2022-03-28

### Changed

- Switch from the official `docker.io/jimmidyson/configmap-reload` image to `ghcr.io/prometheus-operator/prometheus-config-reloader` to avoid Docker Hub's rate limits.
- Remove `cluster.local` suffix from URLs so that it doesn't conflict with clusters that use a different domain name.

## [1.0.0] - 2022-03-22

Initial release

[unreleased]: https://github.com/karavel-io/platform-component-prometheus/compare/1.0.1...HEAD
[1.0.1]: https://github.com/karavel-io/platform-component-prometheus/compare/1.0.0...1.0.1
[1.0.0]: https://github.com/karavel-io/platform-component-prometheus/releases/tag/1.0.0
