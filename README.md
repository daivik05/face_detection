# Face Detection System

This Python script implements a face detection system using machine learning techniques. It leverages the use of PCA (Principal Component Analysis) for feature extraction and SVM (Support Vector Machine) for classification to detect faces in images.

## Overview

The face detection system follows these steps:

1. **Clone Repository**: The script clones a GitHub repository named "face_detection" to access the necessary files and data for face detection. The repository URL is [here](https://github.com/daivik05/face_detection).

2. **Load Data**: It loads face data from a CSV file named "face_data.csv", containing pixel values of face images as well as target labels.

3. **Display Original Images**: It displays the original face images from the dataset.

4. **Split Data**: The dataset is split into training and testing sets using the `train_test_split` function from scikit-learn.

5. **Feature Extraction**: PCA is applied to the training data to extract principal components (eigenfaces) that represent the variation in face images.

6. **Visualize Eigenfaces**: It displays the eigenfaces obtained from PCA, which represent the most significant features in the face images.

7. **Model Training**: An SVM classifier with an RBF kernel is trained on the transformed data obtained from PCA.

8. **Model Evaluation**: The trained model is used to predict faces on the test set, and a classification report is generated to evaluate the performance of the face detection system.

## Usage

To use the Face Detection System:

1. Ensure you have the required dependencies installed (`numpy`, `pandas`, `matplotlib`, `scikit-learn`).
2. Clone the GitHub repository containing the face detection code and data.
3. Run the script (`face_detection.py`) to perform face detection on the provided dataset.
4. Review the classification report to assess the accuracy and performance of the face detection system.

## Requirements

- Python 3.x
- `numpy`, `pandas`, `matplotlib`, `scikit-learn` libraries

## Contributing

Contributions to enhance the face detection system, improve classification accuracy, or optimize performance are welcome! Please feel free to submit pull requests or open issues if you encounter any problems.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
