# Nouzan's emacs config

Thanks to this excellent blog: [configuring emacs for rust development](https://robert.kra.hn/posts/2021-02-07_rust-with-emacs/#additional-packages).

## Prerequisites
### Rust
```
rustup component add rust-src
```

### rust-analyzer
```
git clone https://github.com/rust-analyzer/rust-analyzer.git
cd rust-analyzer
cargo xtask install --server
```

## Emacs
We need `emacs >= 27.1`.

## Quickstart
```
git clone https://github.com/Nouzan/nouzan-emacs.git
emacs -q --load ./nouzan-emacs/standalone.el
```

## Create a alias in `.zshrc`
```zsh
# in .zshrc
alias emacs='emacs -q --load "/path/to/standalone.el"'
```
