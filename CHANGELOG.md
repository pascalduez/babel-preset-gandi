# Change log

## [Unreleased]

## 2.0.0 - 2017-11-07
### Changed
  - Switch to `babel-preset-env`.
    Remove duplicate or unused transform plugins.

## 2016-10-10
### Changed
  - Enable babel-runtime transform `polyfill` option to polyfill built-ins such as Promise, Set, Symbol etc,
    without polluting the global scope or duplicating helpers.
    https://babeljs.io/docs/plugins/transform-runtime/#technical-details

## 2016-08-24
### Added
  - Add the support of Flow.

## 2016-06-27
### Added
  - Add transform-runtime plugin, allows to not duplicate polyfill transforms.
    Requires babel-runtime as a dependency of your app and a devDependency of your lib.

## 2016-06-09
### Added
  - Adds async keyword support.

## 2016-06-07
### Added
  - Add "babel-plugin-transform-object-assign" to ponyfill Object.assign.

## 2016-03-17
### Fixed
  - Fix transformers order as reported in
    [loganfsmyth/babel-plugin-transform-decorators-legacy#24
    ](https://github.com/loganfsmyth/babel-plugin-transform-decorators-legacy/issues/24)

## 2016-02-23
### Added
  - Add "babel-plugin-syntax-trailing-function-commas" to support args function trailing commas.
  - Add "babel-preset-es2015"
  - Add "babel-preset-react"
  - Add "babel-preset-react-hmre"
  - Add "babel-plugin-react-transform"

## 2016-01-22
### Added
  - Initial commit.
