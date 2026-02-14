---
title: "SIMD Matrix Multiplication"
excerpt: "High-performance SIMD-optimized matrix multiplication using AVX intrinsics, achieving ~8x speedup over standard implementations."
collection: portfolio
---

## SIMD Matrix Multiplication

A C++ implementation comparing standard matrix multiplication with SIMD-optimized (AVX) matrix multiplication, demonstrating significant performance improvements through hardware-level parallelism.

### Key Results
- Achieved approximately **8x speedup** over non-optimized C++ implementation using AVX SIMD instructions
- Tested on matrices up to 10,000 x 10,000 dimensions
- Standard implementation: 95.57 seconds for 1000x1000 matrix multiplication
- SIMD implementation: 12.28 seconds for the same operation

### Approach
- Uses `_mm256_loadu_ps`, `_mm256_mul_ps`, `_mm256_add_ps`, and `_mm256_hadd_ps` AVX intrinsics
- Processes 8 single-precision floating-point values simultaneously
- Implements matrix transpose optimization for cache-friendly access patterns

### Technologies
- C++, AVX/SIMD Intrinsics, x86 Architecture

[[GitHub]](https://github.com/cglosner/SIMD_Matrix)
