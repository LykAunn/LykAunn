# 👋 Hi, I'm Lyk Aunn

**Artificial Intelligence & Computer Science @ The University of Edinburgh**  
*Systems Architecture | Engine Programming | High-Performance Computing*

I focus on the intersection of **low-level systems**, and **high-performance computing**. I enjoy peeling back the layers of abstraction to understand how hardware and software truly interact—from memory allocators and CPU caches to bare-metal graphics pipelines.

-----

### 🛠️ Tech Stack & Tooling

*   **Systems & Low-Level:** C++, Rust, C, MIPS Assembly
*   **General Purpose:** Java, Python, TypeScript
*   **Graphics & UI:** SDL2, Ratatui
*   **Tooling & Verification:** CMake, ASan/UBSan, doctest, Git, Linux
*   **Embedded & Real-Time:** Embassy (Async Rust), CANopen, STM32

-----

### 🏗️ Featured Projects

#### 📐 [3D Software Rasterizer](https://github.com/LykAunn) | *C++, CMake*
A 3D rendering pipeline built from scratch without hardware graphics APIs.
*   Implemented homogeneous MVP matrix transformations, perspective division, and viewport mapping.
*   Engineered bounding-box triangle rasterization using 2D barycentric edge functions and per-pixel z-buffering.
*   Enforced memory safety and invariants using CMake test targets with ASan, UBSan, and `doctest`.

#### ⚡ [Trade Matching Engine](https://github.com/LykAunn/Trade-Matching-Engine) | *Rust, Ratatui*
A high-performance limit order book and execution system.
*   Architected a price-time priority order book using `BTreeMap` bid/ask sides for $O(\log n)$ price-level lookups and $O(1)$ order removal.
*   Implemented deterministic matching with partial fills and structured execution events across MPSC channels.
*   Built a real-time TUI utilizing a multi-threaded feed simulator to stream execution data.

#### 🦀 [CHIP-8 Virtual Machine](https://github.com/LykAunn/Chip8-Emulator) | *Rust, SDL2*
A cycle-accurate emulation of the CHIP-8 interpreted programming language.
*   Engineered an $O(1)$ function-pointer dispatch table for the 35-opcode ISA, eliminating conditional branch overhead.
*   Managed the fetch-decode-execute cycle, bitwise XOR sprite collision detection, and ownership-aware SDL2 buffers.

#### 🧠 [Multi-Level Cache Simulator](https://github.com/inf2c-cs-2022/coursework-2-c-LykAunn) | *C*
A functional simulator of a CPU cache hierarchy (L1/L2).
*   Designed a configurable n-way set-associative cache utilizing 3D pointer arrays and a global counter-based LRU policy.
*   Verified zero memory leaks across complex dynamic allocations using Valgrind.

-----

### 📚 Currently Leveling Up

I believe a great systems engineer is a perpetual student. Right now, my technical focus involves:

*   **Graphics Pipeline Internals:** Expanding my software rasterizer to include perspective-correct texture mapping and advanced shading models.
*   **Low-Latency Infrastructure:** Studying lock-free data structures and cache-line optimization for order-matching engines.
*   **Engineering Prep:** Deepening my understanding of C/C++ memory mechanics, pointer arithmetic, and algorithmic complexity for tier-one software engineering applications.

-----

### 📫 Connect with Me

*   **Email:** [lykaunn@gmail.com](mailto:lykaunn@gmail.com)
*   **LinkedIn:** [linkedin.com/in/lykaunnliu](https://linkedin.com/in/lykaunnliu/)
