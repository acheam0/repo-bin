# repo-bin
Binary package repository for KISS Linux

## Usage
Just add this repository to your $KISS_PATH. `kiss` handles the submodules automatically

## Build process
Each package is built at https://jenkins.armaanb.net on each push to the submodule repositories. It builds the package in a Docker container and pushes the binary to Wasabi object storage. See the [kiss-ci](kiss-ci) script.

## Packages
| Package   | Version  | Build status                                                                                                                                         | Maintainer |
|----------|----------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| Blender  | 2.91.0 | [![Build Status](https://jenkins.armaanb.net/job/kiss-community/job/blender-bin/badge/icon)](https://jenkins.armaanb.net/job/kiss-community/job/blender-bin/) | @ArmaanB
| CMake  | 3.19.2 | [![Build Status](https://jenkins.armaanb.net/job/kiss-community/job/cmake-bin/badge/icon)](https://jenkins.armaanb.net/job/kiss-community/job/cmake-bin/) | @ArmaanB
| Firefox  | 84.0.1 | [![Build Status](https://jenkins.armaanb.net/job/kiss-community/job/firefox-bin/badge/icon)](https://jenkins.armaanb.net/job/kiss-community/job/firefox-bin/) | @ArmaanB
| GCC  | 10.2.0 | [![Build Status](https://jenkins.armaanb.net/job/kiss-community/job/gcc-bin/badge/icon)](https://jenkins.armaanb.net/job/kiss-community/job/gcc-bin/) | @ArmaanB
| LLVM     | 11.0.0 | [![Build Status](https://jenkins.armaanb.net/job/kiss-community/job/llvm-bin/badge/icon)](https://jenkins.armaanb.net/job/kiss-community/job/llvm-bin/) | @ArmaanB
| Node.js     | 15.4.0 | [![Build Status](https://jenkins.armaanb.net/job/kiss-community/job/nodejs-bin/badge/icon)](https://jenkins.armaanb.net/job/kiss-community/job/nodejs-bin/) | @ArmaanB
| Qt5-webengine     | 5.15.2 | [![Build Status](https://jenkins.armaanb.net/job/kiss-community/job/qt5-webengine-bin/badge/icon)](https://jenkins.armaanb.net/job/kiss-community/job/qt5-webengine-bin/) | @ArmaanB
| Rust     | 1.48.0 | [![Build Status](https://jenkins.armaanb.net/job/kiss-community/job/rust-bin/badge/icon)](https://jenkins.armaanb.net/job/kiss-community/job/rust-bin/) | @ArmaanB
