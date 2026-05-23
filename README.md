# Hi, I'm Mohammad Reza Bathaei 👋
### Embedded Systems & Edge AI Engineer

Focused on bridging the divide between high-level deep learning concepts and real-time, bare-metal hardware constraints. I build highly deterministic, framework-free execution paths optimized for performance-critical edge computing.

---

## 🛠️ Core Technical Stack

* **Languages & Paradigms:** C++17/C++20 (Bare-Metal, Zero-Heap Allocation), Python, Object-Oriented Design, Concurrent Systems.
* **Vector Execution & Hardware Optimization:** SIMD Vectorization, Intel AVX2, AMD Fused Multiply-Accumulate (FMA), Cache-Aligned Memory Layouts.
* **Libraries & Interfaces:** Eigen Linear Algebra, Inter-Process Communication (IPC via standard I/O pipes), Matplotlib Visualization, JSON Serialization.
* **Core Domains:** Graph Neural Networks (GNNs), Physics-Informed Neural Networks (PINNs), Real-Time Operating Systems (RTOS) concepts, Digital Signal Processing.

---

## 🚀 Featured Project: ARGUS-Q Engine

### [AETHER-Q: Bare-Metal Graph Neural Network Inference Engine](https://github.com/MHR-Bathaei/AETHER-Q)
An ultra-low latency, framework-free C++ inference engine designed to execute localized Graph Neural Networks on space-constrained edge nodes. 
* **Performance:** Achieved a blistering mean inference latency of **4.10 microseconds** via manual 256-bit SIMD register acceleration (`-mavx2`, `-mfma`).
* **Architecture:** Implemented as a resident background microservice daemon communicate-linked via real-time JSON pipelines to frontend visualizations, boasting zero runtime heap fragmentation.
* **Safety Integration:** Features a native, mathematical validation layer executing parallel Maxwellian divergence checks directly inside the inference execution sequence.

---

## 📈 Engineering Philosophies
* **Hardware is Hard, Software Must Be Fast:** Don't throw compute at a software bottleneck. Optimize the instruction paths.
* **Deterministic Execution over Hype:** Memory safety and fixed runtime baselines are critical requirements for embedded safety compliance.
