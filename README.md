## Projects Overview

### 1. Brain Tumor Detection (`brain_tumor.ipynb`)
- **Objective:** Classify MRI images to detect brain tumors.
- **Database:** Public brain MRI dataset (e.g., Kaggle Brain Tumor Dataset).
- **Preprocessing:** Image resizing, normalization, data augmentation (rotation, flipping).
- **Algorithm Architecture:** Custom CNN with multiple convolutional, pooling, and dense layers.
- **Methodology:** Images are preprocessed and fed into a CNN for binary classification (tumor vs. non-tumor).
- **Results:** Test accuracy of 98.5%.

### 2. Breast Cancer Prediction (`breast_cancer_prediciton.ipynb`)
- **Objective:** Predict whether a tumor is benign or malignant using cell nucleus features.
- **Database:** UCI Breast Cancer Wisconsin (Diagnostic) Dataset.
- **Preprocessing:** Handling missing values, feature scaling (StandardScaler), feature selection.
- **Algorithms Used:** K-Nearest Neighbors (KNN), Support Vector Classifier (SVC).
- **Methodology:** Tabular data is split into train/test sets, scaled, and used to train classical ML models.
- **Results:**  
  - KNN: Mean Accuracy = 97.0%  
  - SVC: Mean Accuracy = 66.0%  
  - KNN performed best.

### 3. Diabetic Eye Diseases Detection (`diabetic_eye_diseases_inceptionv3.ipynb`)
- **Objective:** Detect diabetic retinopathy from retinal images.
- **Database:** Kaggle Diabetic Retinopathy Detection Dataset.
- **Preprocessing:** Image resizing, normalization, augmentation (brightness, rotation).
- **Algorithm Architecture:** InceptionV3 pre-trained CNN
- **Methodology:** Transfer learning—InceptionV3 base is frozen, custom layers are trained for disease stage classification.
- **Results:** Test accuracy = 92.3%.

### 4. Lung Cancer Detection (`lung_cancer_inceptionv3.ipynb`)
- **Objective:** Classify lung cancer from medical images.
- **Database:** Kaggle Lung Cancer CT Scan Dataset.
- **Preprocessing:** Image resizing, normalization, augmentation (zoom, shift).
- **Algorithm Architecture:** InceptionV3 pre-trained CNN.
- **Methodology:** Transfer learning—InceptionV3 base is used, custom layers are trained for cancer detection.
- **Results:** Test accuracy = 95.7%.

### 5. Malaria Detection (`malaria-detection-inceptionv3.ipynb`)
- **Objective:** Detect malaria-infected cells from microscopic images.
- **Database:** NIH Malaria Cell Images Dataset.
- **Preprocessing:** Image resizing, normalization, augmentation (rotation, flip).
- **Algorithm Architecture:** InceptionV3 pre-trained CNN, custom dense layers for binary classification.
- **Methodology:** Transfer learning—InceptionV3 base is frozen, custom layers are trained for malaria detection.
- **Results:** Test accuracy = 97.8%.


