# Residual_MS_ZCP_UNet
## Overview
This repository presents a deep learning-based framework for accurate breast tumor segmentation from ultrasound images. The proposed Residual Multi-Scale ZCP U-Net integrates multi-scale feature extraction, residual learning, and an attention mechanism (ZCP block) to improve segmentation performance under challenging conditions such as speckle noise, low contrast, and irregular tumor boundaries.
## Key Features
- Multi-scale feature extraction for capturing fine and coarse details
- Residual connections for stable and efficient training
- ZCP attention (channel + spatial attention) for enhanced feature representation
- Robust performance on breast ultrasound images
- Hybrid loss function (BCE + Dice) for improved segmentation
## Results
The proposed model achieves:
- Dice Coefficient: 92.77%
- IoU: 86.58%
- Accuracy: 98.81%
