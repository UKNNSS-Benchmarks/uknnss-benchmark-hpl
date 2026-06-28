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
- HPL performance on 50% of the system (or dual-injection portion if applicable)
- HPL performance on full system

All tests should
- Run under Top500/Green500 conditions for at least 1 hour.
- Should provide data for a valid Top500/Green500 submission including power draw data.

## License

This benchmark description and associated files are released under the MIT license.

## Changelog

The following changes to this document have been made since initial release:

| <div style="width:90px">Date</div> | Change |
|-----------:|--------|
| 2026-06-25 | Update required tests |
