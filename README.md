# CUDA_TSP_Accelerator
## 🚀 Introduction
This project implements a **CUDA-accelerated Genetic Algorithm (GA)** to solve the **Traveling Salesman Problem (TSP)**. By leveraging GPU parallelization, we aim to significantly enhance the performance of the GA, a metaheuristic commonly used for solving combinatorial optimization problems like the TSP.

The **Traveling Salesman Problem** is a classic optimization challenge where the goal is to find the shortest path that visits a set of cities exactly once and returns to the starting city. It is widely known for its computational complexity, making it a prime candidate for acceleration through parallel computing.

---

## 🧩 Features
- **CUDA-based Acceleration**: 
  - Parallelized fitness evaluation.
  - Efficient implementation of crossover and mutation operations.
  - Optimized population management and genetic diversity maintenance.
- **Flexible Task Selection**: Customizable for different TSP datasets.
- **Performance Benchmarks**: Includes runtime comparisons of serial vs. CUDA-accelerated implementations.
- **Scalable Design**: Adapts to varying GPU architectures and resources.

---

## 📁 Repository Structure

```plaintext
CUDA_TSP_Accelerator/
├── README.md           # Project overview and setup instructions
├── LICENSE             # License information
├── src/                # Source code
│   ├── host_code/      # Host-side logic for CUDA kernel execution
│   ├── device_code/    # CUDA kernels for GA components
├── data/               # Example datasets for TSP
├── benchmarks/         # Benchmarking scripts and performance results
├── docs/               # Documentation, diagrams, and notes
