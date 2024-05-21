# Changelog

## \[2.0.0-beta.16]

### Dependencies

- Upgraded to `tauri-utils@2.0.0-beta.16`

## \[2.0.0-beta.15]

### Dependencies

- Upgraded to `tauri-utils@2.0.0-beta.15`

## \[2.0.0-beta.14]

### Enhancements

- [`bf2635ab6`](https://www.github.com/tauri-apps/tauri/commit/bf2635ab6241a5b82569eafc939046d6e245f3ad)([#9632](https://www.github.com/tauri-apps/tauri/pull/9632)) Improve the error message that is shown when the `links` property is missing from a Tauri Plugin.

### Dependencies

- Upgraded to `tauri-utils@2.0.0-beta.14`

## \[2.0.0-beta.13]

### Dependencies

- Upgraded to `tauri-utils@2.0.0-beta.13`

## \[2.0.0-beta.12]

### Dependencies

- Upgraded to `tauri-utils@2.0.0-beta.12`

## \[2.0.0-beta.11]

### Dependencies

- Upgraded to `tauri-utils@2.0.0-beta.11`

## \[2.0.0-beta.10]

### New Features

- [`e227fe02f`](https://www.github.com/tauri-apps/tauri/commit/e227fe02f986e145c0731a64693e1c830a9eb5b0)([#9156](https://www.github.com/tauri-apps/tauri/pull/9156)) Allow plugins to define (at compile time) JavaScript that are initialized when `withGlobalTauri` is true.
- [`e227fe02f`](https://www.github.com/tauri-apps/tauri/commit/e227fe02f986e145c0731a64693e1c830a9eb5b0)([#9156](https://www.github.com/tauri-apps/tauri/pull/9156)) Added `Builder::global_api_script_path` to define a JavaScript file containing the initialization script for the plugin API bindings when `withGlobalTauri` is used.

### Dependencies

- Upgraded to `tauri-utils@2.0.0-beta.10`

## \[2.0.0-beta.9]

### Dependencies

- Upgraded to `tauri-utils@2.0.0-beta.9`

## \[2.0.0-beta.8]

### Dependencies

- Upgraded to `tauri-utils@2.0.0-beta.8`

## \[2.0.0-beta.7]

### Dependencies

- Upgraded to `tauri-utils@2.0.0-beta.7`

## \[2.0.0-beta.6]

### Dependencies

- Upgraded to `tauri-utils@2.0.0-beta.6`

### Breaking Changes

- [`3657ad82`](https://www.github.com/tauri-apps/tauri/commit/3657ad82f88ce528551d032d521c52eed3f396b4)([#9008](https://www.github.com/tauri-apps/tauri/pull/9008)) Allow defining permissions for the application commands via `tauri_build::Attributes::app_manifest`.

## \[2.0.0-beta.5]

### Dependencies

- Upgraded to `tauri-utils@2.0.0-beta.5`

## \[2.0.0-beta.4]

### Dependencies

- Upgraded to `tauri-utils@2.0.0-beta.4`

## \[2.0.0-beta.3]

### Dependencies

- Upgraded to `tauri-utils@2.0.0-beta.3`

## \[2.0.0-beta.2]

### Enhancements

- [`dd7571a7`](https://www.github.com/tauri-apps/tauri/commit/dd7571a7808676c8063a4983b9c6687dfaf03a09)([#8815](https://www.github.com/tauri-apps/tauri/pull/8815)) Do not generate JSON schema and markdown reference file if the plugin does not define any permissions and delete those files if they exist.

### Dependencies

- Upgraded to `tauri-utils@2.0.0-beta.2`

## \[2.0.0-beta.1]

### Bug Fixes

- [`4e101f80`](https://www.github.com/tauri-apps/tauri/commit/4e101f801657e7d01ce8c22f9c6468067d0caab2)([#8756](https://www.github.com/tauri-apps/tauri/pull/8756)) Rerun build script when a new permission is added.

### Dependencies

- Upgraded to `tauri-utils@2.0.0-beta.1`

## \[2.0.0-beta.0]

### New Features

- [`74a2a603`](https://www.github.com/tauri-apps/tauri/commit/74a2a6036a5e57462f161d728cbd8a6f121028ca)([#8661](https://www.github.com/tauri-apps/tauri/pull/8661)) Implement access control list for IPC usage.
