# etcd

[English version](./README.md)

Distributed reliable key-value store for the most critical data of a distributed system

![etcd](https://repo.x-cmd.io/etcd.svg?lang=zh)

## 安装

```sh
x install etcd
```

## 代码洞察

合计: **180,315** 行代码（覆盖前 5 种语言、共 **1183** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 166,864 | 26,660 | 25,436 | 1092 |
| Json | 5,036 | 0 | 0 | 27 |
| Sh | 2,865 | 905 | 639 | 45 |
| Jsonnet | 1,667 | 14 | 14 | 10 |
| Svg | 1,394 | 7 | 0 | 9 |

## OpenSSF Scorecard 评分

总评分: **6.7 / 10**

评分最低的几项:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Dangerous-Workflow** (0/10) — dangerous workflow patterns detected
- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: some github tokens can't read classic branch protect…

## 源代码

- **上游仓库**: <https://github.com/etcd-io/etcd>
- **官网**: <https://etcd.io>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v3.7.1` (2026-07-23)
- **最近提交**: 2026-09-11
- **Release 含资产**: 8 个

## 流行度

- **Star**: 52,248 · **Fork**: 10,495 · **开放 issue**: 7,265 · **贡献者**: 984

## 累计统计

- **发布数**: 292 · **已合并 PR**: 10661 · **开放 PR**: 215 · **已关闭 issue**: 7139 · **开放 issue**: 126 · **提交数**: 25219

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-12 | 0 | 50 | 36 | 3 | 21 | 70 |
| last60d | 2026-07-13 | 3 | 128 | 85 | 11 | 31 | 190 |
| 90d | 2026-06-13 | 6 | 171 | 109 | 19 | 48 | 271 |
| last180d | 2026-03-15 | 20 | 402 | 165 | 70 | 68 | 686 |
| 360d | 2025-09-16 | 33 | 782 | 192 | 151 | 80 | 1413 |
| last720d | 2024-09-21 | 53 | 1863 | 209 | 497 | 105 | 3414 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [etcd-v3.7.1-darwin-amd64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.1/etcd-v3.7.1-darwin-amd64.zip) | 23.3 MiB | `native/darwin/x64` |
| [etcd-v3.7.1-darwin-arm64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.1/etcd-v3.7.1-darwin-arm64.zip) | 21.8 MiB | `native/darwin/arm64` |
| [etcd-v3.7.1-linux-amd64.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.1/etcd-v3.7.1-linux-amd64.tar.gz) | 22.8 MiB | `native/linux/x64` |
| [etcd-v3.7.1-linux-arm64.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.1/etcd-v3.7.1-linux-arm64.tar.gz) | 20.9 MiB | `native/linux/arm64` |
| [etcd-v3.7.1-linux-ppc64le.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.1/etcd-v3.7.1-linux-ppc64le.tar.gz) | 21.0 MiB | `native/unknown` |
| [etcd-v3.7.1-linux-s390x.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.1/etcd-v3.7.1-linux-s390x.tar.gz) | 22.5 MiB | `native/unknown` |
| [etcd-v3.7.1-windows-amd64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.1/etcd-v3.7.1-windows-amd64.zip) | 23.3 MiB | `native/win/x64` |
| [SHA256SUMS](https://github.com/etcd-io/etcd/releases/download/v3.7.1/SHA256SUMS) | 676 B | `other` |

## 发行版状态

在 [repology.org](https://repology.org/project/etcd) 上共有 **170** 个发行版报告此项目。**18** 个 ✅ 已是最新上游版本，**127** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Debian unstable | `3.5.16` | 🪦 legacy |
| Debian 14 | `3.5.16` | 🪦 legacy |
| Debian 13 | `3.5.16` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `3.5.16` | ⚠️ outdated |
| Ubuntu 24.04 LTS | `3.4.30` | ⚠️ outdated |
| Arch | `3.7.1` | ✅ latest |
| Homebrew | `3.7.1` | ✅ latest |
| Nix unstable | `3.6.14` | ⚠️ outdated |
| Void | `3.7.1` | ✅ latest |
| Alpine edge | `3.6.13` | ⚠️ outdated |
| openSUSE Tumbleweed | `3.7.1` | ✅ latest |

## 改进这些数据

etcd 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `etcd` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/etcd.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/260911.yml` · 2026-09-11T20:17:33Z._
