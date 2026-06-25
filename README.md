# 🧠 Brain Tumor Detection using Deep Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-orange)
![Flask](https://img.shields.io/badge/Flask-Web%20App-black)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)

A deep learning-based Brain Tumor Detection system built using **TensorFlow/Keras**, **OpenCV**, and **Flask**. The project preprocesses MRI images, applies image augmentation techniques, and predicts whether a brain scan contains a tumor.

---

## 📌 Features

✅ Brain MRI image classification
✅ Image preprocessing and contour extraction
✅ Data augmentation for improving model performance
✅ TensorFlow/Keras-based neural network model
✅ Flask web interface for prediction
✅ Upload and analyze MRI scans

---

## 🛠 Tech Stack

* Python
* TensorFlow / Keras
* Flask
* OpenCV
* NumPy
* Scikit-learn
* Matplotlib

---

## 📂 Project Structure

```text
.
├── app.ipynb                    # Main notebook
├── Data Augmentation.ipynb      # Data augmentation notebook
├── model.h5                     # Trained model
├── templates/                   # HTML templates
├── static/                      # CSS/images
├── yes/                         # Tumor images
├── no/                          # Non-tumor images
├── augmented_data/              # Generated dataset
├── requirements.txt
└── README.md
```

---

## ▶ Running on Google Colab
Open Google Colab
Upload app.ipynb
Upload dataset folders (yes, no)
Upload augmentated data
Upload static, templates, testing
Upload the model to skip training
Run notebook cells sequentially

Install required packages:

!pip install -r requirements.txt

Or install manually:

!pip install tensorflow opencv-python numpy matplotlib scikit-learn imutils pillow

Open your browser:

```text
http://localhost:5000
```

Upload an MRI image and receive prediction results.

---

## 🔄 Workflow

```text
MRI Image
    ↓
Image Preprocessing
    ↓
Contour Detection
    ↓
Data Augmentation
    ↓
CNN Training
    ↓
Tumor Prediction
```

---

## 📊 Data Augmentation

Data augmentation techniques used:

* Rotation
* Zoom
* Horizontal flip
* Width/height shift
* Shear transformation

These techniques increase dataset diversity and improve model performance.

---

## 📜 License

This project is open-source and available for educational purposes.

---

## 👨‍💻 Author

**ZOROXHUNTER**

If you found this useful, give the repository a ⭐
