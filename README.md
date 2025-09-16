Combined GPT FlashAttention Benchmark Suite

This repository provides a comprehensive benchmarking toolkit for evaluating FlashAttention against traditional math-based attention backends in large-scale language models.

What This Notebook Does

FlashAttention vs Math Backend Comparison
Benchmarks the performance differences between FlashAttention and PyTorch’s default math backend.

Optimized Benchmarks for Longer Sequences
Includes tests for scaling efficiency on longer input lengths.

Automated Diagnostics & Environment Checks
Runs GPU, CUDA, and PyTorch diagnostics to verify FlashAttention compatibility.

Results Analysis & Visualization
Provides plots and tables to compare throughput, latency, and memory usage across setups.

Target Hardware

Designed for NVIDIA A100 GPUs

Uses bfloat16 (BF16) precision for efficiency.

Compatible with models like GPT-NeoX-20B.

Key Features

GPU cleanup routines for reproducible results.

Automated prompt generation for diverse benchmark scenarios (generic text, math reasoning, etc.).

Configurable benchmarking pipeline to extend for other models or precision modes.

Example Outputs

Performance charts showing latency vs. sequence length.

Throughput comparisons between FlashAttention and baseline methods.
