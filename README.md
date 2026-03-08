# NEURA_AI
# Neura AI 🧠

### AI-Based Brain Tumor Detection Using MRI Scans

Neura AI is a deep learning–powered medical imaging system designed to detect brain tumors from MRI scans. The system uses Convolutional Neural Networks (CNNs) to analyze MRI images and classify them into different tumor categories.

The goal of this project is to assist radiologists and healthcare professionals by providing fast, accurate, and automated tumor detection from brain MRI images.

---

## 📌 Features

* Automated **brain tumor detection** from MRI scans
* Classification into tumor categories:

  * Glioma
  * Meningioma
  * Pituitary Tumor
  * No Tumor
* Deep learning–based **CNN model**
* Web interface for **MRI image upload**
* Visualization of prediction results
* High-accuracy classification using medical imaging datasets

---

## 🧠 Problem Statement

Brain tumors are serious medical conditions that require early detection and accurate diagnosis. Manual analysis of MRI scans can be time-consuming and may vary depending on the radiologist's experience.

Neura AI provides an automated system that can quickly analyze MRI images and identify the presence and type of brain tumor, helping medical professionals make faster decisions.

---

## ⚙️ System Architecture

MRI Image → Preprocessing → CNN Model → Prediction → Result Visualization

### Pipeline

1. MRI image upload
2. Image preprocessing (resizing, normalization, noise reduction)
3. CNN model processes the image
4. Model predicts tumor class
5. Results displayed to the user

---

## 🧪 Dataset

The model can be trained using publicly available brain MRI datasets such as:

* Brain MRI Images Dataset (Kaggle)
* BraTS (Brain Tumor Segmentation Dataset)

Classes used in training:

* Glioma Tumor
* Meningioma Tumor
* Pituitary Tumor
* No Tumor

---

## 🛠 Tech Stack

### Machine Learning

* Python
* PyTorch
* NumPy
* OpenCV
* Matplotlib

### Backend

* Django / Flask

### Frontend

* React.js

### Other Tools

* Jupyter Notebook
* Git

---

## 📂 Project Structure

```
Neura-AI/
│
├── dataset/
│   ├── glioma/
│   ├── meningioma/
│   ├── pituitary/
│   └── no_tumor/
│
├── model/
│   └── cnn_model.py
│
├── backend/
│   └── api.py
│
├── frontend/
│   └── react-app/
│
├── notebooks/
│   └── training.ipynb
│
└── README.md
```

---

## 🚀 Installation

Clone the repository:

```
git clone https://github.com/yourusername/neura-ai.git
```

Navigate to the project directory:

```
cd neura-ai
```

Install dependencies:

```
pip install -r requirements.txt
```

Run the backend server:

```
python app.py
```

Start the frontend:

```
npm start
```

---

## 📊 Model Performance

Example metrics after training:

* Accuracy: ~94–97%
* Precision: High
* Recall: High

Actual performance may vary depending on dataset size and preprocessing techniques.

---

## 📷 Example Prediction

Input: Brain MRI Scan

Output:

```
Prediction: Glioma Tumor
Confidence: 96.4%
```

---

## ⚠️ Disclaimer

Neura AI is a research and educational project. It is not intended to replace professional medical diagnosis. The system should only be used as a decision-support tool for healthcare professionals.

---

## 👨‍💻 Author

Farhan Jafar
B.Tech CSE – Delhi Technological University

Skills: Deep Learning | Machine Learning | React | Node.js | PyTorch
