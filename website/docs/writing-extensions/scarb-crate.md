# Using Scarb as a library <Badge type="warning" text="deprecated" />

Scarb is a [Rust](https://rust-lang.org) crate which can be used as a regular library in Rust applications.
We publish each release of Scarb to [crates.io](https://crates.io), the official package registry for Rust.

This crate serves as an API for writing custom extensions for Scarb.
It is not recommended to link to Scarb in regular unrelated applications, for this it is preferred to interact with
Scarb binary.

::: tip
The combination of calling scarb command with the `--json` flag, and the `scarb metadata` command should cover all use
cases for communicating with Scarb from outside world.
:::

<BigLink href="https://crates.io/crates/scarb">
    Go to Scarb on crates.io
</BigLink>

## Crate documentation

Documentation about Scarb crate features is maintained in source code.
Like for any public Rust crate, rendered documentation is hosted on [docs.rs](https://docs.rs).

<BigLink href="https://docs.rs/scarb">
    Go to Scarb documentation on docs.rs
</BigLink>