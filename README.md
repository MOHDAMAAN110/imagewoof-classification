🐺 ImageWoof Classification with Modified Pooling Layers
📌 Project Overview

This project showcases deep learning on the ImageWoof dataset (10 dog breeds 🐶), a subset of ImageNet.
I trained a ResNet18-based neural network with:

✅ Standard PyTorch DataLoader using ImageFolder
✅ Modified pooling layer (AdaptiveAvgPool2d) at the end of the network
✅ Training on Google Colab GPU
✅ Achieved stable results within just 10 epochs 🎯

This project extends my earlier Imagenette experiment by applying the same pipeline to ImageWoof.

🚀 Key Features

Dataset: ImageWoof (10 classes of dog breeds)

Framework: PyTorch

Training: 10 epochs on Colab GPU

Model Modifications:

Replaced default ResNet18 average pooling with AdaptiveAvgPool2d

Adjusted final fully connected layer for 10-class classification

Results: Stable accuracy achieved on validation set

📂 Repository Structure
📦 ImageWoof-Classification
 ┣ 📜 ImageWoof_CustomNet.ipynb   # Main training notebook
 ┣ 📜 README.md                   # Project overview (this file)

📊 Results & Observations

Model successfully trained on 10 ImageWoof classes

Modified pooling improved adaptability in feature learning

Training pipeline can be easily extended to Imagenette / ImageWoof

💡 Future Work

Experiment with ResNet/EfficientNet backbones

Add accuracy/loss plots for better visualization

Test model on real-world dog images

✨ Why This Project Matters

This project demonstrates my ability to:

Handle real-world image datasets efficiently

Modify and fine-tune neural network architectures

Build an end-to-end pipeline: data → model → training → results → documentation

👨‍💻 Author: Mohd Amaan
📧 Contact: mohdamaan40963@gmail.com
.
