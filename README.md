# @plurnk/plurnk-mimetypes-grammar-make

Pre-built `tree-sitter-make` WASM grammar for the [@plurnk/plurnk-mimetypes](https://github.com/plurnk/plurnk-mimetypes) framework.

## install

```
npm i @plurnk/plurnk-mimetypes-grammar-make
```

## what's in here

- **`make.wasm`** — pre-built from the pinned upstream [tree-sitter-make](https://github.com/tree-sitter-grammars/tree-sitter-make) commit (SHA in `.grammar-pin`)
- `scripts/build-wasm.mjs` — reproducible rebuild from the pinned source
- `scripts/verify-wasm.mjs` — CI byte-identical reproducibility check

Declares only `web-tree-sitter` as a peer — no native `tree-sitter`, no node-gyp.

## license

MIT. The bundled `make.wasm` is built from the upstream tree-sitter-make grammar; see the pinned commit for that project's attribution.
