# etcd

[中文版本](./README.cn.md)

Distributed reliable key-value store for the most critical data of a distributed system

[![x-cmd/install — etcd Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/etcd.svg)](https://x-cmd.com/install/etcd)

## Install

```sh
x install etcd
```

## Code insight

Total: **181,910** lines of code across **1199** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 168,286 | 26,984 | 25,627 | 1096 |
| Json | 5,063 | 0 | 0 | 27 |
| Sh | 3,018 | 1,107 | 717 | 57 |
| Jsonnet | 1,667 | 14 | 14 | 10 |
| Svg | 1,394 | 7 | 0 | 9 |

## OpenSSF Scorecard

Overall score: **7 / 10**

Lowest-scoring checks:

- **Dangerous-Workflow** (0/10) — dangerous workflow patterns detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: some github tokens can't read classic branch protect…

## Source

- **Upstream**: <https://github.com/etcd-io/etcd>
- **Homepage**: <https://etcd.io>
- **License**: Apache-2.0

## Release

- **Latest**: `v3.7.4` (2026-11-19)
- **Last commit**: 2026-11-23
- **Assets in release**: 8

## Popularity

- **Stars**: 52,649 · **Forks**: 10,623 · **Open issues**: 7,392 · **Contributors**: 1,012

## Totals (cumulative)

- **Releases**: 301 · **Merged PRs**: 10808 · **Open PRs**: 310 · **Closed issues**: 7208 · **Open issues**: 184 · **Commits**: 25443

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-24 | 3 | 68 | 74 | 27 | 52 | 98 |
| last60d | 2026-09-24 | 6 | 124 | 121 | 45 | 70 | 183 |
| 90d | 2026-08-25 | 9 | 173 | 146 | 54 | 88 | 245 |
| last180d | 2026-05-27 | 19 | 386 | 228 | 92 | 122 | 558 |
| 360d | 2025-11-28 | 35 | 783 | 281 | 183 | 135 | 1333 |
| last720d | 2024-12-03 | 60 | 1838 | 302 | 517 | 159 | 3284 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [etcd-v3.7.4-darwin-amd64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.4/etcd-v3.7.4-darwin-amd64.zip) | 23.3 MiB | `native/darwin/x64` |
| [etcd-v3.7.4-darwin-arm64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.4/etcd-v3.7.4-darwin-arm64.zip) | 21.8 MiB | `native/darwin/arm64` |
| [etcd-v3.7.4-linux-amd64.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.4/etcd-v3.7.4-linux-amd64.tar.gz) | 22.8 MiB | `native/linux/x64` |
| [etcd-v3.7.4-linux-arm64.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.4/etcd-v3.7.4-linux-arm64.tar.gz) | 20.9 MiB | `native/linux/arm64` |
| [etcd-v3.7.4-linux-ppc64le.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.4/etcd-v3.7.4-linux-ppc64le.tar.gz) | 21.1 MiB | `native/unknown` |
| [etcd-v3.7.4-linux-s390x.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.4/etcd-v3.7.4-linux-s390x.tar.gz) | 22.5 MiB | `native/unknown` |
| [etcd-v3.7.4-windows-amd64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.4/etcd-v3.7.4-windows-amd64.zip) | 23.3 MiB | `native/win/x64` |
| [SHA256SUMS](https://github.com/etcd-io/etcd/releases/download/v3.7.4/SHA256SUMS) | 676 B | `other` |

## Distribution status

Reported by **165** distros on [repology.org](https://repology.org/project/etcd). **14** are ✅ on the latest upstream release, **125** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
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
| openSUSE Tumbleweed | `3.7.3` | ⚠️ outdated |

## Improve this data

Install metadata for etcd lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `etcd` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/etcd.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261123.yml` · 2026-11-23T07:46:58Z._
