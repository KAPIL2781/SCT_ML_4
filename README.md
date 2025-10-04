# SCT_ML_4
Machine Learning Task 4 – Hand Gesture Recognition Model
# Hand Gesture Recognition Model

## 🤲 Overview
This project implements a **Convolutional Neural Network (CNN)** to classify 10 distinct hand gestures using a custom subset of the LeapGestRecog dataset. The model enables intuitive human-computer interaction by recognizing gestures such as palm, fist, thumb, and more from near-infrared images. Developed and trained on Google Colab, this repository showcases the end-to-end machine learning pipeline, including data preprocessing, model training, and visualizations.

## 📌 Problem Statement
Develop a hand gesture recognition model to accurately identify and classify different hand gestures from image data, facilitating gesture-based control systems.

## 📊 Dataset
- **Source**: [LeapGestRecog Dataset](https://www.kaggle.com/datasets/gti-upm/leapgestrecog)
- **Subset**: Manually created `archive/00` folder containing 10 gesture subfolders (e.g., `01_palm`, `02_l`, etc.), each with 200 near-infrared images (total 2000 images).
- **Features**: Grayscale pixel values resized to 64x64 pixels.

## ⚙️ Steps Followed
1. **Data Loading**: Collected images from the `archive/00` subfolders.
2. **Preprocessing**: Resized images to 64x64, normalized pixel values, and one-hot encoded labels.
3. **Data Splitting**: Split data into 80% training and 20% testing sets.
4. **Model Training**: Trained a CNN with two convolutional layers, max pooling, and dense layers using TensorFlow/Keras.
5. **Evaluation**: Calculated accuracy, confusion matrix, precision-recall curve, and ROC curve.
6. **Visualization**: Generated plots for training progress, confusion matrix, precision-recall, ROC, and a 2x3 image grid of predictions.

## 📈 Results
- **Test Accuracy**: [Insert accuracy from Cell 6, e.g., XX.X%] .
- **Confusion Matrix**: Visualizes true vs. predicted labels across 10 classes.
- **Precision-Recall Curve**: Shows macro-average performance with an average precision (AP) of [Insert AP from Cell 8, e.g., XX.X%].
- **ROC Curve**: Displays macro-average ROC with an AUC of [Insert AUC from Cell 9, e.g., XX.X%].
- **Image Grid**: Displays 6 test images with true and predicted gesture labels.


## 📦 Tech Stack
- **Languages/Frameworks**: Python, TensorFlow/Keras
- **Libraries**: NumPy, Matplotlib, Seaborn, Scikit-learn, PIL, TQDM
- **Platform**: Google Colab

## ✨ Author
**Kapil**  
📍 BE (CSE - AI ), Chitkara University ]  
