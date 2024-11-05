# Renovate Config

Used by default for all my repos.

Main considerations:

- Automerging via PR, once a week, to reduce noise, but still give me visibility. If too noisy consider using `automergeType: branch` instead (but setup tests first)
- Pin dependencies to avoid [silent problems]
- Group all updates together, while overriding `lockFileMaintenance` to be `true`

[silent problems]: https://docs.renovatebot.com/dependency-pinning/#upgrading-pinned-versions