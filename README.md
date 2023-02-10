# Using Rust on the Raspberry Pi Pico

This is a simple template with the [blink exmaple](https://github.com/rp-rs/rp-hal-boards/blob/main/boards/rp-pico/examples/pico_blinky.rs)
with all the necessary additional files to get started propgramming the Raspberry Pi Pico boards using rust.

To start one needs to have installed the `thumbv6m-none-eabi` toolcahin and the `elf2uf2` tool.
To install them, just run
```
rustup toolchain add thumbv6m-none-eabi
cargo install elf2uf2
```
