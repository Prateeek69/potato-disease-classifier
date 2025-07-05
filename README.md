# 🥔 Potato Disease Classifier - Frontend

This is the **frontend** for a Deep Learning project that classifies **potato leaf diseases** into:
- Early Blight 🍂  
- Late Blight 🍃  
- Healthy 🌿

The frontend is built using **React**, allowing users to **drag and drop an image of a potato leaf** and get instant predictions via the connected backend API.

---

## 🔍 Project Overview

This frontend connects to a backend model trained on the [PlantVillage Dataset (Potato Leaves)](https://www.kaggle.com/datasets/arjuntejaswi/plant-village). The model achieves an accuracy of **92.46%** in classifying the leaf condition into:
- **Early Blight**
- **Late Blight**
- **Healthy**

The backend processes the image and returns the predicted class, which is then displayed in the UI.

---

## 🚀 Features

- 🖼️ Drag & Drop potato leaf images
- 🔄 Real-time prediction via backend API
- 📱 Responsive and lightweight React interface
- 📊 Model trained using deep learning (TensorFlow/Keras in backend)

---

## 🔧 Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/Prateeek69/potato-disease-classifier.git
cd potato-disease-classifier
```

### 2. Install dependencies
```bash
npm install
```

### 3. Run the development server
```bash
npm start
```
🔗 Backend Integration
The frontend sends image data to this backend API for prediction:

```arduino 
https://potato-disease-classifier-three.vercel.app/predict
``` 
Update the URL in your frontend code (App.js or wherever applicable) if your backend is deployed to a different server.

## 📸 Example Usage

1. 🖼️ Drag & drop a potato leaf image.
2. 🔄 The app sends the image to the backend.
3. 🧠 The backend returns the predicted disease class.
4. 📋 The result is shown below the upload area.

---

## 🧠 Model Training Details

- Model trained using a **Convolutional Neural Network (CNN)** on potato leaf images from the [PlantVillage dataset](https://www.kaggle.com/datasets/arjuntejaswi/plant-village).
- Achieved **92.46% accuracy** on the validation set.
- Training code and notebook are available in the **private backend repository**.

---

## 📁 Dataset

The dataset used is available on Kaggle:  
👉 [PlantVillage (Potato Leaves Subset)](https://www.kaggle.com/datasets/arjuntejaswi/plant-village)

---

## 👨‍💻 Author

**Prateek**  
🔗 [GitHub](https://github.com/Prateeek69)
