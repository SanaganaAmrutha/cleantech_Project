# CleanTech
# CleanTech: Transforming Waste Management with Transfer Learning

CleanTech is a deep learning-based web application designed to automate waste classification using transfer learning. It classifies images into three categories: **Biodegradable**, **Recyclable**, and **Trash**, supporting better waste segregation and sustainable waste management.

## 🧠 Project Overview

- 🔍 **Goal**: Classify waste images in real-time to assist in efficient urban waste handling.
- 🧰 **Model**: Pre-trained VGG16 model fine-tuned with custom classification layers.
- 🌐 **Web Interface**: Built using Flask with a simple HTML frontend.

## 📁 Project Structure

w_flask/
├── app.py # Flask backend script
├── vgg16.keras # Saved model (fine-tuned VGG16)
├── templates/
│ ├── index.html # File upload form
│ └── result.html # Display prediction
├── static/uploads/ # Uploaded images storage
├── train_model.ipynb # Jupyter Notebook for training the model


## ⚙️ Setup Instructions

### Prerequisites
- Python 3.x
- pip or conda for managing packages

### Install Dependencies
```bash
pip install tensorflow flask numpy matplotlib

Run the Application

cd w_flask
python3 app.py

Then open your browser at http://127.0.0.1:5000/
🧪 Model Summary

    Base model: VGG16 (imagenet weights, without top)

    Added Layers: Flatten → Dropout → Dense (softmax)

    Accuracy:

        Training: 92.3%

        Validation: 90.6%

        Fine-tuned: 91.2%

📸 Sample Predictions

    Plastic Bottle → Recyclable

    Banana Peel → Biodegradable

    Styrofoam Cup → Trash

📈 Future Enhancements

    Add more waste categories (metal, glass, e-waste)

    Integrate smart bin sensors

    Deploy on cloud/edge devices

    Add mobile support
