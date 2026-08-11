# 📉 LOESS / LOWESS Local Regression Visualization

This repository contains the complete Python code to generate a step-by-step animation of **LOESS (Locally Estimated Scatterplot Smoothing)** using custom synthetic data, sliding window fitting, and validation-based bandwidth (span) tuning.

## 🎬 Features
- **Synthetic Data Generation**: Damped multi-frequency sine/cosine function.
- **Kernel Weighting**: Tricube kernel function implementation.
- **Sliding Window Visualizer**: Dynamic display of local weighted least squares fitting.
- **Hyperparameter Optimization**: Automated validation MSE evaluation for optimal span selection.

## 🛠️ Requirements
```bash
pip install numpy matplotlib scikit-learn imageio-ffmpeg
