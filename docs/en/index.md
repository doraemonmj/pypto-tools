# pypto-tools Documentation

This repository distributes two independent products. Each has its own release line and its own documentation set.

| Product | What it does | Documentation |
|---|---|---|
| **PyPTO3 Toolkit** | VS Code extension that visualizes PyPTO 3.0 runtime and compilation output | [Extension user guide](toolkit/index.md) |
| **task-submit** | Queue service that allocates NPU devices and runs jobs on a shared Ascend host | [task-submit guide](task-submit/index.md) |

Neither product requires the other.

## Releases

Release tags carry a product prefix; filter the [release list](https://github.com/hw-native-sys/pypto-tools/releases) by prefix to find the latest package for a product.

| Product | Tag prefix | Asset |
|---|---|---|
| PyPTO3 Toolkit | `v*` | VSIX |
| task-submit | `task-submit-v*` | `task-submit-<version>.tar.gz` and `.sha256` |

## Repository scope

This repository holds documentation and Release assets. The extension source is maintained outside this repository; `task-submit` is developed in [pypto-tools/npu-taskqueue](https://github.com/pypto-tools/npu-taskqueue). The source archives that GitHub generates automatically are not product sources.
