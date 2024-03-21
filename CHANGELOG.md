# Changelog

All notable changes to this project will be documented in this file, in reverse chronological order by release.
This file is automatically maintained by release-please.

## [3.0.0](https://github.com/mustanggb/BaconQrCode/compare/v2.0.6...v3.0.0) (2024-03-21)


### ⚠ BREAKING CHANGES

* drop support for PHP < 8.1

### Features

* add GD image renderer ([#171](https://github.com/mustanggb/BaconQrCode/issues/171)) ([c01758c](https://github.com/mustanggb/BaconQrCode/commit/c01758cc4bf2eb4225b92dae7d766c1a4b069185))
* drop support for PHP &lt; 8.1 ([2f1e117](https://github.com/mustanggb/BaconQrCode/commit/2f1e117289ad94cfa681ef092e17557f434b35e1))
* make utf-8 eci prefix configurable ([#130](https://github.com/mustanggb/BaconQrCode/issues/130)) ([1f3e1e9](https://github.com/mustanggb/BaconQrCode/commit/1f3e1e90222057fdc0fdadf2ec9c83a67d1fc03b))


### Bug Fixes

* correctly encode kanji bytes ([735e04e](https://github.com/mustanggb/BaconQrCode/commit/735e04e44c8a4544481f218dcea42dacebc2a09c))
* use non-locale aware format for scale and translate ([#100](https://github.com/mustanggb/BaconQrCode/issues/100)) ([788bb77](https://github.com/mustanggb/BaconQrCode/commit/788bb77af152abcb938dc8f0af4421084d78b949))
* **Version:** correct number of EC blocks for version 4 ([9298801](https://github.com/mustanggb/BaconQrCode/commit/92988018b8e3f960944945ae4b9ff158be403fc2))


### Miscellaneous Chores

* add test related files to .gitattributes ([3e68a9d](https://github.com/mustanggb/BaconQrCode/commit/3e68a9d37552e5c43c4fd801e66b41033153cba2))
* bump github action "codecov/codecov-action" 3 =&gt; 4 ([de6217a](https://github.com/mustanggb/BaconQrCode/commit/de6217abb28715a87b62fc104d06439df7df71ac))
* fix ci deprecations ([1e39f3b](https://github.com/mustanggb/BaconQrCode/commit/1e39f3b6eb67973b47ff63414a1807ae5c09c0b6))
* fix ci deprecations, run phpcs on php 8.2 ([#140](https://github.com/mustanggb/BaconQrCode/issues/140)) ([c6f79a4](https://github.com/mustanggb/BaconQrCode/commit/c6f79a46f3f0d9d18260f22f4ef5939932469559))
* remove non-required entries from CHANGELOG.md ([151a958](https://github.com/mustanggb/BaconQrCode/commit/151a9586b84738b9d7594149d162a3895e7f1e7e))

## 2.0.7 - 2022-03-14

### Fixed

- [#102](https://github.com/Bacon/BaconQrCode/issues/102) Fix internal path for CompositeEye

## 2.0.6 - 2022-02-04

### Fixed

- Added tests back into release package.

## 2.0.5 - 2022-01-31

### Fixed

- [#70](https://github.com/Bacon/BaconQrCode/issues/79) Fix Imagick backend gradient generation.

## 2.0.2 - 2020-07-30

### Changed

- [#71](https://github.com/Bacon/BaconQrCode/issues/71) Upgrade phpunit.
- [#71](https://github.com/Bacon/BaconQrCode/issues/71) Allow tests in vendor bundles for Debian packaging.
- [#71](https://github.com/Bacon/BaconQrCode/issues/71) Update TravisCI config file.

## 2.0.1 - 2020-07-14

### Fixed

- [#69](https://github.com/Bacon/BaconQrCode/pull/69) SimpleCircleEye Class not working properly.

## 2.0.0 - 2018-04-25

### Added

- [#25](https://github.com/Bacon/BaconQrCode/pull/25) allows for setting a more compact text output

- CHANGELOG.md added (how meta)

- Allows more complex shapes for modules

- Allows setting a gradient for the foreground

- Allows transparent backgrounds and alpha channel on all colors

### Changed

- Minimum PHP version changed to 7.1

- Imagick renderer now allows setting different output formats

- New optimized SVG renderer

### Deprecated

- Nothing.

### Removed

- Legacy ZF module support removed

### Fixed

- Non-release files are excluded from composer packages
