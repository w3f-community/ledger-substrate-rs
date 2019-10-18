# Rust library for Ledger Kusama app
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![CircleCI](https://circleci.com/gh/ZondaX/ledger-polkadot-rs.svg?style=shield)](https://circleci.com/gh/ZondaX/ledger-polkadot-s)

This package provides a basic Rust client library to communicate with the Kusama/Polkadot App running in a Ledger Nano S/X devices

## Build

- Install rust using the instructions [here](https://www.rust-lang.org/tools/install)
- To build run:
```shell script
cargo build
```

## Run Tests
To run the tests

- Initialize your device with the test mnemonic. More info [here](https://github.com/zondax/ledger-polkadot#set-test-mnemonic)
- run tests using: 
```shell script
cargo test --all
```
