# 🌱 Plant Disease Detection using Deep Learning (PyTorch + Grad-CAM)

## 📌 Project Overview

This project builds a deep learning model to detect plant diseases from leaf images. It focuses on tomato leaf classification using the PlantVillage dataset and applies Grad-CAM to visualize which parts of the image influenced the model’s decision.

---

## 🚀 Key Features

* Image classification using **EfficientNet-B0**
* Transfer Learning with pretrained weights (ImageNet)
* Dataset preprocessing and augmentation
* Model training and evaluation using PyTorch
* Grad-CAM visualization for model interpretability

---

## 🧠 Tech Stack

* Python
* PyTorch
* Torchvision
* Google Colab
* Matplotlib
* Grad-CAM

---

## 📂 Dataset

* **PlantVillage Dataset (Tomato Leaf Diseases)**
* Dataset is loaded from Google Drive (`archive.zip`)

---

## ⚙️ How to Run the Project

1. Open the notebook in Google Colab
2. Upload dataset zip file to Google Drive
3. Update dataset path if needed:

   ```python
   zip_path = '/content/drive/MyDrive/archive.zip'
   ```
4. Run all cells step-by-step

---

## 🏗️ Project Workflow

1. Import Libraries
2. Load and Extract Dataset
3. Data Preprocessing & Augmentation
4. Model Building (EfficientNet-B0)
5. Training the Model
6. Evaluation
7. Grad-CAM Visualization

---

## 📊 Model Details

* Model: EfficientNet-B0
* Loss Function: CrossEntropyLoss
* Optimizer: Adam
* Input Image Size: 224x224

---

## 🔍 Results

* Successfully classifies tomato leaf diseases
* Grad-CAM highlights infected regions in leaf images
* Model learns meaningful visual patterns

---

## 📸 Sample Output

(Add screenshots of predictions and Grad-CAM heatmaps here)

---

## 💡 Future Improvements

* Deploy as a web app (Streamlit / Flask)
* Add more plant species and diseases
* Improve accuracy with fine-tuning
* Use larger and more diverse datasets

---

## 👨‍💻 Author

Kanishk Yadav
