This project presents a hybrid deep learning and machine learning pipeline for the automated detection of lemon leaf diseases. It leverages pretrained convolutional neural networks—VGG16, VGG19, and ResNet50—for feature extraction, and employs classical machine learning classifiers such as K-Nearest Neighbors (KNN), Random Forest, Naive Bayes, and Logistic Regression for accurate disease classification.

The primary objective is to support lemon farmers in Manipur, particularly in Kachai Village, by providing an efficient and scalable solution for early disease detection, thereby advancing sustainable and precision agriculture.

The model was trained on the Lemon Leaf Disease Dataset (LLDD), which originally contained 1,354 images, and was expanded through augmentation to a total of 7,547 labeled images covering 9 distinct lemon leaf disease classes which i downloaded and used from kaggle https://www.kaggle.com/datasets/mahmoudshaheen1134/lemon-leaf-disease-dataset-lldd/data




![image](https://github.com/user-attachments/assets/3c4bf9e7-7028-416d-ba02-77501e9c202b)

The methodology involves preprocessing leaf images by resizing them to 224×224 and normalizing pixel values, followed by feature extraction using pretrained CNN models (VGG16, VGG19, ResNet50). These deep features are then classified using traditional machine learning algorithms such as K-Nearest Neighbors, Random Forest, Naive Bayes, and Logistic Regression. Model performance is evaluated using accuracy metrics, visualized through charts and tables, and the results are saved as .pkl model files and a comprehensive model_performance_summary.csv.

This intelligent lemon leaf disease detection system functions like a digital plant doctor—analyzing visual patterns through deep learning, identifying disease symptoms, and delivering precise, actionable diagnoses to help farmers take timely, informed decisions.







