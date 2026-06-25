# 🧠 Brain Tumor Detection using Deep Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-orange)
![Flask](https://img.shields.io/badge/Flask-Web%20App-black)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)

A deep learning-based Brain Tumor Detection system built using **TensorFlow/Keras**, **OpenCV**, and **Flask**. This project preprocesses MRI images, applies image augmentation techniques, and predicts whether a brain MRI scan contains a tumor.

---

## 📌 Features

✅ Brain MRI image classification
✅ Image preprocessing and contour extraction
✅ Data augmentation for improved model performance
✅ TensorFlow/Keras-based CNN model
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
├── static/                      # CSS and images
├── yes/                         # Tumor MRI images
├── no/                          # Non-tumor MRI images
├── augmented_data/              # Augmented dataset
├── requirements.txt
└── README.md
```

---

## 🚀 Installation & Setup

### Clone the repository

```bash
git clone <repository-url>
cd Brain-Tumor-Detection
```

### Install dependencies

```bash
pip install -r requirements.txt
```

Or install manually:

```bash
pip install tensorflow opencv-python numpy matplotlib scikit-learn imutils pillow flask
```

---

## ▶ Running on Google Colab

1. Open Google Colab

2. Upload:

   * `app.ipynb`
   * Dataset folder (`augmented_data/`)  OR Upload `Data Augmentation.ipynb` and Dataset folders (`yes/`,`no/`)
   * `templates/`
   * `static/`
   * `testing`
   * `cnn-parameters-improvement-23-0.91.model` (optional if you want to skip training)

3. Run notebook cells sequentially

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

The following augmentation techniques are used:

* Rotation
* Zoom
* Horizontal flip
* Width/height shift
* Shear transformation

These techniques increase dataset diversity and improve model generalization.

---

## 📜 License

This project is open-source and intended for educational purposes.

---

## 👨‍💻 Author

**ZOROXHUNTER**

If you found this project useful, consider giving the repository a ⭐
