# 🐱🐶 Cats vs Dogs Image Classifier using SVM
This project implements an image classifier that distinguishes between cats and dogs using a Support Vector Machine (SVM) with a linear kernel. The model is trained on 128×128 grayscale images from the [Kaggle Dogs vs. Cats dataset](https://www.kaggle.com/competitions/dogs-vs-cats/data).

## 📌 Features
- Preprocesses and resizes images to 128×128
- Converts images to grayscale and flattens them
- Trains a Support Vector Classifier (SVC with linear kernel)
- Evaluates performance using classification report and confusion matrix
- Visualizes random test predictions

## 🗂️ Dataset
The dataset used is from Kaggle:
🔗 [Dogs vs. Cats - Kaggle Competition](https://www.kaggle.com/competitions/dogs-vs-cats/data)
Due to GitHub's 25MB file size limit, the full dataset is **not included** in this repository.

The dataset is sourced from the Kaggle Dogs vs. Cats competition. A subset was used for training and testing due to the dataset's large size. However, it is not included in this repository as it exceeds GitHub’s 25MB file size limit.

## 🧪 Requirements
- Python 3.x
- NumPy
- OpenCV
- scikit-learn
- Matplotlib
- Seaborn
- tqdm
