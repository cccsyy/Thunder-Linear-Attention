<div align="center">

# ⚡ Thunder Linear Attention

</div>

## 📚 Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [Supported Tasks](#supported-tasks)
- [Project Structure](#project-structure)
- [Evaluation & Validation](#evaluation--validation)
- [Contributing](#contributing)
- [License](#license)

---

## Project Overview

Thunder Linear Attention is an efficient library for linear attention mechanisms, implemented on Ascend NPU to facilitate multi-task transfer and validation. The library supports mainstream tasks in both Computer Vision (CV) and Natural Language Processing (NLP), and is compatible with models like GPT and LLaMA for large-scale pretraining and accelerated inference.
---

## Features

- ⚡ **Linear Complexity Attention**: Overcomes the O(n²) bottleneck of standard self-attention, enabling ultra-long sequence processing
- 🔀 **Multi-task Transfer**: Seamlessly switch between CV and NLP tasks
- 🏆 **Mainstream Model Compatibility**: Supports GPT, LLaMA, and more
- 🧩 **Rich Dataset Support**: Built-in integration with high-quality datasets such as Slimpajama
- 🧪 **Standard Evaluation Tools**: Integration with lm-harness and other evaluation suites

---

## Installation



---

## Quick Start

#### 1. For NLP Language Modeling



#### 2. For CV Tasks (Classification/Segmentation/Detection)



---

## Supported Tasks

- **CV Tasks**
  - High-level: Classification, segmentation, detection, diffusion
  - Low-level: Super-resolution (SR), denoising

- **NLP Tasks**
  - Language modeling: GPT, LLaMA (340M ~ 1.3B parameters)
  - Dataset: Slimpajama (based on the transformers/mindspeed-llm library)
  - Evaluation: lm-harness

---

## Project Structure



---

## Evaluation & Validation



---

## Contributing



---

## License



---


