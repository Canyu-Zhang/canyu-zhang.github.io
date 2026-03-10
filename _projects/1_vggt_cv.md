---
layout: page
title: Decoding VGGT Features in 3D with Sparse Convolution
description: Course Project — Computer Vision (Prof. Saining Xie), NYU Shanghai · Sep – Dec 2025
img: assets/img/rhino.png
importance: 1
category: course
---

**Course Project** — Computer Vision, NYU Shanghai (Prof. Saining Xie) &nbsp;|&nbsp; Sep. 2025 – Dec. 2025

---

### Overview

This project explores decoding [VGGT](https://github.com/facebookresearch/vggt) / AnySplat features for 3D Gaussian Splatting using sparse 3D convolutions, replacing the original MLP-based decoder with a ResNet-style architecture that better exploits voxelized spatial structure.

---

### Contributions

- **Feed-forward Gaussian Splatting refinement pipeline** built on top of the VGGT/AnySplat backbone, introducing a ResNet-style sparse 3D convolutional decoder for voxelized feature aggregation.
- **Kernel normalization** for sparse 3D convolutions to stabilize feature aggregation under sparse voxel occupancy, addressing the inconsistent receptive field problem caused by varying numbers of active voxels.

---

### Results

Improved 3D reconstruction quality on standard benchmarks:

| Metric | Baseline | Ours |
|--------|----------|------|
| PSNR ↑ | 22.05 | **23.22** |
| SSIM ↑ | 0.692 | **0.744** |
| LPIPS ↓ | 0.327 | **0.277** |

---

### Stack

PyTorch · [SpConv](https://github.com/traveller59/spconv) · VGGT / AnySplat · Gaussian Splatting
