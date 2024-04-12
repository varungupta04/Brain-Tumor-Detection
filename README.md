# Brain Tumor Detection with SVM and CNN

This repository contains implementations of brain tumor detection using Support Vector Machine (SVM) and Convolutional Neural Network (CNN) models.

## Overview

Brain tumor detection is a critical task in medical imaging analysis, aiding in early diagnosis and treatment planning. This project explores two approaches for brain tumor detection:

1. **SVM Approach**: Utilizes traditional machine learning techniques, specifically Support Vector Machine (SVM), to classify brain images as tumor or non-tumor based on extracted features.
   
2. **CNN Approach**: Employs a Convolutional Neural Network (CNN) architecture to automatically learn and extract features from brain images, followed by classification.

## Requirements

- Python (>=3.6)
- TensorFlow
- Scikit-learn
- Matplotlib
- Numpy

## Dataset

The dataset used for training and evaluation consists of MRI (Magnetic Resonance Imaging) scans of the brain, with annotated labels indicating the presence or absence of tumors. 

## Usage

1. Clone the repository:

```
git clone https://github.com/your-username/brain-tumor-detection.git
cd brain-tumor-detection
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```

3. Train and evaluate the SVM model:

```
python svm_model.py
```

4. Train and evaluate the CNN model:

```
python cnn_model.py
```

## Results

The performance of both SVM and CNN models is evaluated using metrics such as accuracy, precision, recall, and F1-score. Results are presented in the respective model scripts and can be visualized for comparison.

## Contributions

Contributions to improve the models, add new features, or enhance documentation are welcome. Please open a pull request or create an issue to discuss proposed changes.

## License

This project is licensed under the [MIT License](LICENSE).
