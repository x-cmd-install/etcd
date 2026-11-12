# etcd

[中文版本](./README.cn.md)

Distributed reliable key-value store for the most critical data of a distributed system

[![x-cmd/install — etcd Code Quality Monitoring Repo Card](https://x-cmd.com/repo-card/etcd.svg)](https://x-cmd.com/install/etcd)

## Install

```sh
x install etcd
```

## Code insight

Total: **181,848** lines of code across **1191** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 168,265 | 26,993 | 25,641 | 1096 |
| Json | 5,054 | 0 | 0 | 27 |
| Sh | 2,976 | 991 | 679 | 49 |
| Jsonnet | 1,667 | 14 | 14 | 10 |
| Svg | 1,394 | 7 | 0 | 9 |

## OpenSSF Scorecard

Overall score: **6.9 / 10**

Lowest-scoring checks:

- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Dangerous-Workflow** (0/10) — dangerous workflow patterns detected
- **Signed-Releases** (0/10) — Project has not signed or included provenance with any releases.

## Source

- **Upstream**: <https://github.com/etcd-io/etcd>
- **Homepage**: <https://etcd.io>
- **License**: Apache-2.0

## Release

- **Latest**: `v3.7.3` (2026-10-22)
- **Last commit**: 2026-11-12
- **Assets in release**: 8

## Popularity

- **Stars**: 52,599 · **Forks**: 10,595 · **Open issues**: 7,369 · **Contributors**: 1,006

## Totals (cumulative)

- **Releases**: 298 · **Merged PRs**: 10784 · **Open PRs**: 290 · **Closed issues**: 7190 · **Open issues**: 179 · **Commits**: 25403

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-10-13 | 3 | 71 | 61 | 20 | 53 | 106 |
| last60d | 2026-09-13 | 6 | 118 | 95 | 36 | 67 | 171 |
| 90d | 2026-08-14 | 6 | 166 | 127 | 40 | 86 | 244 |
| last180d | 2026-05-16 | 17 | 401 | 219 | 79 | 117 | 634 |
| 360d | 2025-11-17 | 32 | 773 | 261 | 169 | 129 | 1323 |
| last720d | 2024-11-22 | 57 | 1840 | 282 | 509 | 154 | 3302 |

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

Reported by **167** distros on [repology.org](https://repology.org/project/etcd). **22** are ✅ on the latest upstream release, **120** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
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

## Improve this data

Install metadata for etcd lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `etcd` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/etcd.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/261112.yml` · 2026-11-12T07:16:50Z._
