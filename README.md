# etcd

[中文版本](./README.cn.md)

Distributed reliable key-value store for the most critical data of a distributed system

![etcd](https://repo.x-cmd.io/etcd.svg)

## Install

```sh
x install etcd
```

## Code insight

Total: **180,315** lines of code across **1183** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 166,864 | 26,660 | 25,436 | 1092 |
| Json | 5,036 | 0 | 0 | 27 |
| Sh | 2,865 | 905 | 639 | 45 |
| Jsonnet | 1,667 | 14 | 14 | 10 |
| Svg | 1,394 | 7 | 0 | 9 |

## OpenSSF Scorecard

Overall score: **6.7 / 10**

Lowest-scoring checks:

- **Dangerous-Workflow** (0/10) — dangerous workflow patterns detected
- **Token-Permissions** (0/10) — detected GitHub workflow tokens with excessive permissions
- **Signed-Releases** (0/10) — Project has not signed or included provenance with any releases.

## Source

- **Upstream**: <https://github.com/etcd-io/etcd>
- **Homepage**: <https://etcd.io>
- **License**: Apache-2.0

## Release

- **Latest**: `v3.7.1` (2026-07-23)
- **Last commit**: 2026-09-11
- **Assets in release**: 8

## Popularity

- **Stars**: 52,250 · **Forks**: 10,497 · **Open issues**: 7,265 · **Contributors**: 984

## Totals (cumulative)

- **Releases**: 292 · **Merged PRs**: 10662 · **Open PRs**: 214 · **Closed issues**: 7141 · **Open issues**: 124 · **Commits**: 25221

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-13 | 0 | 49 | 35 | 4 | 19 | 72 |
| last60d | 2026-07-14 | 3 | 129 | 82 | 12 | 30 | 192 |
| 90d | 2026-06-14 | 6 | 172 | 107 | 20 | 47 | 273 |
| last180d | 2026-03-16 | 20 | 403 | 164 | 72 | 66 | 688 |
| 360d | 2025-09-17 | 33 | 782 | 191 | 153 | 78 | 1415 |
| last720d | 2024-09-22 | 53 | 1864 | 208 | 499 | 103 | 3416 |

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [etcd-v3.7.1-darwin-amd64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.1/etcd-v3.7.1-darwin-amd64.zip) | 23.3 MiB | `native/darwin/x64` |
| [etcd-v3.7.1-darwin-arm64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.1/etcd-v3.7.1-darwin-arm64.zip) | 21.8 MiB | `native/darwin/arm64` |
| [etcd-v3.7.1-linux-amd64.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.1/etcd-v3.7.1-linux-amd64.tar.gz) | 22.8 MiB | `native/linux/x64` |
| [etcd-v3.7.1-linux-arm64.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.1/etcd-v3.7.1-linux-arm64.tar.gz) | 20.9 MiB | `native/linux/arm64` |
| [etcd-v3.7.1-linux-ppc64le.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.1/etcd-v3.7.1-linux-ppc64le.tar.gz) | 21.0 MiB | `native/unknown` |
| [etcd-v3.7.1-linux-s390x.tar.gz](https://github.com/etcd-io/etcd/releases/download/v3.7.1/etcd-v3.7.1-linux-s390x.tar.gz) | 22.5 MiB | `native/unknown` |
| [etcd-v3.7.1-windows-amd64.zip](https://github.com/etcd-io/etcd/releases/download/v3.7.1/etcd-v3.7.1-windows-amd64.zip) | 23.3 MiB | `native/win/x64` |
| [SHA256SUMS](https://github.com/etcd-io/etcd/releases/download/v3.7.1/SHA256SUMS) | 676 B | `other` |

## Distribution status

Reported by **170** distros on [repology.org](https://repology.org/project/etcd). **18** are ✅ on the latest upstream release, **127** are ⚠️ on an older version.

| Distro | Version | Status |
|--------|---------|--------|
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

## Improve this data

Install metadata for etcd lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `etcd` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/etcd.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260912.yml` · 2026-09-12T04:43:56Z._
