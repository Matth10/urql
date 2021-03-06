# @urql/preact

## 1.1.5

### Patch Changes

- Add graphql@^15.0.0 to peer dependency range, by [@kitten](https://github.com/kitten) (See [#688](https://github.com/FormidableLabs/urql/pull/688))
- Forcefully bump @urql/core package in all bindings and in @urql/exchange-graphcache.
  We're aware that in some cases users may not have upgraded to @urql/core, even though that's within
  the typical patch range. Since the latest @urql/core version contains a patch that is required for
  `cache-and-network` to work, we're pushing another patch that now forcefully bumps everyone to the
  new version that includes this fix, by [@kitten](https://github.com/kitten) (See [#684](https://github.com/FormidableLabs/urql/pull/684))
- Updated dependencies (See [#688](https://github.com/FormidableLabs/urql/pull/688) and [#678](https://github.com/FormidableLabs/urql/pull/678))
  - @urql/core@1.10.8

## 1.1.4

### Patch Changes

- ⚠️ Fix node resolution when using Webpack, which experiences a bug where it only resolves
  `package.json:main` instead of `module` when an `.mjs` file imports a package, by [@JoviDeCroock](https://github.com/JoviDeCroock) (See [#642](https://github.com/FormidableLabs/urql/pull/642))
- Updated dependencies (See [#642](https://github.com/FormidableLabs/urql/pull/642))
  - @urql/core@1.10.4

## 1.1.3

### Patch Changes

- ⚠️ Fix Node.js Module support for v13 (experimental-modules) and v14. If your bundler doesn't support
  `.mjs` files and fails to resolve the new version, please double check your configuration for
  Webpack, or similar tools, by [@JoviDeCroock](https://github.com/JoviDeCroock) (See [#637](https://github.com/FormidableLabs/urql/pull/637))
- Updated dependencies (See [#637](https://github.com/FormidableLabs/urql/pull/637))
  - @urql/core@1.10.3

## 1.1.2

### Patch Changes

- Bumps the `@urql/core` dependency minor version to ^1.10.1 for React, Preact and Svelte, by [@JoviDeCroock](https://github.com/JoviDeCroock) (See [#623](https://github.com/FormidableLabs/urql/pull/623))
- Updated dependencies (See [#621](https://github.com/FormidableLabs/urql/pull/621))
  - @urql/core@1.10.2

## 1.1.1

### Patch Changes

- Switch over to using @urql/core package (See [`75323c0`](https://github.com/FormidableLabs/urql/commit/75323c0))
- Updated dependencies (See [#533](https://github.com/FormidableLabs/urql/pull/533), [#519](https://github.com/FormidableLabs/urql/pull/519), [#515](https://github.com/FormidableLabs/urql/pull/515), [#512](https://github.com/FormidableLabs/urql/pull/512), and [#518](https://github.com/FormidableLabs/urql/pull/518))
  - @urql/core@1.9.0

## 1.1.0

- Update urql to 1.8.0
- Update wonka to 4.0.0 (and incorporate breaking changes)
