# 🥔 Potato Disease Detection Using Hybrid Quantum Machine Learning

A Hybrid Quantum-Classical Deep Learning model for Potato Leaf Disease Detection using image classification techniques. This project uses Quantum Machine Learning (QML), Principal Component Analysis (PCA), and Deep Learning to identify potato plant diseases from leaf images.

---

## 🚀 Project Overview

Potato crops are highly vulnerable to diseases such as Early Blight and Late Blight, which can significantly reduce agricultural productivity. Early detection of these diseases helps farmers take preventive measures and minimize crop losses.

This project combines classical deep learning and quantum computing concepts to classify potato leaf images into different disease categories.

---

## 🎯 Objectives

- Detect potato leaf diseases from images.
- Explore Hybrid Quantum Machine Learning for agricultural applications.
- Compare classical and quantum-enhanced learning approaches.
- Build an efficient image classification pipeline.

---

## 📌 Features

✅ Potato Leaf Disease Classification

✅ Hybrid Quantum-Classical Neural Network

✅ PCA-Based Feature Reduction

✅ Quantum Circuit Integration using Pennylane

✅ Data Preprocessing & Augmentation

✅ Class Balancing Techniques

✅ GPU Support

✅ Model Evaluation and Visualization

---

## 🦠 Disease Categories

The model classifies potato leaf images into:

- Healthy
- Early Blight
- Late Blight

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Pennylane
- NumPy
- Pandas
- Scikit-Learn
- OpenCV
- Matplotlib
- PIL (Python Imaging Library)

---

## 📂 Dataset

The project uses a Potato Disease Detection Dataset containing images of healthy and diseased potato leaves.

Dataset Structure:

```text
dataset/
│
├── Potato___Healthy/
├── Potato___Early_Blight/
└── Potato___Late_Blight/
```

---

## ⚙️ Project Workflow

### 1. Data Collection

Potato leaf images are loaded from the dataset.

### 2. Data Preprocessing

- Image resizing
- Normalization
- Data augmentation
- Label encoding

### 3. Dataset Balancing

Class balancing techniques are applied to improve model performance.

### 4. Feature Extraction

Images are converted into numerical feature vectors.

### 5. PCA Dimensionality Reduction

Principal Component Analysis (PCA) reduces feature dimensions before quantum processing.

### 6. Quantum Feature Learning

A parameterized quantum circuit is implemented using Pennylane.

### 7. Hybrid Model Training

The quantum layer is integrated with classical neural network layers.

### 8. Disease Prediction

The trained model predicts whether a potato leaf is healthy or affected by disease.

---

## 🧠 Hybrid Model Architecture

```text
Input Image
      ↓
Image Preprocessing
      ↓
Feature Extraction
      ↓
PCA
      ↓
Classical Neural Network
      ↓
Quantum Layer
      ↓
Fully Connected Layer
      ↓
Disease Classification
```

---

## 📊 Evaluation Metrics

The model is evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/potato-disease-detection-qml.git
cd potato-disease-detection-qml
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 🔧 Required Libraries

```bash
pip install torch torchvision
pip install pennylane
pip install numpy pandas
pip install matplotlib
pip install scikit-learn
pip install opencv-python
pip install pillow
```

---

## ▶️ Running the Project

Open the notebook and execute all cells.

---

## 📈 Results

The Hybrid Quantum-Classical model successfully classifies potato leaf diseases by combining classical deep learning with quantum feature processing.

The performance depends on:

- Number of qubits
- PCA components
- Training epochs
- Dataset size
- Quantum circuit depth

---

## 🌱 Applications

- Smart Agriculture
- Precision Farming
- Automated Crop Monitoring
- Early Disease Detection
- Agricultural Decision Support Systems

---

## 🔮 Future Improvements

- Real-time disease detection using mobile cameras
- Streamlit web deployment
- Advanced quantum circuits
- Explainable AI integration
- Multi-crop disease classification

---
## 📚 Learn More About Quantum Machine Learning

Interested in understanding the concepts behind Quantum Machine Learning (QML) used in this project?

Read my article:

🔗 [[Quantum Computing: The Future Beyond Classical Machines](YOUR_ARTICLE_LINK_HERE)](https://medium.com/@gunjansoni20058/quantum-machine-learning-isnt-about-faster-computers-it-s-about-rethinking-computation-da5534461349)


  ---

## 👩‍💻 Author

**Gunjan Soni**

Computer Science Student | AI/ML Enthusiast | Quantum Machine Learning Researcher

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.

---

## 🙏 Acknowledgements

- PyTorch
- Pennylane
- Scikit-Learn
- Open Source Community
- Plant Disease Dataset Contributors
