# rust-vscode-devcontainer
vscode devcontainer for rust.

## Reinit project:

```sh
rm -r ./Cargo.lock ./Cargo.toml ./src/ ./target/ .gitignore
cargo init
```

Add `"version"` to `"ghcr.io/devcontainers/features/rust:1": {}` in `devcontainer.json`.
