# etcd

[中文版本](./README.cn.md)

Distributed reliable key-value store for the most critical data of a distributed system

[![x-cmd/install — etcd Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/etcd.svg)](https://x-cmd.com/install/etcd)

## Install

```sh
x install etcd
```

## Code insight

Total: **181,360** lines of code across **1186** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 167,788 | 26,911 | 25,590 | 1094 |
| Json | 5,045 | 0 | 0 | 27 |
| Sh | 2,974 | 949 | 669 | 46 |
| Jsonnet | 1,667 | 14 | 14 | 10 |
| Svg | 1,394 | 7 | 0 | 9 |

## OpenSSF Scorecard

Overall score: **6.9 / 10**

Lowest-scoring checks:

- **Dangerous-Workflow** (0/10) — dangerous workflow patterns detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: some github tokens can't read classic branch protect…

## Source

- **Upstream**: <https://github.com/etcd-io/etcd>
- **Homepage**: <https://etcd.io>
- **License**: Apache-2.0

## Release

- **Latest**: `v3.7.3` (2026-10-22)
- **Last commit**: 2026-10-23
- **Assets in release**: 8

## Popularity

- **Stars**: 52,431 · **Forks**: 10,555 · **Open issues**: 7,314 · **Contributors**: 994

## Totals (cumulative)

- **Releases**: 298 · **Merged PRs**: 10738 · **Open PRs**: 261 · **Closed issues**: 7175 · **Open issues**: 139 · **Commits**: 25334

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-09-27 | 3 | 53 | 57 | 14 | 22 | 72 |
| last60d | 2026-08-28 | 6 | 97 | 82 | 23 | 34 | 133 |
| 90d | 2026-07-29 | 6 | 146 | 112 | 28 | 50 | 208 |
| last180d | 2026-04-30 | 20 | 394 | 196 | 72 | 80 | 617 |
| 360d | 2025-11-01 | 35 | 761 | 236 | 160 | 91 | 1318 |
| last720d | 2024-11-06 | 59 | 1835 | 254 | 506 | 117 | 3326 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [etcd-v3.7.3-darwin-amd64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.3/etcd-v3.7.3-darwin-amd64.zip) | 23.3 MiB | `native/darwin/x64` |
| [etcd-v3.7.3-darwin-arm64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.3/etcd-v3.7.3-darwin-arm64.zip) | 21.8 MiB | `native/darwin/arm64` |
| [etcd-v3.7.3-linux-amd64.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.3/etcd-v3.7.3-linux-amd64.tar.gz) | 22.8 MiB | `native/linux/x64` |
| [etcd-v3.7.3-linux-arm64.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.3/etcd-v3.7.3-linux-arm64.tar.gz) | 20.9 MiB | `native/linux/arm64` |
| [etcd-v3.7.3-linux-ppc64le.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.3/etcd-v3.7.3-linux-ppc64le.tar.gz) | 21.1 MiB | `native/unknown` |
| [etcd-v3.7.3-linux-s390x.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.3/etcd-v3.7.3-linux-s390x.tar.gz) | 22.5 MiB | `native/unknown` |
| [etcd-v3.7.3-windows-amd64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.3/etcd-v3.7.3-windows-amd64.zip) | 23.3 MiB | `native/win/x64` |
| [SHA256SUMS](https://github.com/etcd-io/etcd/releases/download/v3.7.3/SHA256SUMS) | 676 B | `other` |

## Distribution status

Reported by **166** distros on [repology.org](https://repology.org/project/etcd). **10** are ✅ on the latest upstream release, **131** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
| Debian unstable | `3.5.16` | 🪦 legacy |
| Debian 14 | `3.5.16` | 🪦 legacy |
| Debian 13 | `3.5.16` | ⚠️ outdated |
| Ubuntu 26.04 LTS | `3.5.16` | ⚠️ outdated |
| Ubuntu 24.04 LTS | `3.4.30` | ⚠️ outdated |
| Arch | `3.7.3` | ✅ latest |
| Homebrew | `3.7.3` | ✅ latest |
| Nix unstable | `3.7.2` | ⚠️ outdated |
| Void | `3.7.1` | ⚠️ outdated |
| Alpine edge | `3.6.13` | ⚠️ outdated |
| openSUSE Tumbleweed | `3.7.3` | ✅ latest |

## Improve this data

Install metadata for etcd lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `etcd` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/etcd.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261027.yml` · 2026-10-27T04:57:55Z._
