> **This repository is retired (2026-11-14).**
>
> HCB is now the **data/gate subproject of [dsh-standards](https://github.com/PerryLink/dsh-standards)**.
>
> - Rules, checker and ENTRY/FLOW/BOOST definitions: [dsh-standards](https://github.com/PerryLink/dsh-standards)
> - Compatibility matrix, tracks data, risk and `hcb-gate/1`: [dsh-hcb](https://github.com/PerryLink/dsh-hcb)
>
> This repo is archived for URL stability. Do not use it for new work.

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
