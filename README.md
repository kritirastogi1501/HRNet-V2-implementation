HRNetV2 for Facial Landmark Detection
High-Resolution Representation Learning for Precise Keypoint Localization
A professional-grade implementation of HRNetV2 (High-Resolution Network Version 2) for facial landmark detection, designed to preserve high-resolution feature maps throughout the network for superior spatial precision.
This project focuses on accurate prediction of facial keypoints from images using multi-scale feature fusion and robust deep learning practices.

Overview
Traditional CNN architectures progressively downsample feature maps, often losing important spatial details required for landmark localization.
HRNetV2 solves this by:
Maintaining high-resolution representations through the entire network
Performing parallel multi-resolution feature extraction
Repeatedly fusing features across resolutions
Delivering highly precise landmark predictions

This implementation is optimized for facial landmark detection tasks, especially where accurate coordinate regression is critical.

Features
Core Highlights-
HRNetV2 backbone architecture
Multi-stage parallel branches
Repeated high-to-low and low-to-high fusion
Heatmap / coordinate-based landmark prediction
Data preprocessing for .pts landmark annotations
Custom dataset loader for facial landmark datasets
Training + validation pipeline
Visualization of predicted landmarks

Inspired by the original HRNet paper:
“Deep High-Resolution Representation Learning for Visual Recognition”
AdamW optimizer support
Group Normalization for stable small-batch training
Modular and scalable architecture
