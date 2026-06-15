# Homebrew Analytics Archive

Monthly snapshots of Homebrew analytics JSON.

Tracked endpoints:

- `https://formulae.brew.sh/api/analytics/os-version/30d.json`
- `https://formulae.brew.sh/api/analytics/os-version/90d.json`
- `https://formulae.brew.sh/api/analytics/os-version/365d.json`

New snapshots are saved under `snapshots/os-version/` by a scheduled GitHub Actions workflow.

File format:

`YYYY-MM-DDTHH:MM:SSZ-{30d|90d|365d}.json`

Historical Web Archive imports live in `web-archive/`.
