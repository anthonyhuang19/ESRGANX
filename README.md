# Adapting ESRGAN for Enhanced Super-Resolution Experiments

## Abstract

This paper explores the Enhanced Super-Resolution Generative Adversarial Network (ESRGAN), a state-of-the-art model for single-image super-resolution (SISR). ESRGAN improves upon SRGAN by utilizing Residual-in-Residual Dense Blocks (RRDB) to stabilize training and by employing a relativistic adversarial loss function for improved image realism. Additionally, a pre-activated VGG-based perceptual loss enhances visual quality by preserving textures and brightness coherence. The model demonstrates notable improvements in generating high-quality super-resolution images.

## 1. Introduction

Single Image Super-Resolution (SISR) aims to recover high-resolution images from low-resolution inputs. Despite advancements with SRGAN, artifacts and perceptual quality gaps remained. ESRGAN addresses these limitations by:
1. Using **RRDBs** for deeper networks without batch normalization.
2. Applying **relativistic adversarial loss** for better realism.
3. Leveraging **VGG-based perceptual loss** to preserve fine details.

## 2. Related Work

Recent advances in super-resolution include transformer-based models like SwinIR, diffusion models like SRDiff, and hybrid models combining CNNs and transformers. ESRGAN builds on these methods, offering perceptual quality improvements that rival or exceed previous approaches.

## 3. Methodology

### 3.1 Residual-in-Residual Dense Block (RRDB)
RRDBs enhance deep network training by eliminating batch normalization, preventing artifacts and improving training stability.

### 3.2 Relativistic Adversarial Discriminator
The relativistic discriminator measures the relative realism of generated images, improving texture quality and perceptual fidelity.

### 3.3 Perceptual Loss
ESRGAN uses a VGG-based perceptual loss to ensure high-level semantic details are preserved, improving the visual quality of super-resolved images.

### 3.4 Total Generator Loss
The generator loss in ESRGAN combines perceptual loss, adversarial loss, and content loss to balance visual quality with pixel accuracy.

## 4. Experiment

### 4.1 Training Process
The model was trained on the DIV2K dataset using the Adam optimizer with a learning rate of 1e-4. The training included both perceptual and adversarial losses.

### 4.2 Qualitative Results
ESRGAN outperforms SRGAN and SRCNN in perceptual quality, particularly in preserving textures and generating photorealistic images, as shown by higher MOS ratings.

### 4.3 Dataset Overview
The model was evaluated on the Set5 and Set14 datasets, commonly used to benchmark super-resolution algorithms.

## 5. Conclusion

ESRGAN demonstrated significant improvements in generating high-quality super-resolution images, effectively recovering high-frequency details. With continued refinement and better hardware, ESRGAN's performance is expected to further enhance the quality of super-resolution tasks.
