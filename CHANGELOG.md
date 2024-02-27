# Changelog

## 4.0.0

- Move stylelint to `peerDependencies`
- Upgrade stylelint to ^16.2.0
  This has required the package to move to ESM as required by stylelint
  https://stylelint.io/migration-guide/to-16/#deprecated-commonjs-api

## 3.0.1

- Update postcss-bem-linter to ^4.0.1

## 3.0.0

- Update postcss-bem-linter to ^4.0.0
- Update stylelint to ^15.9.0 - BREAKING CHANGE
  - Drops support for Node 12

## 2.1.1

- Bump dependencies to resolve warnings [#56](https://github.com/simonsmith/stylelint-selector-bem-pattern/pull/56)

## 2.1.0

- Supports `implicitUtilities` [#38](https://github.com/simonsmith/stylelint-selector-bem-pattern/pull/38)

## 2.0.0

- Update `postcss-bem-linter` to `3.0.0`. See
  [https://github.com/postcss/postcss-bem-linter/releases/tag/3.0.0](release
  notes)

## 1.1.1

- Support `ignoreCustomProperties`.
- Use `root` for `implicitComponents` warning if no `node` is in the warning.

## 1.1.0

- Supports `implicitComponents`.

## 1.0.0

- Namespace rule name.

## 0.2.3

- Move PostCSS from `devDependencies` to `dependencies`.

## 0.2.2

- Remove code for default options that didn't work anyway.

## 0.2.1

- Fix option-validating bug that errored when `presetOptions` were passed.

## 0.2.0

- Upgrade to stylelint v3; use `stylelint.createPlugin()`.

## 0.1.0+

- Initial experimentation.
