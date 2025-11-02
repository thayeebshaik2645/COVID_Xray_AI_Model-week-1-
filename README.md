COVID-19 X-Ray Classification using CNN
📘 Project Overview

This project uses a Convolutional Neural Network (CNN) to classify chest X-ray images into two categories: 
PNEUMONIA and NORMAL. The model is trained using a dataset of labeled X-ray images to help automate the 
diagnosis process and assist medical professionals in early detection of pneumonia and COVID-related infections.

🎯 Problem Statement

Pneumonia remains a leading cause of respiratory illness and death globally, particularly among children, the elderly, and immunocompromised individuals.
Traditional diagnosis through chest X-rays requires expert radiologists and can be time-consuming, subjective, and prone to human error, especially under heavy clinical workloads.
With the growing availability of digital medical imaging, there is a strong need for an automated diagnostic system that can assist medical professionals in identifying pneumonia accurately and rapidly.

This project aims to design and implement a CNN-based classification model that:
-Automatically classifies chest X-ray images into PNEUMONIA or NORMAL categories.
-Reduces dependency on manual interpretation.
-Provides a faster and more consistent diagnostic aid.
-Contributes to sustainable healthcare practices by enhancing efficiency in medical image analysis.

📂 Dataset Description

The dataset consists of chest X-ray images categorized into two classes: NORMAL and PNEUMONIA.
- Training set: Images used to train the CNN model.
- Testing set: Images used to evaluate model performance.

Dataset structure:
xray_dataset_covid19/
 ┣ train/
 ┃ ┣ NORMAL/
 ┃ ┗ PNEUMONIA/
 ┗ test/
    ┣ NORMAL/
    ┗ PNEUMONIA/

🧠 Model Architecture

The CNN model is built using TensorFlow and Keras, featuring:
- Convolutional layers for feature extraction.
- MaxPooling layers for dimensionality reduction.
- Dense layers for classification.
- Dropout layer to prevent overfitting.

Optimizer: Adam  
Loss function: Binary Crossentropy  
Metrics: Accuracy

📈 Model Training & Evaluation

The model was trained for 10 epochs. The accuracy improved steadily across epochs, achieving over 90% validation accuracy.

Example metrics:
- Training Accuracy: ~70-80%
- Validation Accuracy: ~93-100%

🚀 Deployment

The project notebook can be accessed and executed directly in Google Colab using the link below:
[Open in Google Colab](https://colab.research.google.com/drive/1R2lEUVdJKFi4lF6_B5omRkrT7ndcX2zW?usp=sharing)

💡 Future Improvements
-Add more data for better generalization
-Experiment with pre-trained models like VGG16 or ResNet50
-Deploy model using Streamlit for real-time X-ray image classification

⚖️ License

This project is licensed under the Apache License 2.0.  
You may use, distribute, and modify this code with proper attribution.

