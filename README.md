# nes-rs [![Build Status](https://travis-ci.org/Reshurum/nes-rs.svg?branch=master)](https://travis-ci.org/Reshurum/nes-rs) [![License](https://img.shields.io/badge/license-MIT%2FApache--2.0-blue.svg)](CONTRIBUTING.md)

nes-rs is an incomplete NES emulator written in Rust. The name is subject
to change once I find something more catchy.

## Goals

This is a list of my long term goals for the project that I do not expect
to be done for a long time.

* Make the emulator as accurate as possible
* Automated testing of the CPU with existing test roms
* Automated testing of the PPU (frame by frame compare)
* RPC-like api to allow external scripts change the emulator state
* Full featured debugger accessible through a command-line interface

## Building and Running

For now the only dependency is rust itself, however this is subject to change
once I start working on the PPU and I plan to use SDL.

## Literature

* [obelisk 6502 documentation](http://www.obelisk.me.uk/6502/)
* [NESdev wiki](http://wiki.nesdev.com/w/index.php/Nesdev_Wiki)
* [6502.org](http://www.6502.org/tutorials/6502opcodes.html)

## License

Licensed under either of the following licenses at your option:

 * Apache License, Version 2.0, ([LICENSE-APACHE](LICENSE-APACHE) or
   http://www.apache.org/licenses/LICENSE-2.0)
 * MIT license ([LICENSE-MIT](LICENSE-MIT) or
   http://opensource.org/licenses/MIT)

## Contribution

Please read [CONTRIBUTING.md](CONTRIBUTING.md) before submitting a PR!
