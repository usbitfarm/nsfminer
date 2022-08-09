# nsfminer (no stinkin' fees) - Performance fork

## Benchmark
Here's a quick benchmark I did of this fork of nsfminer vs nsfminer vs teamredminer on my RX 480:

original nsfminer: `25.43 mh/s`

this fork of nsfminer: `28.81 mh/s`

> Ethereum (ethash) miner with OpenCL, CUDA and stratum support

**nsfminer** is an Ethash GPU mining application: with nsfminer you can mine every coin which relies on an Ethash Proof of Work.

This is a direct descendent of the Ethminer project at https://github.com/ethereum-mining/ethminer. Since that project
is largely abandoned and unmanaged this personal version is published with the hope that it may continue to be useful. In the spirit
of open source problem reports and pull requests are welcome, but please use git-clang-format on your requests.

## Features

* OpenCL mining
* Nvidia CUDA mining
* realistic benchmarking
* stratum mining without proxy
* Automatic devices configuration
* farm failover

## Table of Contents

- [nsfminer (no stinkin' fees) - Performance fork](#nsfminer-no-stinkin-fees---performance-fork)
  - [Benchmark](#benchmark)
  - [Features](#features)
  - [Table of Contents](#table-of-contents)
  - [Usage](#usage)
    - [Examples connecting to pools](#examples-connecting-to-pools)
    - [Building from source](#building-from-source)
  - [API](#api)
  - [License](#license)

## Usage

**nsfminer** is a command line program. This means you launch it either
from a Windows command prompt or Linux console, or create shortcuts to
predefined command lines using a Linux Bash script or Windows batch/cmd file.
For a full list of available command, please run:

```sh
nsfminer --help
```
Complete list of command options [here](docs/Options.md).

### Examples connecting to pools

Check our [samples](docs/POOL_EXAMPLES_ETH.md) to see how to connect to different pools.

### Building from source

[Instructions](docs/BUILD.md)

## API

[Specifications](docs/API_DOCUMENTATION.md)

## License

Licensed under the [GNU General Public License, Version 3](LICENSE).
