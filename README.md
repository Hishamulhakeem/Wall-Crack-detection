# Wall Crack Detection 🧱🧠

This project uses a Convolutional Neural Network (CNN) built with TensorFlow and Keras to classify images of walls into two categories:
- **Cracks**
- **Non Cracks**

The model is trained on a custom dataset and performs binary classification using a simple custom CNN architecture.

---

## 📁 Dataset

The dataset is stored in the `data/` directory 

## 🏗️ Model Architecture

The CNN consists of:
- 3 Convolutional layers (with increasing filters: 32, 64, 128)
- 3 Max Pooling layers
- 1 Flatten layer
- 1 Dense layer with 512 units and ReLU activation
- Output Dense layer with 1 unit and Sigmoid activation for binary classification

---

## 🧪 Training

The data is split as:
- 80% Training
- 20% Validation

The model is trained using:
- **Adam Optimizer**
- **Binary Crossentropy Loss**
- **Accuracy** as evaluation metric


