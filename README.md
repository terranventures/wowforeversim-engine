# wowforeversim engine

Built files for [wowforeversim](https://wowforeversim.vercel.app): the simulator engine compiled to WebAssembly,
one file per class, named by content hash. The site loads them through jsDelivr. CI publishes here and keeps
the newest five; there is no source in this repository.

| File | What |
|---|---|
| `druid-<hash>.wasm.gz` | Druid engine (gzip) |
| `wasm_exec-<go version>.js` | Go's WebAssembly loader |

## License

wowforeversim's own code in these files: copyright terranventures, all rights reserved. The files may be
loaded by browsers using wowforeversim; no other use is licensed.

The engine includes third-party code under its own licenses (wowsims Forever, Go, Protocol Buffers for Go,
golang.org/x/exp): see [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
