# Part 2: Computer Vision Problem Formulation and CNN Prototype

## Surface Defect Detection Using CNN

### Objective
The objective of this project is to build and evaluate a Convolutional Neural Network (CNN) model for image classification using surface defect image data.

---

## Problem Identification

This dataset represents an Image Classification problem because:
- Each image belongs to one specific category.
- The CNN predicts a single class label for every image.
- The dataset contains multiple defect classes such as:
  - normal
  - scratch
  - dent
  - stain

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- OpenCV
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## Dataset Exploration

The dataset was analyzed for:
- Number of classes
- Images per class
- Sample image visualization
- Image dimensions
- Dataset balance

---

## Image Preprocessing

The preprocessing steps included:
- Image resizing
- Pixel normalization
- Train-validation split
- Data augmentation

---

## CNN Model Architecture

The CNN model contains:
- Convolution layers
- ReLU activation functions
- MaxPooling layers
- Flatten layer
- Dense layers
- Softmax output layer

---

## CNN Concepts

### What is Convolution?
Convolution extracts important visual features such as edges, textures, and patterns from images.

### Why is Pooling Used?
Pooling reduces image dimensions and computational complexity while preserving important features.

### Why is ReLU Commonly Used?
ReLU introduces non-linearity and helps CNNs learn complex image patterns efficiently.

### Why are CNNs Better than Feed-Forward Networks for Images?
CNNs automatically learn spatial features and patterns from images, making them highly effective for computer vision tasks.

---

## Model Evaluation

The CNN model was evaluated using:
- Training accuracy
- Validation accuracy
- Accuracy-loss curves
- Confusion matrix
- Classification report
- Sample image predictions

---

## Business Use Case Mapping

This computer vision solution can be used in manufacturing industries for automated defect detection and quality inspection.

Benefits include:
- Faster inspection
- Reduced manual effort
- Improved product quality
- Real-time defect detection
- Lower operational costs

---

## Repository Structure

part-2-cnn-computer-vision/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
├── sample_predictions/
│   └── prediction_outputs.png
└── results/
    ├── accuracy_loss_curves.png
    └── confusion_matrix.png

---

## Conclusion

In this project, a CNN-based image classification model was successfully built for surface defect detection. The project demonstrated image preprocessing, convolutional neural network learning, feature extraction, model evaluation, and real-world business applications of computer vision systems.
