# Celebrity Face Recognition and Classification

This project implements a comprehensive system for celebrity face recognition using computer vision and machine learning techniques. The system includes image processing, face and eye detection, cropping, feature extraction, data preparation, model training, evaluation, algorithm comparison, and visualization.

## Key Features

- **Image Processing**: Utilized the OpenCV library to read and manipulate images. Converted images to grayscale for simplifying further processing.
- **Face and Eye Detection**: Employed Haarcascades classifiers for detecting faces and eyes in images. Drew bounding boxes around the detected faces and eyes.
- **Cropping and Feature Extraction**: Cropped the images to focus on the detected face region. Used PyWavelets for feature extraction, enhancing the model's ability to distinguish between celebrities.
- **Data Preparation**: Created a directory named 'Cropped' to store the cropped face images. Iterated through celebrity image folders, detecting and cropping faces with detectable eyes. Stored the cropped face images in the 'Cropped' folder and maintained a dictionary with celebrity names.
- **Model Training**: Reshaped the cropped face images to prepare them for model training. Trained the model using a variety of machine learning algorithms, including SVM, random forest, and logistic regression.
- **Model Evaluation**: Evaluated the trained models on testing sets to assess their accuracy and performance. Employed GridSearchCV for hyperparameter tuning to enhance model performance.
- **Algorithm Comparison**: Explored and compared the performance of SVM, random forest, and logistic regression algorithms. Selected the algorithm with the highest accuracy score (SVM with a 0.9 score).
- **Confusion Matrix and Visualization**: Used the confusion matrix to analyze the model's performance in terms of true positive, true negative, false positive, and false negative predictions. Visualized the confusion matrix using a heatmap for a clear understanding of classification results.

- Overall, the project demonstrates a robust pipeline for celebrity face recognition, classification, and model evaluation, utilizing image processing, feature extraction, and machine learning techniques. The inclusion of PyWavelets and algorithm comparison adds depth to the project's technical approach.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/celebrity-face-recognition.git
   cd celebrity-face-recognition
