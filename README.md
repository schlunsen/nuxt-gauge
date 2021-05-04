# nuxt-gauge

[![npm version][npm-version-src]][npm-version-href]
[![npm downloads][npm-downloads-src]][npm-downloads-href]
[![Github Actions CI][github-actions-ci-src]][github-actions-ci-href]
[![Codecov][codecov-src]][codecov-href]
[![License][license-src]][license-href]

> Nuxt module using vue-gauge

[📖 **Release Notes**](./CHANGELOG.md)

## Setup

1. Add `nuxt-gauge` dependency to your project

```bash
yarn add nuxt-gauge # or npm install nuxt-gauge
```

2. Add `nuxt-gauge` to the `modules` section of `nuxt.config.js`

```js
{
  modules: [
    // Simple usage
    'nuxt-gauge',

    // With options
    ['nuxt-gauge', { /* module options */ }]
  ]
}
```

## Development

1. Clone this repository
2. Install dependencies using `yarn install` or `npm install`
3. Start development server using `npm run dev`

## License

[MIT License](./LICENSE)

Copyright (c) Rasmus Schlünsen <rasmus@schlunsen.com>

<!-- Badges -->
[npm-version-src]: https://img.shields.io/npm/v/nuxt-gauge/latest.svg
[npm-version-href]: https://npmjs.com/package/nuxt-gauge

[npm-downloads-src]: https://img.shields.io/npm/dt/nuxt-gauge.svg
[npm-downloads-href]: https://npmjs.com/package/nuxt-gauge

[github-actions-ci-src]: https://github.com/schlunsen/nuxt-gauge/workflows/ci/badge.svg
[github-actions-ci-href]: https://github.com/schlunsen/nuxt-gauge/actions?query=workflow%3Aci

[codecov-src]: https://img.shields.io/codecov/c/github/schlunsen/nuxt-gauge.svg
[codecov-href]: https://codecov.io/gh/schlunsen/nuxt-gauge

[license-src]: https://img.shields.io/npm/l/nuxt-gauge.svg
[license-href]: https://npmjs.com/package/nuxt-gauge
