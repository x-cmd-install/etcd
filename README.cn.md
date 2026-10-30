# etcd

[English version](./README.md)

Distributed reliable key-value store for the most critical data of a distributed system

[![x-cmd/install — etcd Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/etcd.svg?lang=zh)](https://x-cmd.com/install/etcd)

## 安装

```sh
x install etcd
```

## 代码洞察

合计: **181,360** 行代码（覆盖前 5 种语言、共 **1186** 个文件）。

| 语言 | 代码 | 注释 | 空行 | 文件数 |
|------|-----:|-----:|-----:|------:|
| Go | 167,788 | 26,911 | 25,590 | 1094 |
| Json | 5,045 | 0 | 0 | 27 |
| Sh | 2,974 | 949 | 669 | 46 |
| Jsonnet | 1,667 | 14 | 14 | 10 |
| Svg | 1,394 | 7 | 0 | 9 |

## OpenSSF Scorecard 评分

总评分: **6.7 / 10**

评分最低的几项:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Dangerous-Workflow** (0/10) — dangerous workflow patterns detected
- **Signed-Releases** (0/10) — Project has not signed or included provenance with any releases.

## 源代码

- **上游仓库**: <https://github.com/etcd-io/etcd>
- **官网**: <https://etcd.io>
- **许可证**: Apache-2.0

## 发布

- **最新版本**: `v3.7.3` (2026-10-22)
- **最近提交**: 2026-10-28
- **Release 含资产**: 8 个

## 流行度

- **Star**: 52,431 · **Fork**: 10,551 · **开放 issue**: 7,316 · **贡献者**: 994

## 累计统计

- **发布数**: 298 · **已合并 PR**: 10747 · **开放 PR**: 255 · **已关闭 issue**: 7175 · **开放 issue**: 141 · **提交数**: 25342

## 最近活动

| 时间窗口 | 起始 | 发布 | 已合并 PR | 开放 PR | 已关闭 issue | 开放 issue | 提交 |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-30 | 3 | 56 | 44 | 11 | 22 | 80 |
| last60d | 2026-08-31 | 6 | 103 | 75 | 23 | 36 | 141 |
| 90d | 2026-08-01 | 6 | 146 | 102 | 28 | 51 | 216 |
| last180d | 2026-05-03 | 17 | 396 | 190 | 70 | 82 | 625 |
| 360d | 2025-11-04 | 35 | 766 | 230 | 160 | 93 | 1326 |
| last720d | 2024-11-09 | 59 | 1833 | 248 | 505 | 119 | 3310 |

## Release 资产

| 资产 | 大小 | 目标平台 |
|------|-----:|----------|
| [etcd-v3.7.3-darwin-amd64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.3/etcd-v3.7.3-darwin-amd64.zip) | 23.3 MiB | `native/darwin/x64` |
| [etcd-v3.7.3-darwin-arm64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.3/etcd-v3.7.3-darwin-arm64.zip) | 21.8 MiB | `native/darwin/arm64` |
| [etcd-v3.7.3-linux-amd64.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.3/etcd-v3.7.3-linux-amd64.tar.gz) | 22.8 MiB | `native/linux/x64` |
| [etcd-v3.7.3-linux-arm64.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.3/etcd-v3.7.3-linux-arm64.tar.gz) | 20.9 MiB | `native/linux/arm64` |
| [etcd-v3.7.3-linux-ppc64le.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.3/etcd-v3.7.3-linux-ppc64le.tar.gz) | 21.1 MiB | `native/unknown` |
| [etcd-v3.7.3-linux-s390x.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.3/etcd-v3.7.3-linux-s390x.tar.gz) | 22.5 MiB | `native/unknown` |
| [etcd-v3.7.3-windows-amd64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.3/etcd-v3.7.3-windows-amd64.zip) | 23.3 MiB | `native/win/x64` |
| [SHA256SUMS](https://github.com/etcd-io/etcd/releases/download/v3.7.3/SHA256SUMS) | 676 B | `other` |

## 发行版状态

在 [repology.org](https://repology.org/project/etcd) 上共有 **166** 个发行版报告此项目。**16** 个 ✅ 已是最新上游版本，**125** 个 ⚠️ 使用旧版本。

| 发行版 | 版本 | 状态 |
|--------|------|------|
| Debian unstable | `3.5.16` | 🪦 legacy |
| Debian 14 | `3.5.16` | 🪦 legacy |
| Debian 13 | `3.5.16` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `3.5.16` | ⚠️ outdated |
| Ubuntu 24.04 LTS | `3.4.30` | ⚠️ outdated |
| Arch | `3.7.3` | ✅ latest |
| Homebrew | `3.7.3` | ✅ latest |
| Nix unstable | `3.7.3` | ✅ latest |
| Void | `3.7.1` | ⚠️ outdated |
| Alpine edge | `3.7.3` | ✅ latest |
| openSUSE Tumbleweed | `3.7.3` | ✅ latest |

## 改进这些数据

etcd 的安装元数据由 [x-cmd/install](https://github.com/x-cmd/install) 索引维护——这是一份由 x-cmd 在安装时读取的精选 YAML 包列表。如果 `etcd` 缺失、过期，或安装行为有问题，欢迎在该 repo 提 issue 或 PR：

- **提交 issue**: <https://github.com/x-cmd/install/issues/new>
- **编辑包条目**: <https://github.com/x-cmd/install/edit/main/etcd.yml>（或索引实际使用的路径）

本页面的数据（card / loc / scorecard / release）由 [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) 自动采集，每日重新生成。**安装行为**（版本选择、平台差异、依赖处理）的改进应提交到上游索引。

_数据快照: `data/card/261030.yml` · 2026-10-30T05:52:59Z._
