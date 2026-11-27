# etcd

[English version](./README.md)

Distributed reliable key-value store for the most critical data of a distributed system

[![x-cmd/install — etcd Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/etcd.svg?lang=zh)](https://x-cmd.com/install/etcd)

## 安装

```sh
x install etcd
```

## 代码洞察

合计: **181,620** 行代码（覆盖前 5 种语言、共 **1199** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 167,996 | 26,990 | 25,619 | 1096 |
| Json | 5,063 | 0 | 0 | 27 |
| Sh | 3,018 | 1,107 | 717 | 57 |
| Jsonnet | 1,667 | 14 | 14 | 10 |
| Svg | 1,394 | 7 | 0 | 9 |

## OpenSSF Scorecard 评分

总评分: **6.9 / 10**

评分最低的几项:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Dangerous-Workflow** (0/10) — dangerous workflow patterns detected
- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: some github tokens can't read classic branch protect…

## 源代码

- **上游仓库**: <https://github.com/etcd-io/etcd>
- **官网**: <https://etcd.io>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v3.7.4` (2026-11-19)
- **最近提交**: 2026-11-24
- **Release 含资产**: 8 个

## 流行度

- **Star**: 52,660 · **Fork**: 10,635 · **开放 issue**: 7,403 · **贡献者**: 1,011

## 累计统计

- **发布数**: 301 · **已合并 PR**: 10819 · **开放 PR**: 365 · **已关闭 issue**: 7208 · **开放 issue**: 195 · **提交数**: 25460

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-28 | 3 | 70 | 131 | 26 | 63 | 115 |
| last60d | 2026-09-28 | 6 | 132 | 173 | 43 | 80 | 201 |
| 90d | 2026-08-29 | 9 | 178 | 201 | 53 | 94 | 263 |
| last180d | 2026-05-31 | 19 | 376 | 279 | 85 | 131 | 576 |
| 360d | 2025-12-02 | 35 | 793 | 336 | 182 | 146 | 1351 |
| last720d | 2024-12-07 | 60 | 1836 | 357 | 511 | 170 | 3274 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [etcd-v3.7.4-darwin-amd64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.4/etcd-v3.7.4-darwin-amd64.zip) | 23.3 MiB | `native/darwin/x64` |
| [etcd-v3.7.4-darwin-arm64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.4/etcd-v3.7.4-darwin-arm64.zip) | 21.8 MiB | `native/darwin/arm64` |
| [etcd-v3.7.4-linux-amd64.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.4/etcd-v3.7.4-linux-amd64.tar.gz) | 22.8 MiB | `native/linux/x64` |
| [etcd-v3.7.4-linux-arm64.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.4/etcd-v3.7.4-linux-arm64.tar.gz) | 20.9 MiB | `native/linux/arm64` |
| [etcd-v3.7.4-linux-ppc64le.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.4/etcd-v3.7.4-linux-ppc64le.tar.gz) | 21.1 MiB | `native/unknown` |
| [etcd-v3.7.4-linux-s390x.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.4/etcd-v3.7.4-linux-s390x.tar.gz) | 22.5 MiB | `native/unknown` |
| [etcd-v3.7.4-windows-amd64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.4/etcd-v3.7.4-windows-amd64.zip) | 23.3 MiB | `native/win/x64` |
| [SHA256SUMS](https://github.com/etcd-io/etcd/releases/download/v3.7.4/SHA256SUMS) | 676 B | `other` |

## 发行版状态

在 [repology.org](https://repology.org/project/etcd) 上共有 **164** 个发行版报告此项目。**15** 个 ✅ 已是最新上游版本，**123** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Debian unstable | `3.5.16` | 🪦 legacy |
| Debian 14 | `3.5.16` | 🪦 legacy |
| Debian 13 | `3.5.16` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `3.5.16` | ⚠️ outdated |
| Ubuntu 24.04 LTS | `3.4.30` | ⚠️ outdated |
| Arch | `3.7.4` | ✅ latest |
| Homebrew | `3.7.4` | ✅ latest |
| Nix unstable | `3.7.4` | ✅ latest |
| Void | `3.7.1` | ⚠️ outdated |
| Alpine edge | `3.7.3` | ⚠️ outdated |
| openSUSE Tumbleweed | `3.7.4` | ✅ latest |

## 改进这些数据

etcd 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `etcd` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/etcd.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261127.yml` · 2026-11-27T08:37:41Z._
