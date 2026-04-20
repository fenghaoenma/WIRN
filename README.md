# WIRN
Wavelet Iterative Reconstruction Network for Sparse Projection Domain CT
# WIRN: Projection-Centric Iterative Reconstruction Framework

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![PyTorch](https://img.shields.io/badge/PyTorch-1.10+-red.svg)](https://pytorch.org/)

> **Official PyTorch Implementation of the paper:** > *"Wavelet Iterative Reconstruction Network for Sparse Projection Domain CT"* > 

## 📢 News
* **[Date]**: The code and pre-trained models will be fully released upon the paper's acceptance. Stay tuned!

## 💡 Overview
**WIRN** is a novel projection-centric iterative reconstruction framework designed for highly efficient and accurate medical image reconstruction. By leveraging dual-domain consistency algorithms and wavelet-based projection manifold restoration, WIRN achieves state-of-the-art performance with remarkably fast convergence.

### Key Highlights:
* **Superior Accuracy:** Outperforms 8 current State-of-the-Art (SOTA) baselines by an average margin of **2 dB** across all evaluated sparsity levels.
* **Extreme Efficiency:** Achieves a processing speed of **2.91 FPS** and converges in just **5 iterations**.
* **Robust Evaluation:** Extensively validated on both public (AAPM) and large-scale clinical (Xiangya) datasets using PSNR and SSIM metrics.

---
## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/WIRN.git](https://github.com/yourusername/WIRN.git)
   cd WIRN
