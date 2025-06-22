🌿 Plant Disease Detection using PyTorch
This project is a deep learning–based model that detects diseases in plant leaves using image classification. Built entirely in PyTorch, it uses a custom Convolutional Neural Network (CNN) to classify images into various plant disease categories.

The model is trained on the "New Plant Diseases Dataset (Augmented)" from Kaggle and achieves high accuracy on the validation set.

🧠 Model Overview
Custom CNN architecture with 2 convolutional layers and 2 fully connected layers

Trained on preprocessed leaf images resized to 128×128

Uses CrossEntropyLoss and Adam optimizer

Evaluated using accuracy, confusion matrix, and classification report

📁 Dataset
Source: New Plant Diseases Dataset (Augmented)

Includes healthy and diseased leaf images across multiple classes

Split into training and validation sets using train_test_split

🚀 How It Works
Loads dataset via kagglehub

Applies PyTorch transforms for preprocessing

Trains for 5 epochs (can be increased)

Saves and reloads the trained model

Evaluates using confusion matrix and precision/recall metrics

🛠️ Tech Stack
Python

PyTorch

Torchvision

scikit-learn (for evaluation)

Matplotlib & Seaborn (for visualization)

📈 Results
Validation accuracy printed after each epoch

Visual confusion matrix for class-wise performance

Full classification report with precision, recall, and F1-scores

📦 Installation (Colab Ready)
bash
Copy
Edit
!pip install kagglehub torch torchvision torchmetrics scikit-learn
📌 Notes
Designed to run on Google Colab

Model weights saved as plant_disease_cnn.pth

Easily extendable to new datasets or deeper models
