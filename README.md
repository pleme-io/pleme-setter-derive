# pleme-setter-derive

Per-field inherent setter: pub fn set_<field>(&mut self, v: <Type>). Generated from a tatara-rust-ast PerFieldDeriveSpec.

[![Build](https://github.com/pleme-io/pleme-setter-derive/actions/workflows/auto-release.yml/badge.svg)](#)
[![crates.io](https://img.shields.io/crates/v/pleme-setter-derive.svg)](https://crates.io/crates/pleme-setter-derive)

## Install

```toml
[dependencies]
pleme-setter-derive = "*"
```

## Generation

This crate is mechanically emitted by [`tatara-rust-ast`](https://github.com/pleme-io/tatara-rust-ast). The author surface is a typed `(defmacro …)` Spec — the proc-macro implementation, tests, Nix flake, caixa wrapper, and CI workflow are all generated. See the catalog at `catalog.json` in the parent registry.
