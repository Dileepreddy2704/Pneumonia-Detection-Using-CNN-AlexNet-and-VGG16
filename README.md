# 🩺 Pneumonia Detection Using CNN, AlexNet, and VGG16

## 📌 Overview

Pneumonia is a severe respiratory infection that affects the lungs and can lead to serious health complications if not diagnosed early. This project applies Deep Learning and Computer Vision techniques to automatically detect pneumonia from Chest X-ray images.

Multiple Convolutional Neural Network (CNN) architectures, including a custom CNN, AlexNet, and VGG16, were implemented and evaluated to classify Chest X-ray images as either **Normal** or **Pneumonia**. The project demonstrates the effectiveness of deep learning models in assisting medical image diagnosis and supporting healthcare professionals with faster and more accurate screening.

---

## 🎯 Objectives

- Develop an automated system for pneumonia detection using Chest X-ray images.
- Implement and compare multiple deep learning architectures.
- Improve classification performance through transfer learning techniques.
- Evaluate model effectiveness for medical image analysis applications.

---

## 🚀 Features

- Automated pneumonia detection from Chest X-ray images
- Binary classification: **Normal** vs **Pneumonia**
- Custom CNN model implementation
- AlexNet architecture implementation
- VGG16 transfer learning model
- Image preprocessing and normalization
- Data augmentation techniques
- Model training, validation, and testing
- Performance comparison across multiple architectures
- Visualization of training and validation metrics

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
- Google Drive

---

## 📂 Dataset

The project utilizes a Chest X-ray dataset consisting of images categorized into:

- **Normal**
- **Pneumonia**

### Dataset Structure

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

Images were preprocessed, resized, normalized, and augmented before training the deep learning models.

---

## 🔍 Methodology

### 1. Data Preprocessing

- Image resizing
- Pixel normalization
- Data augmentation
- Dataset splitting for training, validation, and testing

### 2. Custom CNN Model

A Convolutional Neural Network was developed from scratch using:

- Convolutional Layers
- Max Pooling Layers
- Dense Layers
- ReLU Activation Functions
- Dropout Regularization

### 3. AlexNet Architecture

Implemented the AlexNet architecture with:

- Multiple convolutional layers
- Batch normalization
- Max pooling layers
- Fully connected layers
- Dropout regularization

### 4. VGG16 Transfer Learning

Implemented transfer learning using the pre-trained VGG16 model:

- ImageNet pre-trained weights
- Feature extraction
- Fine-tuning for pneumonia classification
- Custom classification layers

---

## 💻 Development Environment

This project was developed and executed entirely in **Google Colab**, leveraging cloud-based GPU resources for efficient deep learning model training and experimentation.

### Google Colab Benefits

- Cloud-based development environment
- GPU acceleration for model training
- Easy integration with Google Drive
- Interactive experimentation and visualization

---

## ▶️ Running the Project

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/pneumonia-detection-using-cnn.git
cd pneumonia-detection-using-cnn
```

### 2. Open the Notebook in Google Colab

Upload or open:

```text
Final_classification_of_pneumonia_using_cnn.ipynb
```

### 3. Mount Google Drive

```python
from google.colab import drive
drive.mount('/content/drive')
```

### 4. Upload Dataset

Store the dataset in Google Drive and update the dataset paths in the notebook accordingly.

### 5. Run the Notebook

Execute all cells sequentially to:

- Load and preprocess the dataset
- Train CNN, AlexNet, and VGG16 models
- Evaluate model performance
- Generate predictions on test images

---

## 📊 Results

The project successfully trained and evaluated multiple deep learning architectures for pneumonia detection.

### Key Outcomes

- Successfully classified Chest X-ray images as Normal or Pneumonia.
- Compared the performance of CNN, AlexNet, and VGG16 models.
- Demonstrated the effectiveness of transfer learning for medical image classification.
- Achieved reliable performance in automated pneumonia detection tasks.

---

## 📈 Future Enhancements

- Implement ResNet and EfficientNet architectures
- Hyperparameter optimization
- Explainable AI using Grad-CAM visualization
- Multi-class lung disease classification
- Deployment as a web application using Streamlit
- Integration with healthcare diagnostic systems

---

## 🌟 Applications

- Computer-Aided Diagnosis (CAD)
- Healthcare Decision Support Systems
- Medical Image Analysis
- Deep Learning Research in Healthcare
- Automated Disease Screening

---

## 👨‍💻 Author

**Dileep Reddy Gurijala**

---

## 📜 License

This project is intended for educational and research purposes.
