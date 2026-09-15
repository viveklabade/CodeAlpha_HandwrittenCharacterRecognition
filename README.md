# Handwritten Character Recognition using CNN

## 📌 Project Overview

This project implements a Handwritten Character Recognition system using a Convolutional Neural Network (CNN).

The model is trained using the MNIST handwritten digit dataset and can classify handwritten digits from **0 to 9**.

This project was completed as **Task 3 of the CodeAlpha Machine Learning Internship**.

## 🎯 Objective

The objective of this project is to identify handwritten characters/digits from images using image processing and deep learning techniques.

## 📊 Dataset

The **MNIST dataset** is used for this project.

* Training images: 60,000
* Testing images: 10,000
* Image size: 28 × 28 pixels
* Classes: 10 digits (0–9)

## 🛠️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Scikit-learn
* Google Colab

## 🧠 Machine Learning Model

A Convolutional Neural Network (CNN) is used for image classification.

### Model Architecture

1. Convolutional Layer — 32 filters
2. Max Pooling Layer
3. Convolutional Layer — 64 filters
4. Max Pooling Layer
5. Flatten Layer
6. Dense Layer — 128 neurons
7. Output Layer — 10 classes

## 🔄 Project Workflow

```text
MNIST Dataset
      ↓
Data Loading
      ↓
Image Visualization
      ↓
Normalization
      ↓
Reshaping
      ↓
CNN Model
      ↓
Model Training
      ↓
Model Evaluation
      ↓
Prediction
      ↓
Confusion Matrix & Classification Report
```

## 📈 Results

The trained CNN model was evaluated using the MNIST test dataset.

**Test Accuracy:** Add your actual test accuracy here.

**Test Loss:** Add your actual test loss here.

The model was also tested on individual handwritten digit images and incorrect predictions were analyzed.

## 📁 Files

* `Handwritten_Character_Recognition.ipynb` — Complete Google Colab notebook
* `handwritten_character_recognition.keras` — Trained CNN model

## ▶️ How to Run

1. Open the Jupyter Notebook in Google Colab.
2. Run the cells sequentially.
3. The MNIST dataset will be loaded automatically.
4. Train the CNN model.
5. Evaluate the model.
6. Generate predictions and performance reports.

## 🚀 Future Improvements

* Use the EMNIST dataset for alphabet recognition.
* Recognize complete handwritten words.
* Recognize handwritten sentences.
* Build a web interface for real-time handwritten character recognition.

## 👨‍💻 Author

**Vivek Labade**

Machine Learning Intern — CodeAlpha
