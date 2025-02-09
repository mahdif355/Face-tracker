# 🎯 AI-Powered Face Tracker 🚀

## 📌 Overview
This project is an **AI-powered face tracker** that **detects and follows only your face** using:
- ✅ **Deep Learning** (ResNet SSD for face detection)
- ✅ **Dlib Tracking** (for real-time face tracking)
- ✅ **Face Recognition** (to track only your face)
- ✅ **OpenCV** (for image processing)

It **learns your face** the first time and **ignores all other faces**.

---

## 📌 Demo (How It Works)
1️⃣ The **first time** the program runs, it **detects your face and saves it**.  
2️⃣ The tracker will **only follow your face**, even if others are present.  
3️⃣ Your **name and confidence score** will be displayed above your face.  
4️⃣ Press **'Q'** to exit.

---

## 📌 Installation
### **1️⃣ Install Dependencies**
Make sure you have **Python 3.9 or later** installed.  
Run the following command to install required libraries:
```bash
pip install opencv-python dlib face_recognition numpy
