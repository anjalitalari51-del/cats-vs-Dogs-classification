# Cats vs Dogs Image Classification Using Convolutional Neural Network (CNN)

## 📌 Problem Statement

The objective of this project is to build a Deep Learning model that can classify images as either Cats or Dogs. The model is trained using image data and learns to identify patterns and features that distinguish cats from dogs.

---

## 📂 Dataset

The project uses a Cats and Dogs image dataset containing images of both categories.

### Categories:
- Cat
- Dog

The dataset is organized into separate folders for training the model.

---

## 🔄 Methodology

1. Data Collection and Loading
2. Image Preprocessing
3. Image Resizing (150 × 150)
4. Data Augmentation
5. CNN Model Building
6. Model Training using TensorFlow/Keras
7. Model Evaluation
8. Saving Trained Model
9. Image Prediction and Classification

---

## 🛠️ Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib

---

## 📋 Requirements

Install the required libraries:

```bash
pip install tensorflow opencv-python numpy matplotlib
```

---

## 🤖 Deep Learning Model

### Convolutional Neural Network (CNN)

The CNN model automatically extracts image features and classifies images into:

- Cat
- Dog

The trained model is saved as:

```text
pet_classifier.keras
```

---

## 📊 Results

The model was successfully trained on the dataset and used to predict whether an input image is a Cat or Dog.

### Output:
- Predicted Class
- Confidence Score (if applicable)

---

## 📁 Project Structure

```text
Cats-vs-Dogs-Classification/
│
├── source code/
│   ├── train.py
│   ├── predict.py
│   ├── show_prediction.py
│   ├── check_images.py
│   └── pet_classifier.keras
│
├── screenshots/
│
└── README.md
```

---

## 🎯 Output

The application accepts an input image and predicts whether the image belongs to:

- 🐱 Cat
- 🐶 Dog

The prediction result is displayed on the screen.

---

## 📸 Screenshots

Project screenshots are available in the `screenshots` folder.
