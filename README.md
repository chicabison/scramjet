
## Development

### Dependencies

- Recent versions of `node.js` and `pnpm`
- `rustup`
- `wasm-bindgen`
- [Binaryen's `wasm-opt`](https://github.com/WebAssembly/binaryen)
- [this `wasm-snip` fork](https://github.com/r58Playz/wasm-snip)

#### Building

- Clone the repository with `git clone --recursive https://github.com/MercuryWorkshop/scramjet`
- Install the dependencies with `pnpm i`
- Change directories with `cd packages/core`
- Build the rewriter with `pnpm rewriter:build`
- Build Scramjet with `pnpm build`

### Running Scramjet Locally

You can run the Scramjet dev server when running this command at the root

```sh
pnpm dev
```

The demo page for scramjet should now be running at <http://localhost:4141> and should rebuild upon a file being changed (excluding the rewriter).
