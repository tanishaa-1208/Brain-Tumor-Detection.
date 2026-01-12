# 🧠 Brain Tumor Detection using CNN & Transfer Learning

This project implements and compares multiple deep learning models for brain tumor detection from MRI images.
The objective is to classify MRI scans into Tumor and No Tumor categories using both a custom CNN architecture and state-of-the-art transfer learning models.

📄 This work is an exact replication and experimental validation of the research paper: “Brain Tumor Detection Using Deep Learning and CNN Architecture”

# 🚀 Models Implemented

The following models were designed, trained, and evaluated:
- Proposed Custom CNN
- EfficientNetB0 (Transfer Learning)
- ResNet50 (Transfer Learning)

Each model is evaluated using standard classification metrics to ensure a fair and consistent comparison.

# 📊 Evaluation Metrics & Analysis

All models were compared using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Grad-CAM visualisations for interpretability and explainability

# 📁 Project Contents

- Brain_MRI_SCAN.ipynb
Main Jupyter Notebook containing:
  Data loading and preprocessing
  Model architecture definitions
  Training and evaluation pipelines
  Metric computation and visualisation

- Research Paper (PDF)
  Reference paper used for exact replication
  Methodology comparison and validation

- Outputs & Visualisations
  Confusion matrix heatmaps
  Grad-CAM activation maps
  Model comparison results

# 📊 Results Summary

- EfficientNetB0 and ResNet50 achieved the highest classification performance on the test dataset.

- The custom CNN demonstrated competitive results while remaining lightweight and computationally efficient.

- Grad-CAM visualisations helped verify that models focused on medically relevant regions of the MRI scans.

# 🧩 Techniques Used

- Convolutional Neural Networks (CNN)
- Transfer Learning
- Image Preprocessing & Normalisation
- Data Augmentation
- Model Explainability using Grad-CAM

# 🛠 Requirements

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, Seaborn

# ▶️ How to Access & Run the Project
a.) Option 1: Run Locally

1. Clone the repository:
git clone <your-repository-link>

2. Open the notebook:
Brain_MRI_SCAN.ipynb

3.Install required libraries if needed and run all cells sequentially.


b.) Option 2: Run on Google Colab (Recommended)

1. Upload Brain_MRI_SCAN.ipynb to Google Colab

 2.Upload the dataset when prompted (or mount Google Drive if configured)

3. Run all cells to reproduce results

📌 [A Colab link for direct execution.](https://colab.research.google.com/github/tanishaa-1208/Brain-Tumor-Detection./blob/main/Brain_MRI_SCAN.ipynb) 


# 💡 Author

This project was developed as part of an AI/ML academic coursework.
Contributors:
- Tanisha Gupta (E23CSEU1482)
- Ishwita Bathla (E23CSEU1495)
