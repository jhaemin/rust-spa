# Rust SPA

SPA written in Rust.

## Development

Open a new terminal and run

```zsh
% cargo make serve
```

Open another terminal and run

```zsh
% cargo make watch
```

## Production

### Format and lint

```zsh
% cargo make verify
```

### Build

```zsh
% cargo make build_release
```

### Deploy

Upload `index.html` and `pkg` into the server's public directory.

## Appendix

This repository is cloned from [seed-quickstart](https://github.com/seed-rs/seed-quickstart).
