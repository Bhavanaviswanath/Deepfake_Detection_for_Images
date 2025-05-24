# Deepfake_Detection_for_Images_Using_CNN


A Convolutional Neural Network (CNN)-based system that detects and classifies images as **real** or **deepfake** by learning visual inconsistencies and artifacts. This project aims to assist in identifying manipulated media and maintaining digital authenticity.

---

## 📌 Project Overview

- 🧠 **Goal:** Detect deepfake images using a trained CNN model.
- 📷 **Input:** Image dataset containing real and fake images.
- ✅ **Output:** Class label (`Real` or `Fake`) for each image.
- 🧪 **Technology Used:** Python, TensorFlow/Keras, OpenCV, NumPy, Matplotlib.

---

## 🧰 Features

- 📦 Image preprocessing with OpenCV
- 🧠 CNN-based image classification
- 📊 Accuracy/Loss evaluation during training
- 📁 Saved model for later use
- 🖼️ Option for single-image prediction using CLI or script

---

## 🗃️ Dataset

You can use publicly available datasets such as:

- [FaceForensics++](https://github.com/ondyari/FaceForensics)
- [DeepFake Detection Challenge (DFDC)](https://www.kaggle.com/c/deepfake-detection-challenge/data)


## 🚀 Usage
🔧 Train the Model 
python train.py

🔍 Predict on a Single Image
python predict.py --image sample.jpg

## 🧠 Model Output
Accuracy/loss curves

Model saved as model.h5

Command-line output: "Predicted: Real / Fake"

![image](https://github.com/GudepuRakshitha/Deepfake-Detection-using-CNN/blob/39dc0abeafab1c5c8a116e7aab4c4005449a24a5/cnn1.png)

![image](https://github.com/GudepuRakshitha/Deepfake-Detection-using-CNN/blob/39dc0abeafab1c5c8a116e7aab4c4005449a24a5/cnn2.png)

![image](https://github.com/GudepuRakshitha/Deepfake-Detection-using-CNN/blob/39dc0abeafab1c5c8a116e7aab4c4005449a24a5/cnn3.png)

![image](https://github.com/GudepuRakshitha/Deepfake-Detection-using-CNN/blob/39dc0abeafab1c5c8a116e7aab4c4005449a24a5/cnn4.png)

![image](https://github.com/GudepuRakshitha/Deepfake-Detection-using-CNN/blob/39dc0abeafab1c5c8a116e7aab4c4005449a24a5/cnn5.png)


## 🙋‍♀️ Author
Natuva Bhavana

📧 Email: natuvabhavana@gmail.com
