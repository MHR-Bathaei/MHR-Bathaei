# Mohammad Reza Bathaei

**ML Systems & Inference Engineer** — I build at the lowest layers of AI execution.  
Bare-metal C++, zero-allocation memory discipline, and hardware-accelerated inference pipelines.  
Currently transitioning from CPU SIMD optimization into GPU kernel engineering and LLM inference infrastructure.

---

## Core Stack

**Languages:** C++17/C++20, C, Python  
**Hardware Acceleration:** Intel AVX2, FMA, SIMD Vectorization, Cache-Aligned Memory Layouts  
**GPU (Active Learning):** CUDA C++, Triton — porting existing SIMD kernels to GPU  
**Inference & ML:** Graph Neural Networks, Physics-Informed Neural Networks, Transformer Architecture  
**Systems:** Zero-Heap Allocation, RTOS Concepts, IPC, Real-Time Telemetry Parsing  
**Protocols:** CCSDS Space Packet Protocol (spacecraft telemetry standard)

---

## Projects

### [AETHERQ](https://github.com/MHR-Bathaei/AETHERQ) — Bare-Metal GNN Inference Engine
Zero-heap C inference engine for Graph Neural Networks on edge hardware.  
**4.10µs mean inference latency** via manual 256-bit SIMD (AVX2/FMA) register acceleration.  
Framework-free. Zero runtime heap fragmentation. Runs as a background microservice daemon  
with real-time JSON pipeline output and integrated Maxwellian divergence validation.

`C` `AVX2` `FMA` `SIMD` `Inference` `Edge AI` `Zero-Allocation`

---

### [ECLIPSE-V](https://github.com/MHR-Bathaei/ECLIPSE-V) — Real-Time Object Detection Engine
Native C++ YOLO inference engine optimized for robotic telemetry applications.  
**52.9+ FPS** sustained throughput. Contiguous memory design, zero-overhead execution path,  
bypasses heavy frameworks entirely.

`C++` `Object Detection` `YOLO` `Real-Time` `Zero-Allocation` `Robotics`

---

### [zero-alloc-ccsds-engine](https://github.com/MHR-Bathaei/zero-alloc-ccsds-engine) — Spacecraft Telemetry Parser
High-throughput C++17 demultiplexer for real-time parsing of CCSDS Space Packet Protocol streams.  
CCSDS is the telemetry standard used by NASA, ESA, and JAXA in operational spacecraft.  
Designed for deterministic low-latency processing on edge hardware under hard real-time constraints.

`C++17` `CCSDS` `Spacecraft` `Telemetry` `Space` `Real-Time` `Zero-Allocation`

---

## What I'm Building Toward

My background is in squeezing maximum performance out of constrained hardware at the CPU level —  
zero-allocation design, manual vectorization, deterministic execution paths.

I'm now applying that same discipline to GPU kernel engineering and LLM inference infrastructure:  
porting SIMD-optimized kernels to CUDA, studying transformer inference internals (FlashAttention,  
PagedAttention, quantization), and working toward meaningful contributions to open-source  
inference engines like llama.cpp.

The hardware changes. The discipline doesn't.

---

## Engineering Principles

- Memory is a first-class constraint, not an afterthought
- Benchmark everything — intuition without numbers is opinion
- Deterministic execution over convenient abstractions
- Understand the hardware before you trust the framework

---

*Open to collaboration, feedback on my projects, and opportunities in ML inference infrastructure.*  
*Master's student in AI — actively building in public.*
