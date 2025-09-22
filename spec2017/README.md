# SPEC CPU2017

Since SPEC 2017 is not publicly available, we only publish the results of
benchmarking here. The x86-64 benchmarks are run on an AMD Ryzen 9 7950X and
the Arm64 benchmarks on a Mac Mini M2.

The numbers listed here represent the percent overhead compared to native code
for each benchmark.

Benchmarks were run with LLVM 20.1.7 with LTO enabled.

## Summary

Geomean overheads on M2 (aarch64) and 7950X (x86-64).

* `aarch64-lfi`: 6.9%
* `aarch64-lfi-stores`: 1.6%
* `aarch64-lfi-jumps`: 0.9%
* `x86_64-lfi`: 7.1%
* `x86_64-lfi-stores`: 5.4%
* `x86_64-lfi-jumps`: 4.4%
