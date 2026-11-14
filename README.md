# hcb-action

> Drop-in GitHub Action: check a DSH plugin's declared compatibility and tracks against HCB.

```yaml
- uses: PerryLink/hcb-action@main
  with:
    package: your-npm-package
    # host: 0.2.2-rc.3
    # fail-on: declared-incompatible
```

It delegates to `PerryLink/hcb/.github/actions/check@main`; the canonical data lives there.
