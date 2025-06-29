# 🌌 GalaxyML: Galaxy Morphology Classification with Deep Learning

**GalaxyML** is a deep learning project aimed at classifying galaxies based on their morphological features using convolutional neural networks (CNNs). Leveraging astronomical image datasets, this project automates visual classification to support astrophysical research and large-scale sky surveys.

## 🧠 Problem Statement

Manual galaxy classification is time-consuming and prone to inconsistency, especially given the scale of modern sky surveys. The goal of GalaxyML is to automate galaxy morphology classification using labeled image data from the Galaxy Zoo project.

## 🚀 Solution Overview

- Built a **CNN-based image classification pipeline** for multi-class galaxy shape prediction.
- Preprocessed images (resizing, normalization, augmentation) to improve generalization.
- Trained and validated models using metrics such as **accuracy**, **F1-score**, and **confusion matrix**.
- Enabled robust classification across elliptical, spiral, and irregular galaxy types.

## 🛠️ Tech Stack

- **Python**
- **PyTorch**, torchvision
- **NumPy**, pandas
- **Matplotlib**, seaborn (visualization)

## 🗃️ Dataset

- **Source**: Galaxy Zoo dataset
- Contains labeled images of galaxies across multiple morphological classes
- Includes metadata for potential future feature integration

## 📊 Results

- Achieved high classification accuracy (~XX% — update if known)
- CNN model outperformed baseline classifiers
- Visualized feature maps and confusion matrix to analyze model behavior

## ▶️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sakshamojha56/GalaxyML.git
   cd GalaxyML
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   
## 📄 License
   This project is licensed under the MIT License.
