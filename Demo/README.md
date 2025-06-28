# CleanTech: Waste Image Classifier Demo

This repository presents a deep learning project called **CleanTech: Transforming Waste Management with Transfer Learning**. The goal of the project is to automate municipal waste classification using computer vision techniques.

## 📽️ Project Demo

Watch the video below to see how the application works:

🔗 **[Watch Demo Video](demo.mp4)**  
*(If hosted on GitHub or external site, replace this with YouTube or Drive link.)*

## 🧠 Overview

- **Goal**: Classify images of municipal waste into:
  - Biodegradable
  - Recyclable
  - Trash
- **Technology**:
  - Model: Pre-trained VGG16 + custom dense layers
  - Interface: Flask-based web application
  - Dataset: Collected from Kaggle

## 🧪 Key Features Demonstrated in Video

- Uploading an image through a web form
- Running prediction via a deep learning model
- Displaying results immediately in the UI
- Achieved accuracy: ~91% (validation)

## 🚀 How to Run

```bash
pip install tensorflow flask numpy
cd w_flask
python3 app.py

