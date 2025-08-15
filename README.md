# Plant_disease_Classification
🌱 Plant Disease Classification using Vision Transformers &amp; EfficientNet  This project implements a **deep learning model** to classify plant leaf images into different disease categories.   It combines the power of **Vision Transformers (ViT)** and **EfficientNet** to achieve high accuracy while handling **class imbalance** effectively.

---

## 📌 Features
- **Vision Transformer (ViT)** and **EfficientNetB0** architectures
- **Class imbalance handling** for more robust predictions
- **Kaggle dataset integration** via API
- **Data preprocessing & augmentation**
- **Evaluation metrics**: Accuracy, Confusion Matrix, and Classification Report
- **Interactive visualizations** of results

---

## 🧠 Project Workflow
1. **Data Download** — Automatically fetch dataset from Kaggle.
2. **Data Preprocessing** — Resize, normalize, and prepare for model input.
3. **Model Training** — Train both EfficientNetB0 and Vision Transformer.
4. **Evaluation** — Compare models using accuracy, confusion matrix, and classification report.
5. **Visualization** — Plot training curves and example predictions.

---

## 🗂 Dataset
- **Source:** [Kaggle Plant Disease Dataset]  
- Contains thousands of plant leaf images, labeled by disease type.
- Images resized to match input size of ViT & EfficientNet.

> **Note:** Used only portion of the data to avoid system RAM crash in Google Colab leads to low performance


## 📊 Results
Confusion Matrix Example:  
<img width="657" height="610" alt="VIT Confusion Matrix" src="https://github.com/user-attachments/assets/5ebc07b5-d08d-4403-863f-04d33cdfa354" />
Training Accuracy & Loss:  
<img width="608" height="200" alt="VIT Performance Curve" src="https://github.com/user-attachments/assets/12c21374-561b-4028-a640-f23a1fb66e7e" />

