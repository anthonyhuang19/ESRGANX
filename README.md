# Adapting ESRGAN for Enhanced Super-Resolution Experiments 📷⚡

## Overview 📌
This repository encapsulates comprehensive experiments focused on adapting **Enhanced Super-Resolution Generative Adversarial Networks (ESRGAN)** for high-quality image super-resolution tasks. The core objective is to push the boundaries of ESRGAN's performance in transforming low-resolution images into sharp, high-resolution outputs.

## Key Features 🌟
- 🧠 **From-Scratch Implementation**  
  Built without using pretrained weights or third-party ESRGAN frameworks.
- 🎨 **Enhanced Image Resolution**  
  Effectively restores textures, edges, and fine details in degraded images.
- ⚙️ **Optimized Architecture**  
  Based on Residual-in-Residual Dense Blocks (RRDB), with refinements for training stability and output quality.

## Contents 🗂️
- `esrgan.ipynb`: Full training/evaluation pipeline
- `report.pdf`: Detailed methodology and results

## Installation 🚀
```bash
git clone https://github.com/anthonyhuang19/Adapting-ESRGAN-for-Enhanced-Super-Resolution-Experiments.git
cd ESRGANX
```
## 🛠️ Tools & Technologies

The development and optimization of **ESRGAN-X** leveraged a modern deep learning stack, including tools for model training, image manipulation, data processing, and performance visualization.

### ⚙️ Frameworks
- **PyTorch**  
  Used as the primary deep learning framework for building, training, and evaluating the ESRGAN architecture. Offers dynamic computation graphs and robust GPU acceleration.

### 🖼️ Image Processing
- **OpenCV**  
  Employed for efficient image manipulation, resizing, augmentation, and file I/O.
- **Pillow (PIL)**  
  Used alongside OpenCV for flexible image loading and pixel-level preprocessing.

### 📊 Data Handling
- **NumPy**  
  Fundamental for tensor operations, array transformations, and efficient numerical computation.
- **Pandas**  
  Utilized for organizing metadata, managing experiment logs, and tracking training statistics.

### 📈 Visualization & Monitoring
- **Matplotlib**  
  Used to plot training curves (loss, PSNR, SSIM) and visualize sample outputs.
- **Seaborn**  
  Enhances Matplotlib aesthetics for better interpretability of trends and performance metrics.

## 🔬 Experimental Workflow

### 1. Data Preprocessing 🌐
Preprocessing is crucial for preparing data to be fed into ESRGAN. We perform:
- **Image resizing** to a consistent shape.
- **Normalization** to scale pixel values for stable training.

### 2. Model Training 🏋️‍♀️
During training, the focus is on optimizing the adversarial loss function to improve both the perceptual quality of images and the restoration of fine details.

### 3. Model Evaluation 📊
We evaluate model performance using standard metrics:
- **PSNR (Peak Signal-to-Noise Ratio)**: Measures image quality.
- **SSIM (Structural Similarity Index)**: Assesses perceptual similarity between original and generated images.

Additionally, visual comparisons are made between the model's output and ground truth images.

## 🤝 Contributing

We welcome contributions to this project! To get involved:
1. **Fork the repository**.
2. **Modify the code** or add new features.
3. **Submit a Pull Request**.

Feel free to report any issues or suggestions for improvement in the Issues tab.

## 📧 Contact
- **GitHub**: [@anthonyhuang19](https://github.com/anthonyhuang19)
