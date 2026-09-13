# ⚡ Z_Forge — High-Performance LZW Compression & Optimization Benchmarks

[![Language: C](https://img.shields.io/badge/Implementation-C99%20%7C%20Python%203-00599C?style=flat-square&logo=c)](https://github.com/Jaswanth1902/Z_Forge)
[![Algorithms](https://img.shields.io/badge/Algorithm-LZW%20Adaptive%20Dictionary-orange?style=flat-square)](https://github.com/Jaswanth1902/Z_Forge)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](LICENSE)

**Z_Forge** is a dual-implementation benchmark suite comparing native **C** and **Python** implementations of the **Lempel-Ziv-Welch (LZW)** lossless data compression algorithm. Features optimized dictionary trie lookups, variable-length bit packing, and an interactive comparative telemetry dashboard.

---

## ⚡ Architecture & Implementations

```
┌─────────────────────────┐         ┌─────────────────────────┐
│   C Implementation      │         │  Python Implementation  │
│  - Static Trie Dict     │         │  - Hash-table Dict      │
│  - Zero-Copy Bitstream  │         │  - Rapid Prototyping    │
│  - Microsecond Latency  │         │  - Telemetry Generator  │
└───────────┬─────────────┘         └───────────┬─────────────┘
            │                                   │
            └─────────────► JSON Stats ◄────────┘
                                 │
                                 ▼
                    ┌─────────────────────────┐
                    │  HTML5 Evaluation Suite │
                    └─────────────────────────┘
```

---

## 🚀 Quickstart

### Compile and Run C Engine
```bash
cd C_Implementation
gcc -O3 -o lzw_compress lzw.c
./lzw_compress ../sample.txt ../sample_c_lzw.bin
```

### Run Python Benchmark
```bash
cd Python_Implementation
python lzw_benchmark.py
```

---

## 📄 License

Distributed under the [MIT License](LICENSE). Copyright (c) 2026 Jaswanth Reddy.
