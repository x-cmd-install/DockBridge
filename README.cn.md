# DockBridge

[English version](./README.md)

DockBridge is a Go-based client-server system that provisions Hetzner Cloud servers for Docker containers, with laptop lock detection and keep-alive features. It enables seamless Docker workflows by proxying commands to remote Hetzner Cloud instances, managing server lifecycle by user activity and connection status.

![DockBridge](https://repo.x-cmd.io/DockBridge.svg?lang=zh)

## 安装

```sh
x install DockBridge
```

## 代码洞察

合计: **15,240** 行代码（覆盖前 5 种语言、共 **115** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 14,783 | 2,385 | 3,155 | 104 |
| Yaml | 272 | 77 | 74 | 7 |
| Sh | 81 | 11 | 16 | 2 |
| Makefile | 65 | 16 | 16 | 1 |
| Gherkin | 32 | 0 | 5 | 1 |

## 源代码

- **上游仓库**: <https://github.com/Max-Levitskiy/DockBridge>
- **许可证**: AGPL-3.0

## 发布

- **最新版本**: `v0.1.0` (2025-12-27)
- **最近提交**: 2026-01-04
- **Release 含资产**: 7 个

## 流行度

- **Star**: 6 · **Fork**: 1 · **开放 issue**: 0 · **贡献者**: 1

## 累计统计

- **发布数**: 1 · **已合并 PR**: 4 · **开放 PR**: 1 · **已关闭 issue**: 0 · **开放 issue**: 0 · **提交数**: 85

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-14 | 0 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-15 | 0 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-15 | 0 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-17 | 0 | 0 | 1 | 0 | 0 | 0 |
| 360d | 2025-09-18 | 1 | 4 | 1 | 0 | 0 | 51 |
| last720d | 2024-09-23 | 1 | 4 | 1 | 0 | 0 | 85 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [checksums.txt](https://github.com/Max-Levitskiy/DockBridge/releases/download/v0.1.0/checksums.txt) | 550 B | `other` |
| [dockbridge-darwin-amd64](https://github.com/Max-Levitskiy/DockBridge/releases/download/v0.1.0/dockbridge-darwin-amd64) | 15.9 MiB | `native/darwin/x64` |
| [dockbridge-darwin-arm64](https://github.com/Max-Levitskiy/DockBridge/releases/download/v0.1.0/dockbridge-darwin-arm64) | 15.2 MiB | `native/darwin/arm64` |
| [dockbridge-linux-amd64](https://github.com/Max-Levitskiy/DockBridge/releases/download/v0.1.0/dockbridge-linux-amd64) | 15.6 MiB | `native/linux/x64` |
| [dockbridge-linux-arm64](https://github.com/Max-Levitskiy/DockBridge/releases/download/v0.1.0/dockbridge-linux-arm64) | 14.8 MiB | `native/linux/arm64` |
| [dockbridge-server-linux-amd64](https://github.com/Max-Levitskiy/DockBridge/releases/download/v0.1.0/dockbridge-server-linux-amd64) | 9.9 MiB | `native/linux/x64` |
| [dockbridge-server-linux-arm64](https://github.com/Max-Levitskiy/DockBridge/releases/download/v0.1.0/dockbridge-server-linux-arm64) | 9.3 MiB | `native/linux/arm64` |

## 改进这些数据

DockBridge 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `DockBridge` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/DockBridge.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260913.yml` · 2026-09-13T05:04:51Z._
