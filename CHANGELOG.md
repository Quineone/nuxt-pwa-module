# Changelog

All notable changes to this project will be documented in this file. See [standard-version](https://github.com/conventional-changelog/standard-version) for commit guidelines.

## [0.8.0](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.7.2...v0.8.0) (2022-10-12)

### [0.7.2](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.7.1...v0.7.2) (2022-10-11)


### Bug Fixes

* improve nitro config to fix nuxi generate ([b322220](https://github.com/kevinmarrec/nuxt-pwa-module/commit/b32222037915a8f060122fea686b80bb7904607f))

### [0.7.1](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.7.0...v0.7.1) (2022-10-11)


### Bug Fixes

* add missing import in nitro plugin ([1c1b3e2](https://github.com/kevinmarrec/nuxt-pwa-module/commit/1c1b3e225c0a7bfa4cfb4ae526a8cb30dd213728))

## [0.7.0](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.6.1...v0.7.0) (2022-10-11)


### Features

* add workbox.autoRegister option ([76ecf22](https://github.com/kevinmarrec/nuxt-pwa-module/commit/76ecf22f24bc4a07a14ac62b92611a91cf2ea2eb)), closes [#46](https://github.com/kevinmarrec/nuxt-pwa-module/issues/46)


### Bug Fixes

* use nitro plugin for sw registration ([79063ef](https://github.com/kevinmarrec/nuxt-pwa-module/commit/79063ef2312e05bbac4e3a1247d367392176a055)), closes [#45](https://github.com/kevinmarrec/nuxt-pwa-module/issues/45)

### [0.6.1](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.6.0...v0.6.1) (2022-10-01)


### Bug Fixes

* **icon:** support all icon sizes ([f342fa8](https://github.com/kevinmarrec/nuxt-pwa-module/commit/f342fa895110ad4525c8e46a9ca5574413dc4b15))

## [0.6.0](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.5.0...v0.6.0) (2022-10-01)


### Features

* usePWAIcon composable  ([#43](https://github.com/kevinmarrec/nuxt-pwa-module/issues/43)) ([adfac55](https://github.com/kevinmarrec/nuxt-pwa-module/commit/adfac557535b7d6b7b81939cf12ba8b08839f4c3)), closes [#42](https://github.com/kevinmarrec/nuxt-pwa-module/issues/42)

## [0.5.0](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.4.2...v0.5.0) (2022-09-29)


### Features

* add custom worker template option ([fd77f68](https://github.com/kevinmarrec/nuxt-pwa-module/commit/fd77f68dd19ee793c7b563e3fa6016b77d18ac9c)), closes [#16](https://github.com/kevinmarrec/nuxt-pwa-module/issues/16) [#27](https://github.com/kevinmarrec/nuxt-pwa-module/issues/27) [#29](https://github.com/kevinmarrec/nuxt-pwa-module/issues/29) [#36](https://github.com/kevinmarrec/nuxt-pwa-module/issues/36) [#38](https://github.com/kevinmarrec/nuxt-pwa-module/issues/38)


### Bug Fixes

* generate manifest.json when ssr is disabled ([8c52b11](https://github.com/kevinmarrec/nuxt-pwa-module/commit/8c52b1103d1c47c27fd3016026ba48a86ea16578)), closes [#32](https://github.com/kevinmarrec/nuxt-pwa-module/issues/32)
* **icon:** better unusual input icon handling ([8c1f8e2](https://github.com/kevinmarrec/nuxt-pwa-module/commit/8c1f8e2c715ca1416d5d3c6d4a7059fe49f8a99b)), closes [#40](https://github.com/kevinmarrec/nuxt-pwa-module/issues/40)

### [0.4.2](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.4.1...v0.4.2) (2022-07-22)


### Bug Fixes

* remove postinstall command ([d67bbc6](https://github.com/kevinmarrec/nuxt-pwa-module/commit/d67bbc6b4cc2bf1e6fc1fa43523c5301fee19907)), closes [#23](https://github.com/kevinmarrec/nuxt-pwa-module/issues/23)

### [0.4.1](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.4.0...v0.4.1) (2022-07-22)


### Bug Fixes

* **manifest:** move server handler to runtime ([73ee968](https://github.com/kevinmarrec/nuxt-pwa-module/commit/73ee9689ae0114d0b4f3779b2c26e58b97900bd0)), closes [#22](https://github.com/kevinmarrec/nuxt-pwa-module/issues/22)

## [0.4.0](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.3.1...v0.4.0) (2022-07-22)


### Bug Fixes

* prevent assets duplication on build ([e54f564](https://github.com/kevinmarrec/nuxt-pwa-module/commit/e54f5648630ca2157f14c9dd138ae0f89f193ffb)), closes [#20](https://github.com/kevinmarrec/nuxt-pwa-module/issues/20)

### [0.3.1](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.3.0...v0.3.1) (2022-06-24)


### Bug Fixes

* disable icon generation on stackblitz ([7813821](https://github.com/kevinmarrec/nuxt-pwa-module/commit/781382127e7773f7362d1c5f44bc4425d59a30d2))

## [0.3.0](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.2.2...v0.3.0) (2022-06-07)


### Features

* padded maskable icons ([8dcdefe](https://github.com/kevinmarrec/nuxt-pwa-module/commit/8dcdefe5e9bf71f64349ac4627e61e75cc96093c)), closes [#10](https://github.com/kevinmarrec/nuxt-pwa-module/issues/10)


### Bug Fixes

* use baseURL for sw/manifest/icons/splash ([#14](https://github.com/kevinmarrec/nuxt-pwa-module/issues/14)) ([aa01db1](https://github.com/kevinmarrec/nuxt-pwa-module/commit/aa01db1679eee3141d8576b24a62b3779f99960e))
* **workbox:** fix worker when using `pages` folder ([52ecdb9](https://github.com/kevinmarrec/nuxt-pwa-module/commit/52ecdb9e420bbd596389ca7bb5533ca4a10d1e32)), closes [#11](https://github.com/kevinmarrec/nuxt-pwa-module/issues/11)

### [0.2.2](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.2.1...v0.2.2) (2022-06-01)


### Bug Fixes

* adjust manifest icons purposes ([f01b0a5](https://github.com/kevinmarrec/nuxt-pwa-module/commit/f01b0a5099bf78731d0e7195b4bb0d093fce97ea)), closes [#8](https://github.com/kevinmarrec/nuxt-pwa-module/issues/8)

### [0.2.1](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.2.0...v0.2.1) (2022-05-31)


### Bug Fixes

* move sw.js on root to make app installable ([bd36561](https://github.com/kevinmarrec/nuxt-pwa-module/commit/bd365611833ea9db4e2e03066fd70322da158288))

## [0.2.0](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.1.0...v0.2.0) (2022-05-31)


### Features

* splash screen support ([#6](https://github.com/kevinmarrec/nuxt-pwa-module/issues/6)) ([970c5f8](https://github.com/kevinmarrec/nuxt-pwa-module/commit/970c5f89a7b6564580b36ee61052caeeeb0fb6ad))

## [0.1.0](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.0.2...v0.1.0) (2022-05-21)


### Features

* add icon generation & asset hashing ([#2](https://github.com/kevinmarrec/nuxt-pwa-module/issues/2)) ([a6ccb95](https://github.com/kevinmarrec/nuxt-pwa-module/commit/a6ccb95a74c94fd7b8b558046274b8f4406bbf6c))

### [0.0.2](https://github.com/kevinmarrec/nuxt-pwa-module/compare/v0.0.1...v0.0.2) (2022-05-15)


### Bug Fixes

* **types:** add `short_name` to `ManifestOptions` ([72ab2ce](https://github.com/kevinmarrec/nuxt-pwa-module/commit/72ab2ce7a95773e2af0568015d6b2d92afd9b191))

### 0.0.1 (2022-05-15)
