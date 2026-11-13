# Scoop bucket for BarSQL

[BarSQL](https://github.com/Bare7a/BarSQL) is a fast, local-first SQL workbench for PostgreSQL, MySQL / MariaDB, SQL Server, ClickHouse, Turso / libSQL and SQLite.

```powershell
scoop bucket add bare7a https://github.com/Bare7a/scoop-bucket
scoop install bare7a/barsql
```

The app keeps updating itself. `scoop update barsql` brings Scoop's own version up to date, and the `BarSQL-data` folder carries over between versions.

BarSQL's release workflow writes `bucket/barsql.json` from `packaging/scoop/barsql.json` in [Bare7a/BarSQL](https://github.com/Bare7a/BarSQL), so change the manifest there, not here.
