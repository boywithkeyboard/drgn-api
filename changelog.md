# Changelog

## v1.1.0

### Features

- added `/servers` endpoints
- added server schema and cache

### Changes

- removed unnecessary asynchronous wrapper function in `deploy` script

### Dependencies

- upgraded `esbuild` to **0.14.45** in [#85](https://github.com/drgnjs/api/pull/85)
- upgraded `typescript` to **4.7.4** in [#86](https://github.com/drgnjs/api/pull/86)

## v1.0.2

### Bug Fixes

- fixed download endpoint for `AppImage` format
- fixed dependencies conflicts *(no impact)*

### Dependencies

- upgraded `concurrently` to **7.2.2** in [#80](https://github.com/drgnjs/api/pull/80)
- upgraded `cachu` to **6.0.0-canary.3** in [#81](https://github.com/drgnjs/api/pull/81)
- upgraded `esbuild` to **0.14.44** in [#82](https://github.com/drgnjs/api/pull/82)
- upgraded `fastify` to **4.0.3** in [#83](https://github.com/drgnjs/api/pull/83)
- upgraded `@types/node` to **18.0.0** in [#84](https://github.com/drgnjs/api/pull/84)

## v1.0.1

### Bug Fixes

- fixed `/download` endpoint

## v1.0.0

drgn's API is now running in production.