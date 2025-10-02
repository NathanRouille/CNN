# CNN Labs with PyTorch 

This repository contains two practical sessions on Convolutional Neural Networks.  
The labs explore both **training CNNs from scratch** and interpretability : **understanding CNNs with visualization (Deep Dream) and adversarial examples**.


## 1. LeNet on MNIST & CIFAR-10
- Training LeNet-5 on MNIST digits.
- Extension to CIFAR-10 (RGB images).
- Implementations of:
  - Early stopping
  - Data augmentation
  - Dropout regularization
- Comparison with ResNet18 (with and without pre-training) from `torchvision.models` to highlight the benefits of deeper architectures.


## 2. Interpretability : Deep Dream & Adversarial Examples
- Using a pre-trained VGG19 network from `torchvision.models`.
- **Deep Dream algorithm**:
  - Gradient ascent on images to maximize feature activations.
  - Visualizing what the network "sees" at each layer.
- **Adversarial examples**:
  - Gradient-based perturbations that fool the network.
  - Forcing misclassification.
  - Illustration of vulnerabilities in CNNs.
