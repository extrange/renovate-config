# Renovate Config

Used by default for all my repos.

- Run on early mondays, to reduce noise. If too noisy consider using `automergeType: branch` instead (but setup tests first)
- Automerge all major/minor/patch updates if tests pass
- Pin dependencies to avoid [silent problems]
- Group all non-major updates together, while overriding `lockFileMaintenance` to be `true`

[silent problems]: https://docs.renovatebot.com/dependency-pinning/#upgrading-pinned-versions