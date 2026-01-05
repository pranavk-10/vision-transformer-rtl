# Vision Transformer Hardware Accelerator (RTL)

This project implements a **tiny Vision Transformer (ViT) inference accelerator**
using **Verilog RTL**, targeting FPGA-based edge AI deployment.

The goal is to bridge **machine learning models and digital hardware design**
by mapping key ViT components (patch embedding, attention, feed-forward layers)
into hardware-friendly architectures.

---

## Project Scope
- Tiny ViT (inference only)
- Fixed-point arithmetic (INT8 / INT16)
- Single-head self-attention
- FPGA-oriented RTL design

---

## Architecture Overview
The design consists of the following blocks:
- Patch Embedding Engine
- Linear MAC Engine
- Self-Attention Core
- Feed Forward Network
- Controller FSM

---

## Directory Structure
- `software/` – Python reference model and weight export
- `hardware/rtl/` – Verilog RTL modules
- `hardware/tb/` – Testbenches
- `docs/` – Architecture and design documentation
- `results/` – Verification and resource reports

---

## Status
🚧 Work in progress – Day 1: ViT fundamentals

---

## Author
Pranav Kamble
