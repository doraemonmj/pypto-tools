# pypto-tools 文档

本仓库分发两个相互独立的产品，各自有独立的发布线和独立的文档。

| 产品 | 用途 | 文档 |
|---|---|---|
| **PyPTO3 Toolkit** | 可视化 PyPTO 3.0 运行时和编译输出的 VS Code 插件 | [插件用户文档](toolkit/index.md) |
| **task-submit** | 在共享 Ascend 主机上分配 NPU 设备并运行任务的队列服务 | [task-submit 文档](task-submit/index.md) |

两个产品互不依赖。

## 发布

Release tag 带产品前缀。请在 [Release 列表](https://github.com/hw-native-sys/pypto-tools/releases) 中按前缀筛选，以找到某个产品的最新安装包。

| 产品 | Tag 前缀 | 附件 |
|---|---|---|
| PyPTO3 Toolkit | `v*` | VSIX |
| task-submit | `task-submit-v*` | `task-submit-<version>.tar.gz` 和 `.sha256` |

## 仓库范围

本仓库存放文档和 Release 附件。插件源码不在本仓库维护；`task-submit` 的源码仓库是 [pypto-tools/npu-taskqueue](https://github.com/pypto-tools/npu-taskqueue)。GitHub 自动生成的源码压缩包并不是产品源码。
