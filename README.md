# 🚢 Ship Detection in Satellite Images using CNN

This project focuses on detecting ships in satellite images using a Convolutional Neural Network (CNN). The model is trained on the ShipsNet dataset and classifies whether a given image contains a ship or not.

---

## 📁 Dataset

The project uses the [ShipsNet dataset](https://www.kaggle.com/datasets/rhammell/ships-in-satellite-imagery). It contains:

- 80x80 RGB satellite images  
- Labels: `1` for ship, `0` for no-ship

Make sure to place the dataset in the following directory:
```
data/shipsnet/
```

---

## 🧠 Model

- ✅ Model: ResNet-18 (pretrained on ImageNet)  
- ✅ Task: Binary classification (Ship vs No Ship)  
- ✅ Input image size: Resized to 224x224  
- ✅ Loss function: CrossEntropyLoss  
- ✅ Optimizer: Adam

---

## 🚀 How to Run

1. Install required libraries:
```bash
pip install -r requirements.txt
```

2. Run the training script:
```bash
python ship_detection.py
```

3. The trained model will be saved as:
```
ship_detector.pth
```

---

## 🧪 Output Example

```
Epoch 1 completed.
Epoch 2 completed.
...
Model saved!
```

---

## 📦 Requirements

```
torch
torchvision
opencv-python
scikit-learn
numpy
```

Install with:

```bash
pip install -r requirements.txt
```

---

## 📊 Future Work

- Upgrade to object detection using YOLOv5 or Faster R-CNN  
- Add evaluation metrics: accuracy, precision, recall, F1-score  
- Visualize predictions with bounding boxes  
- Deploy as a web app using Flask or Streamlit

---

## 📌 Project Structure

```
ship-detection-project/
│
├── data/
│   └── shipsnet/
├── ship_detection.py
├── requirements.txt
└── README.md
```

---

## 👤 Author

**Monish Sai**  
Machine Learning & Computer Vision Enthusiast  
[LinkedIn](https://www.linkedin.com/in/monishmuddaka/) • [Email](monumuddaka@gmail.com)
