# cloudnative-pg

[![GitLab Sync](https://img.shields.io/badge/gitlab_sync-cloudnative_pg-blue?style=for-the-badge&logo=gitlab)](https://gitlab-internal.spirit-dev.net/github-mirror/helm-cloudnative-pg) <!-- markdownlint-disable MD041 -->
[![GitHub Mirror](https://img.shields.io/badge/github_mirror-cloudnative_pg-blue?style=for-the-badge&logo=github)](https://github.com/spirit-dev/helm-cloudnative-pg)
[![App Status](https://argocd-internal.spirit-dev.net/api/badge?name=cloudnative-pg-turingpi&revision=true&showAppName=true)](https://argocd-internal.spirit-dev.net/applications/cloudnative-pg-turingpi)

<!--TOC-->

- [Installation process](#installation-process)

<!--TOC-->

## Installation process

The installation is entirely managed by Argocd.

A `Makefile` is present here to ease the first and one-time deployment or in case of an issue.
The installation should be done in two steps:

```shell
#> make dry-run ENV=<ENV>
#> make install ENV=<ENV>
```
