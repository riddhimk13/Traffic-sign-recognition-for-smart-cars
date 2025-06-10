# Traffic Sign Recognition using CNN and Dual Datasets

This project focuses on building a **Convolutional Neural Network (CNN)** model to perform **traffic sign recognition**, leveraging data from both **German** and **Indian** traffic sign datasets. The goal is to improve the model's robustness across different traffic systems and sign variations.

## Key Features

- 🔁 **Dual-Dataset Integration**: Combines German Traffic Sign Recognition Benchmark (GTSRB) and Indian Traffic Sign Dataset for enhanced generalization.
- 🧠 **CNN Model**: Built from scratch using Keras/TensorFlow to classify traffic signs into multiple categories.
- 📊 **Evaluation**: Accuracy, confusion matrix, and visual predictions used to validate the model performance.
- 🧼 **Data Preprocessing**: Resizing, normalization, label encoding, and train-test split included.

## Datasets

- **GTSRB**: German Traffic Sign Recognition Benchmark – widely used, publicly available.
- **Indian Traffic Sign Dataset**: Contains traffic signs commonly found on Indian roads (custom collected or sourced).

## Technologies Used

- `Python`, `NumPy`, `Pandas`, `Matplotlib`, `Seaborn` for data handling and visualization  
- `OpenCV` for image processing  
- `TensorFlow / Keras` for CNN model building and training

## Results

- Achieved high accuracy 92% on validation/test set
- Successfully generalized across signs from different regions
- Clear visualization of predictions and misclassifications

