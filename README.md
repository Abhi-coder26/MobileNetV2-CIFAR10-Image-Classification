# MobileNetV2-CIFAR10-Image-Classification

A deep learning image classification project using MobileNetV2 on the CIFAR-10 dataset. Achieved 93.57% test accuracy through transfer learning and fine-tuning. Includes performance metrics, confusion matrix analysis, external image testing, model saving, and deployment readiness for TinyML and IoT applications.

## 📌 Project Overview

This project implements **MobileNetV2** for image classification on the **CIFAR-10 dataset** using TensorFlow and Keras. The model was fine-tuned using transfer learning techniques to achieve high classification performance while maintaining a lightweight architecture suitable for resource-constrained environments.

The project includes data preprocessing, model training, evaluation, confusion matrix analysis, external image testing, and model saving.

---

## 🎯 Objectives

* Implement MobileNetV2 for CIFAR-10 image classification
* Apply transfer learning and fine-tuning techniques
* Evaluate model performance using standard metrics
* Generate confusion matrix and classification report
* Perform external image testing
* Save trained models and visualizations

---

## 📂 Dataset

### CIFAR-10 Dataset

The CIFAR-10 dataset contains:

* 60,000 color images
* 10 object categories
* Image size: 32 × 32 × 3

### Classes

| Class Index | Class Name |
| ----------- | ---------- |
| 0           | Airplane   |
| 1           | Automobile |
| 2           | Bird       |
| 3           | Cat        |
| 4           | Deer       |
| 5           | Dog        |
| 6           | Frog       |
| 7           | Horse      |
| 8           | Ship       |
| 9           | Truck      |

---

## 🏗️ Model Architecture

### MobileNetV2

MobileNetV2 is a lightweight convolutional neural network architecture designed for efficient image classification.

### Key Features

* Depthwise Separable Convolutions
* Inverted Residual Blocks
* Linear Bottlenecks
* Transfer Learning Support
* Low Computational Cost
* Suitable for Mobile and Embedded Devices

---

## ⚙️ Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-Learn
* Kaggle Notebook

---

## 📊 Model Performance

| Metric              | Value  |
| ------------------- | ------ |
| Training Accuracy   | 96.56% |
| Validation Accuracy | 93.82% |
| Test Accuracy       | 93.57% |
| Precision           | 93.54% |
| Recall              | 93.57% |
| F1 Score            | 93.54% |
| Test Loss           | 0.20   |

---

## 📈 Model Information

| Metric               | Value        |
| -------------------- | ------------ |
| Model Name           | MobileNetV2  |
| Total Parameters     | 2,588,490    |
| Model Size           | ~29 MB       |
| Total Inference Time | 0.472944 sec |

---

## 🔍 Confusion Matrix Analysis

### Summary

* Test Samples: 10,000
* Correct Predictions: 9,357
* Incorrect Predictions: 643
* Confusion Matrix Accuracy: 93.57%

### Status

✅ Excellent Classification Performance

The confusion matrix demonstrates strong classification performance across the CIFAR-10 classes with minimal misclassification.

---

## 🌍 External Image Testing

A total of **10 real-world images** were tested.

### Results

| Actual Class | Predicted Class | Confidence |
| ------------ | --------------- | ---------- |
| Ship         | Ship            | 99.83%     |
| Airplane     | Airplane        | 99.34%     |
| Automobile   | Automobile      | 54.67%     |
| Bird         | Bird            | 99.92%     |
| Cat          | Cat             | 98.72%     |
| Deer         | Deer            | 31.71%     |
| Dog          | Dog             | 97.45%     |
| Frog         | Cat             | 92.11%     |
| Horse        | Horse           | 86.55%     |
| Truck        | Truck           | 95.11%     |

### External Testing Summary

* Total Images Tested: 10
* Correct Predictions: 9
* Incorrect Predictions: 1
* External Testing Accuracy: 90.00%

### Misclassification

* Actual Class: Frog
* Predicted Class: Cat
* Confidence Score: 92.11%

---

## 📁 Repository Structure

```text
MobileNetV2-CIFAR10-Image-Classification
│
├── README.md
├── mobilenetv2-cifar10-project-report.pdf
├── mobilenetv2-cifar10.ipynb
```

### File Description

| File Name                              | Description                                                                                                             |
| -------------------------------------- | ----------------------------------------------------------------------------------------------------------------------- |
| README.md                              | Project documentation and performance summary                                                                           |
| mobilenetv2-cifar10-project-report.pdf | Detailed project report including methodology, implementation, results, and conclusions                                 |
| mobilenetv2-cifar10.ipynb              | Complete notebook containing preprocessing, training, evaluation, confusion matrix analysis, and external image testing |

---

## 📷 Generated Outputs

* Accuracy Curve
* Loss Curve
* Classification Report
* Performance Metrics
* Confusion Matrix
* External Image Testing Results
* Project Summary

---

## 👨‍💻 Author

**Abhishek Chaurasiya**

B.Tech Information Technology

Research Internship Project

**Project Title:** MobileNetV2 CIFAR-10 Image Classification

---

## ⭐ Final Result

**The fine-tuned MobileNetV2 model achieved 93.57% test accuracy on the CIFAR-10 dataset and 90.00% accuracy on external image testing, demonstrating strong classification performance and reliable generalization on unseen images.**
