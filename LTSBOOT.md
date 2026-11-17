# ltsboot: Spring Security 5.7 LTS fork

**Disclaimer.** ltsboot is an independent open source project. It is not affiliated with, endorsed by, or sponsored by Broadcom Inc. or VMware, Inc. Spring and Spring Boot are trademarks of Broadcom Inc. and are used here only to describe compatibility.

## Base

- Upstream: [spring-projects/spring-security](https://github.com/spring-projects/spring-security)
- Base tag: `5.7.14` (2024-11-18), the last OSS release of the 5.7 line.
- License: Apache License 2.0 ([LICENSE.txt](LICENSE.txt), [notice.txt](notice.txt)).

## Versioning

Versions have four numeric parts: `<upstream version>.<ltsboot release>`, for example `5.7.14.1` and `5.7.14.2`.
Maven and Gradle are expected to rank `5.7.14.1` above the base version `5.7.14`; the ordering is verified before the first release.

First release: `5.7.14.1`.

## Coordinates

- groupId: `io.github.ltsboot` (organization name still to be defined).
- artifactIds are unchanged, for example `spring-security-core` and `spring-security-config`.

## Compatibility

Java package names do not change (`org.springframework.*`). Consuming projects keep their imports and change only the version and groupId.

## Changes

Every modified file carries the line `Modifications Copyright 2026 the ltsboot contributors.` directly below the original copyright line. All changed files are listed in [CHANGES.md](CHANGES.md).
