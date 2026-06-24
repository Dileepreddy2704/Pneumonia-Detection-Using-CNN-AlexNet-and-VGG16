# 🩺 Pneumonia Detection Using CNN, AlexNet, and VGG16

## 📌 Overview

Pneumonia is a serious lung infection that can be life-threatening if not diagnosed early. This project leverages Deep Learning and Computer Vision techniques to automatically detect pneumonia from Chest X-ray images. Multiple Convolutional Neural Network (CNN) architectures, including a custom CNN, AlexNet, and VGG16, were implemented and evaluated to classify X-ray images as either **Normal** or **Pneumonia**.

The project demonstrates the potential of AI-assisted medical diagnosis by providing an automated and efficient pneumonia detection system.

---

## 🎯 Objectives

- Develop an automated pneumonia detection system using Chest X-ray images.
- Implement and compare different deep learning architectures.
- Improve diagnostic accuracy using transfer learning techniques.
- Evaluate model performance for medical image classification tasks.

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## 📂 Dataset

The project uses a Chest X-ray dataset containing images categorized into:

- **Normal**
- **Pneumonia**

Dataset Structure:

```text
Dataset/
├── train/
│   ├── NORMAL/
│   └── PNEUMONIA/
├── val/
│   ├── NORMAL/
│   └── PNEUMONIA/
└── test/
    ├── NORMAL/
    └── PNEUMONIA/
```

---

## 🔍 Methodology

### 1. Data Preprocessing
- Image resizing and normalization
- Data augmentation
- Train-validation-test split

### 2. Custom CNN Model
- Convolutional Layers
- Max Pooling Layers
- Fully Connected Layers
- ReLU Activation Functions

### 3. AlexNet Architecture
- Deep convolutional network implementation
- Batch normalization
- Dropout regularization
- Feature extraction from X-ray images

### 4. VGG16 Transfer Learning
- Pre-trained ImageNet weights
- Transfer learning approach
- Fine-tuning for pneumonia classification

---

## 🚀 Features

- Automated pneumonia detection from Chest X-rays
- Deep learning-based image classification
- Custom CNN implementation
- AlexNet architecture implementation
- VGG16 transfer learning model
- Data augmentation for improved performance
- Model evaluation and comparison
- Visualization of training and validation metrics

---

## 📊 Results

The models were trained and evaluated on Chest X-ray images to classify patients as either Normal or Pneumonia.

Key outcomes include:

- Successful implementation of multiple CNN architectures.
- Comparative analysis of CNN, AlexNet, and VGG16 models.
- Improved classification performance using transfer learning.
- Demonstrated effectiveness of deep learning for medical image diagnosis.

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/pneumonia-detection-using-cnn.git
cd pneumonia-detection-using-cnn
```

Install dependencies:

```bash
pip install tensorflow keras numpy pandas matplotlib seaborn
```

---

## ▶️ Usage

1. Download and organize the Chest X-ray dataset.
2. Update dataset paths in the notebook.
3. Open the notebook:

```bash
jupyter notebook Final_classification_of_pneumonia_using_cnn.ipynb
```

4. Run all cells sequentially to:
   - Load and preprocess data
   - Train the models
   - Evaluate performance
   - Generate predictions

---

## 📈 Future Enhancements

- Implement ResNet and EfficientNet architectures
- Hyperparameter optimization
- Explainable AI using Grad-CAM
- Multi-class lung disease classification
- Web-based deployment using Streamlit

---

## 👨‍💻 Author

**Dileep Reddy Gurijala**

---

## 📜 License

This project is developed for educational and research purposes.
