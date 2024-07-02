# Celebrity Face Recognition and Classification

This project implements a comprehensive system for celebrity face recognition using computer vision and machine learning techniques. The system includes image processing, face and eye detection, cropping, feature extraction, data preparation, model training, evaluation, algorithm comparison, and visualization.

## Key Features

- **Image Processing**: Utilized OpenCV to manipulate and preprocess images, converting them to grayscale for simplifying further processing.
- **Face and Eye Detection**: Implemented Haarcascades classifiers to detect and draw bounding boxes around faces and eyes in images.
- **Cropping and Feature Extraction**: Cropped detected face regions and used PyWavelets for feature extraction to enhance model accuracy.
- **Data Preparation**: Organized cropped face images into a 'Cropped' directory and maintained a dictionary with celebrity names.
- **Model Training**: Trained models using SVM, random forest, and logistic regression algorithms after reshaping cropped face images.
- **Model Evaluation**: Evaluated model performance using testing sets, employing GridSearchCV for hyperparameter tuning.
- **Algorithm Comparison**: Compared SVM, random forest, and logistic regression algorithms, selecting SVM for its highest accuracy.
- **Confusion Matrix and Visualization**: Analyzed model performance through confusion matrix visualization using heatmap for clear classification insights.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/celebrity-face-recognition.git
   cd celebrity-face-recognition
