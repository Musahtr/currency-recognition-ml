# AI-Powered Nigerian Currency Recognition and Intelligent Cash Processing System

An end-to-end deep learning project that automatically recognizes Nigerian Naira denominations from images using Computer Vision and Convolutional Neural Networks (CNNs). This project serves as the first phase of developing an intelligent cash-processing system capable of recognizing currency denominations and laying the foundation for future counterfeit detection, damaged-note identification, and integration with electronic note-counting machines.

---

# Project Overview

Cash-intensive organizations such as banks, retail businesses, and financial institutions process large volumes of currency daily. While existing note-counting machines efficiently count the number of notes, they often require users to manually separate denominations before counting. This process is time-consuming, prone to human error, and limits operational efficiency.

This project aims to develop a robust machine learning model that automatically recognizes Nigerian Naira denominations from images, improving the speed and accuracy of cash handling while providing a scalable foundation for future intelligent cash-processing solutions.

---

# Problem Definition

Manual identification and sorting of Nigerian currency denominations remain inefficient and susceptible to errors, particularly when processing mixed bundles of cash. Existing currency-counting machines primarily focus on counting notes and generally lack the capability to automatically classify denominations or support advanced features such as counterfeit detection and damaged-note identification.

The goal of this project is to develop a deep learning-based image classification system capable of accurately recognizing Nigerian Naira denominations from images. The resulting model will serve as the core component of an intelligent cash-processing solution that can be expanded to support counterfeit detection, damaged-note recognition, and multi-currency classification.

---

# Project Objectives

* Develop a deep learning model capable of recognizing Nigerian Naira denominations from images.
* Build a reliable and reproducible image preprocessing pipeline.
* Train and evaluate a baseline Convolutional Neural Network (CNN).
* Improve model performance through transfer learning and hyperparameter tuning.
* Create a scalable solution suitable for future deployment in intelligent cash-processing systems.
* Establish a foundation for counterfeit detection, damaged-note recognition, and multi-currency support.

---

# Business Success Metrics

The project will be considered successful if it:

* Accurately identifies Nigerian currency denominations under different imaging conditions.
* Reduces the need for manual sorting before cash counting.
* Minimizes human errors during cash processing.
* Produces predictions quickly enough for practical real-time applications.
* Provides a scalable framework for integrating counterfeit detection and damaged-note identification in future versions.

---

# Machine Learning Evaluation Metrics

Model performance will be evaluated using the following metrics:

| Metric               | Description                                                                                        |
| -------------------- | -------------------------------------------------------------------------------------------------- |
| **Accuracy**         | Overall percentage of correctly classified currency images.                                        |
| **Precision**        | Measures the proportion of correctly predicted denominations among all predictions for each class. |
| **Recall**           | Measures the model's ability to correctly identify all images belonging to each denomination.      |
| **F1-Score**         | Harmonic mean of Precision and Recall, providing a balanced performance measure.                   |
| **Confusion Matrix** | Visualizes classification performance and identifies commonly confused denominations.              |
| **Inference Time**   | Measures the average prediction time per image for real-time deployment assessment.                |

### Target Performance

| Metric         | Target                   |
| -------------- | ------------------------ |
| Accuracy       | ≥ 95%                    |
| Precision      | ≥ 94%                    |
| Recall         | ≥ 94%                    |
| F1-Score       | ≥ 94%                    |
| Inference Time | < 100 ms per image (CPU) |

---

# Dataset

The project currently uses a publicly available Nigerian Naira image dataset containing the following denominations:

* ₦5
* ₦10
* ₦20
* ₦50
* ₦100
* ₦200
* ₦500
* ₦1000

The dataset is organized into three subsets:

* Training Set
* Validation Set
* Test Set

To improve model robustness and real-world applicability, future versions of this project will incorporate a custom-built dataset captured under diverse environmental conditions, including varying lighting, backgrounds, viewing angles, note orientations, folded notes, worn notes, and partially occluded currency images.

---

# Project Structure

```text
currency-recognition-ml/
│
├── dataset/
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_baseline_model.ipynb
│
├── src/
├── models/
├── outputs/
├── README.md
├── pyproject.toml
├── uv.lock
└── .gitignore
```

---

# Technologies Used

* Python
* PyTorch
* TorchVision
* OpenCV
* NumPy
* Matplotlib
* Jupyter Notebook
* VS Code
* Git
* GitHub

---

# Project Workflow

1. Business Problem Definition
2. Data Collection
3. Exploratory Data Analysis (EDA)
4. Data Preprocessing
5. Baseline Model Development
6. Model Training
7. Model Evaluation
8. Hyperparameter Tuning
9. Transfer Learning
10. Model Deployment

---

# Current Progress

| Stage                       | Status         |
| --------------------------- | -------------- |
| Business Problem Definition | ✅ Completed    |
| Dataset Selection           | ✅ Completed    |
| Exploratory Data Analysis   | ✅ Completed    |
| Data Preprocessing          | 🔄 In Progress |
| Baseline CNN Development    | ⏳ Pending      |
| Model Evaluation            | ⏳ Pending      |
| Model Deployment            | ⏳ Pending      |

---

# Future Improvements

* Develop a larger custom Nigerian currency dataset captured under real-world conditions.
* Implement counterfeit currency detection.
* Detect damaged and worn banknotes.
* Extend support to additional African currencies.
* Integrate the model into intelligent electronic note-counting machines.
* Deploy the solution as a web application and REST API.
* Optimize the model for mobile and edge-device deployment.

---

# Author

**Musa Haruna Taura**

Civil Engineer | Machine Learning Engineer | AI Research Enthusiast

GitHub: https://github.com/Musahtr

LinkedIn: *(Add your LinkedIn profile)*

---

# License

This project is intended for educational, research, and portfolio purposes.
