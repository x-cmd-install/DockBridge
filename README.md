# DockBridge

[中文版本](./README.cn.md)

DockBridge is a Go-based client-server system that provisions Hetzner Cloud servers for Docker containers, with laptop lock detection and keep-alive features. It enables seamless Docker workflows by proxying commands to remote Hetzner Cloud instances, managing server lifecycle by user activity and connection status.

![DockBridge](https://repo.x-cmd.io/DockBridge.svg)

## Install

```sh
x install DockBridge
```

## Code insight

Total: **15,240** lines of code across **115** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 14,783 | 2,385 | 3,155 | 104 |
| Yaml | 272 | 77 | 74 | 7 |
| Sh | 81 | 11 | 16 | 2 |
| Makefile | 65 | 16 | 16 | 1 |
| Gherkin | 32 | 0 | 5 | 1 |

## Source

- **Upstream**: <https://github.com/Max-Levitskiy/DockBridge>
- **License**: AGPL-3.0

## Release

- **Latest**: `v0.1.0` (2025-12-27)
- **Last commit**: 2026-01-04
- **Assets in release**: 7

## Popularity

- **Stars**: 6 · **Forks**: 1 · **Open issues**: 0 · **Contributors**: 1

## Totals (cumulative)

- **Releases**: 1 · **Merged PRs**: 4 · **Open PRs**: 1 · **Closed issues**: 0 · **Open issues**: 0 · **Commits**: 85

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 0 | 0 | 0 | 0 | 0 |
| last60d | 2026-07-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| 90d | 2026-06-13 | 0 | 0 | 0 | 0 | 0 | 0 |
| last180d | 2026-03-15 | 0 | 0 | 1 | 0 | 0 | 0 |
| 360d | 2025-09-16 | 1 | 4 | 1 | 0 | 0 | 51 |
| last720d | 2024-09-21 | 1 | 4 | 1 | 0 | 0 | 85 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [checksums.txt](https://github.com/Max-Levitskiy/DockBridge/releases/download/v0.1.0/checksums.txt) | 550 B | `other` |
| [dockbridge-darwin-amd64](https://github.com/Max-Levitskiy/DockBridge/releases/download/v0.1.0/dockbridge-darwin-amd64) | 15.9 MiB | `native/darwin/x64` |
| [dockbridge-darwin-arm64](https://github.com/Max-Levitskiy/DockBridge/releases/download/v0.1.0/dockbridge-darwin-arm64) | 15.2 MiB | `native/darwin/arm64` |
| [dockbridge-linux-amd64](https://github.com/Max-Levitskiy/DockBridge/releases/download/v0.1.0/dockbridge-linux-amd64) | 15.6 MiB | `native/linux/x64` |
| [dockbridge-linux-arm64](https://github.com/Max-Levitskiy/DockBridge/releases/download/v0.1.0/dockbridge-linux-arm64) | 14.8 MiB | `native/linux/arm64` |
| [dockbridge-server-linux-amd64](https://github.com/Max-Levitskiy/DockBridge/releases/download/v0.1.0/dockbridge-server-linux-amd64) | 9.9 MiB | `native/linux/x64` |
| [dockbridge-server-linux-arm64](https://github.com/Max-Levitskiy/DockBridge/releases/download/v0.1.0/dockbridge-server-linux-arm64) | 9.3 MiB | `native/linux/arm64` |

## Improve this data

Install metadata for DockBridge lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `DockBridge` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/DockBridge.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260911.yml` · 2026-09-11T04:40:38Z._
