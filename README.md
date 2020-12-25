# repo-bin
Binary package repository for KISS Linux

## Usage
Just add this repository to your $KISS_PATH. `kiss` handles the submodules automatically

## Build process
Each package is built at https://jenkins.armaanb.net on each push to the submodule repositories. It builds the package in a Docker container and pushes the binary to Wasabi object storage. See the [kiss-ci](kiss-ci) script.

## Packages
| Package   | Version  | Build status                                                                                                                                         | Maintainer |
|----------|----------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| Firefox  | 84.0.1   | [![Build Status](https://jenkins.armaanb.net/job/kiss-community/job/firefox-bin/job/main/badge/icon)](https://jenkins.armaanb.net/job/kiss-community/job/firefox-bin/job/main/) | @ArmaanB
| LLVM     | 11.0.0-1 |[![Build Status](https://jenkins.armaanb.net/job/kiss-community/job/llvm-bin/job/main/badge/icon)](https://jenkins.armaanb.net/job/kiss-community/job/llvm-bin/job/main/) | @ArmaanB
| Rust     | 1.48.0-1 |[![Build Status](https://jenkins.armaanb.net/job/kiss-community/job/rust-bin/job/main/badge/icon)](https://jenkins.armaanb.net/job/kiss-community/job/rust-bin/job/main/) | @ArmaanB
