# Image-Depth-Estimation (Stereo Matching)

## Overview

This repository is about Stereo Matching. The goal is to generate accurate disparity maps that can be used for 3D reconstruction, autonomous vehicles, and other applications requiring depth information.

- **Pixel-wise Matching**: Implemented methods include:
    - Sum of Absolute Differences
    - Sum of Squared Differences
- **Window-based Matching**: 
    - Enhanced pixel-wise matching by considering a window of neighboring pixels
    - Optimized using matrix convolution for fast processing
- **Cosine Similarity**: Measured similarity between image patches as an alternative matching cost function


## Installation
1. Clone the Repository
   ```bash
   git clone https://github.com/lbnm203/Image-Depth-Estimation.git

   cd Image-Depth-Estimation
   ```

2. Run Notebook
   ```bash
   pixel-wise-matching.ipynb
   window-based-matching.ipynb
   cosine-window-based.ipynb
   ```

## Results
Disparity maps generated from various matching techniques are stored in the `assets/` directory
