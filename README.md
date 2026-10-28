# lib-compress

Compression contract — codec types plus the laws every backend must satisfy.

Part of the `handl-lang` org split (ADR-0128). History is a `git subtree
split` of the platform monorepo's `compress/` (via `c`).

## Layout

```text
src/        the .hnl sources
pkg.hnl     dependencies, when any: `{ deps: { <name>: "branch:<ref>" } }`
```

## Gate

```bash
HNL=../host-cli/target/debug/hnl scripts/hnl-gate.sh
```

## License

MIT.
