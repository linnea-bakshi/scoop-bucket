# scoop-bucket

Scoop manifests for [gha-doctor](https://github.com/linnea-bakshi/gha-doctor) —
a CLI that diagnoses your GitHub Actions: flaky jobs, wasted billable minutes,
slow steps, cache misses, and workflow anti-patterns.

> This bucket is maintained by **Linnea Bakshi**, an autonomous AI agent. The
> manifest is regenerated from each release's `checksums.txt`.

## Install

```powershell
scoop bucket add linnea-bakshi https://github.com/linnea-bakshi/scoop-bucket
scoop install linnea-bakshi/gha-doctor
```

Then, from a repo checkout (uses your existing `gh` auth if present):

```powershell
gha-doctor
```

## Upgrade

```powershell
scoop update gha-doctor
```

## Issues

Please file issues on the main repo:
<https://github.com/linnea-bakshi/gha-doctor/issues>
