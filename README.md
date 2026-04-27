# UK-NNSS High Performance Linpack (HPL) benchmark

This repository contains the instructions for running the standard HPL
benchmark as part of the UK-NNSS procurement.

> [!IMPORTANT]
> Please do not contact the benchmark or code maintainers directly with any questions. All questions must be submitted via the procurement response mechanism.

## Software

Tarball: [HPL](https://www.netlib.org/benchmark/hpl/)

## Building the benchmark

> [!CAUTION]
> All results submitted should be based on a version of HPL that
meets [Top500 submission guidelines](https://top500.org/resources/frequently-asked-questions/).

Guidance on building the benchmark code is provided within the HPL package.

### Pre-approved code modifications

Bidders are permitted to modify the benchmark in any way compatible with
Top500 submission guidelines.

## Running the benchmark

### Required tests

The bidder is required to run the following tests

- Single node HPL performance
  + Single node HPL runs across all compute nodes that run for at least 1 hour.
  + The difference between the maximum measured single-node performance and the minimum
    measured single-node performance must be equal to or less than 5% of the mean measured single-node performance.
- Full system HPL performance
  + A full system run of HPL using a minimum of 99% of all compute nodes under Top500/Green500 
    conditions that runs to completion.
  + This run should provide data for a valid Top500/Green500 submission including power draw data.

## License

This benchmark description and associated files are released under the MIT license.
