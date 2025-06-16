# 🧠 N-Body 3D Optimisation Project

This repository presents an optimized implementation of the **N-Body problem in 3D**, written in **C**, and enhanced with **AVX2**, **OpenMP**, and **MAQAO** profiling tools. The project was developed as part of the **High Performance Computing (HPC)** module during my year at **ISTY (IATIC4 – Université Paris-Saclay)**.

---

## 🚀 Summary

- **Language**: C  
- **Technologies**: AVX2 (vectorization), OpenMP (parallelism), MAQAO (performance analysis)
- **Optimization Passes**: 8 (including SoA, `restrict`, loop tiling, unrolling, AVX2 SIMD, etc.)
- **Performance Gain**: from **5 GFLOP/s** to **85 GFLOP/s** → **x17 acceleration**  
- **Tested CPU**: Intel® Core™ i7-6600U  
- **Profiling**: Done via MAQAO micro-architectural analysis

---

## ⚙️ Key Features

- 3D gravitational simulation of particles using double-precision floating point arithmetic.
- Multi-pass transformation from a naive scalar implementation to a highly optimized vector-parallel version.
- Memory and cache optimizations using SoA (Structure of Arrays), data locality and alignment strategies.
- Verified performance improvements with MAQAO performance counters and timeline reports.

---

## ⚠️ Important Notice

> **The full source code is not publicly available in this repository** for academic and licensing reasons.  
> However, if you are interested in the **full source code** or the **complete PDF report**, feel free to **contact me directly via email**:

📩 **rochdi.dardor@ens.uvsq.fr**

---

## 📂 Repo Structure (Partial)

├─ main.c 
     Makefile # For compiling with AVX2 and OpenMP flags
     results/ # Contains performance snapshots & MAQAO outputs
     report-summary.txt # Overview of applied optimizations

---

## ✅ Dependencies

- `gcc` or `clang` with AVX2 and OpenMP support
- MAQAO profiler (optional but recommended)
- Linux environment (Ubuntu/Debian tested)

---

## 📜 License

This project is for **educational and research purposes only**.  
All rights reserved © Rochdi Dardor – ISTY / Université Paris-Saclay – 2025.
