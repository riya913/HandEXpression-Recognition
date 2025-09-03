# ✋ Hand Gesture Recognition

## 📌 Overview
This project focuses on recognizing **hand gestures** using **OpenCV, Keras, and Convolutional Neural Networks (CNNs)**.  
The system captures live video feed, segments the hand region, and classifies gestures in **real-time**.

---

## 📂 Dataset
- **Link:** [Gesture Dataset](https://drive.google.com/drive/folders/17zMVpSzfA2U9wSv7y31JhcLUd2ZMHN1w?usp=drive_link)  
- **Description:** The dataset includes images of **6 different hand gestures**.  
- **Gesture Types:**
  - BLANK  
  - OK  
  - THUMBSUP  
  - THUMBSDOWN  
  - PUNCH  
  - HIGH-FIVE  

---

## 🎯 Project Objective
Build a **Real-Time Hand Gesture Recognition System**:
- Capture live video feed using **OpenCV**  
- Segment the **hand region** and preprocess images  
- Train and use a **CNN model** for gesture classification  

---

## 📁 Project Structure
- ├── cam_run.py # Main script for real-time gesture recognition
- ├── train_gestures.ipynb # Notebook for dataset loading & CNN model training
- ├── my_dataset/ # Folder containing gesture images
- └── README.md # Project documentation


---

## ⚙️ Requirements
- Python 3.6.7  
- OpenCV → `pip install opencv-python`  
- Matplotlib  
- Keras  
- scikit-learn  

Install all requirements with:
```bash
pip install opencv-python matplotlib keras scikit-learn
