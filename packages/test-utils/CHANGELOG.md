# @udecode/plate-test-utils

## 5.3.6

### Patch Changes

- [#1150](https://github.com/udecode/plate/pull/1150) [`8e7ece4c`](https://github.com/udecode/plate/commit/8e7ece4ceb48d5715e9a6c33fb6fb9b1f1e2b9f0) Thanks [@jeffsee55](https://github.com/jeffsee55)! - Fixes dependencie issue for React<17 users by using the classic `React.createElement` function rather than the newer `jsx-runtime` transform.

  Per babel docs: https://babeljs.io/docs/en/babel-preset-react#with-a-configuration-file-recommended

## 3.2.0

### Minor Changes

- [#995](https://github.com/udecode/plate/pull/995) [`58387c6d`](https://github.com/udecode/plate/commit/58387c6d34e86be7880999b40a9105b6178f4ce4) Thanks [@dylans](https://github.com/dylans)! - update slate dependencies and peerDependencies to 0.66.\*

### Patch Changes

- [#995](https://github.com/udecode/plate/pull/995) [`5eb42cdd`](https://github.com/udecode/plate/commit/5eb42cdd47db4fd41936420b86b0bf7df9a8aa09) Thanks [@dylans](https://github.com/dylans)! - update to slate 0.66.x

## 1.0.0

### Major Changes

🎉 The **Slate Plugins** project has evolved to **Plate** 🎉

To migrate, install `@udecode/plate[-x]` then find and replace all
occurrences of:

- `slate-plugins` to `plate`
- `SlatePlugins` to `Plate`
- `SlatePlugin` to `PlatePlugin`
