# Datadog Backup

![Rspec and Release](https://github.com/scribd/datadog_backup/workflows/Rspec%20and%20Release/badge.svg)

Use `datadog_backup` to backup your datadog account.
Currently supports

  - dashboards
  - monitors

Additional features may be built out over time.

## Installation

```
gem build datadog_backup.gemspec
gem install datadog_backup-*.gem
```

## Usage

```
DATADOG_API_KEY=example123 DATADOG_APP_KEY=example123 datadog_sync <backup|diffs> [--backup-dir /path/to/backups] [--debug] [--monitors-only] [--dashboards-only]
```

# Development

Releases are cut using [semantic-release](https://github.com/semantic-release/semantic-release).

Please write commit messages following [Angular commit guidelines](https://github.com/angular/angular.js/blob/master/DEVELOPERS.md#-git-commit-guidelines)
