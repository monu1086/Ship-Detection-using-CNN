# Ship-Detection-using-CNN
# 🚢 Ship Detection in Satellite Images using CNN

This project focuses on detecting ships in satellite images using a Convolutional Neural Network (CNN). The model is trained on the ShipsNet dataset and classifies whether a given image contains a ship or not.

---

## 📁 Dataset

The project uses the [ShipsNet dataset](https://www.kaggle.com/datasets/rhammell/ships-in-satellite-imagery). It contains:

- 80x80 RGB satellite images
- Labels: `1` for ship, `0` for no-ship

Make sure to place the dataset in:

---

## 🧠 Model

- Model: ResNet-18 (pretrained on ImageNet)
- Task: Binary classification (Ship vs No Ship)
- Input image size: Resized to 224x224
- Loss function: CrossEntropyLoss
- Optimizer: Adam

---

## 🚀 How to Run

1. Install required libraries:
```bash

