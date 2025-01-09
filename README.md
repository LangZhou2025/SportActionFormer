# SportNeuroTrans Net

## Overview

**SportNeuroTrans Net** is a neuro-inspired Transformer model designed specifically for **sports micro-movement recognition**, which is a crucial research direction in computer vision with wide applications in sports training and analysis. This project addresses the challenges of recognizing subtle and detail-rich movements with complex spatiotemporal characteristics, offering an efficient and accurate solution for real-time applications.

---

## Features

- **Hierarchical Classification Structure**: Progressive recognition from coarse to fine levels to improve the model's ability to distinguish complex movements.
- **Duration-Aware Attention Mechanism**: Dynamically adjusts attention weights based on the duration of movements, effectively handling variable action time spans.
- **Neural Gate Mechanism**: Filters out key action frames to enhance computational efficiency.
- **High Performance**: Outperforms six existing state-of-the-art (SOTA) methods on multiple datasets while significantly reducing computational resource usage.

---

## Datasets Used

The model has been tested on the following commonly used datasets:

- **Gym88**
- **Gym288**
- **UCF101**
- **Diving48**

---

## Results

- **Accuracy**: Achieved state-of-the-art results on all benchmark datasets.
- **Efficiency**: Reduced computational resource usage while maintaining high accuracy.
- **Real-Time Performance**: Designed for scenarios with high real-time requirements.

---

## Installation

### Prerequisites

1. **Python 3.7+**
2. **PyTorch 1.10+**
3. **CUDA 11.0+** (for GPU acceleration)

### Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/SportNeuroTransNet.git
   cd SportNeuroTransNet
