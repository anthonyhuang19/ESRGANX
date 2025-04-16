# Adapting ESRGAN for Enhanced Super-Resolution Experiments 📷⚡

## Overview 📌
This repository encapsulates comprehensive experiments focused on adapting **Enhanced Super-Resolution Generative Adversarial Networks (ESRGAN)** for high-quality image super-resolution tasks. The core objective is to push the boundaries of ESRGAN's performance in transforming low-resolution images into sharp, high-resolution outputs.

## Key Features 🌟
- **Enhanced Image Resolution**: Restores high-frequency details and fine textures
- **Optimized Architecture**: Modified ESRGAN for improved performance
- **Real-World Applications**: Medical imaging, satellite imaging, general enhancement

## Contents 🗂️
- `esrgan.ipynb`: Full training/evaluation pipeline
- `report.pdf`: Detailed methodology and results

## Installation 🚀
```bash
git clone https://github.com/anthonyhuang19/Adapting-ESRGAN-for-Enhanced-Super-Resolution-Experiments.git
cd Adapting-ESRGAN-for-Enhanced-Super-Resolution-Experiments
```
## 🛠️ Tools & Technologies Used

The following tools and technologies were used to implement and optimize the ESRGAN model:

### Frameworks:
- **TensorFlow / PyTorch**: Powerful deep learning frameworks for model training and fine-tuning.

### Image Processing:
- **OpenCV & PIL**: Libraries for loading, processing, and visualizing images efficiently.

### Data Handling:
- **NumPy & Pandas**: Key libraries for manipulating and processing data during the training and evaluation stages.

### Visualization:
- **Matplotlib & Seaborn**: Used to create visual plots for comparing training results and performance metrics.

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
- **LinkedIn**: [Anthony Huang](https://www.linkedin.com/in/anthonyhuang1909/)
