# lib-compress

Compression contract — codec types plus the laws every backend must satisfy.

## Layout

```text
src/                     the .hnl sources
pkg.hnl                  package manifest
scripts/hnl-gate.sh      the gate
workflows/gate.yaml                    bupha entry (handl-gates)
```

## Gate

```bash
HNL=../host-cli/target/debug/hnl scripts/hnl-gate.sh
```

## License

MIT.
