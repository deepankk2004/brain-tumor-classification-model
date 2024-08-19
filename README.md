# Brain Tumor Classification using Deep Learning

## Overview

This project aims to classify brain tumors using deep learning techniques, utilizing both TensorFlow and PyTorch frameworks. The model is trained on a dataset consisting of images labeled with different types of brain tumors. The key components of this project include data preprocessing, model architecture design, training, and evaluation.

## Dataset

The dataset used for this project is sourced from the [Kaggle Brain Tumor Classification Dataset](https://www.kaggle.com/prathamgrover/brain-tumor-classification). It consists of images classified into different tumor categories. The dataset is divided into training and validation sets.

## Techniques Used

### 1. Data Preprocessing
- **Resizing Images**: Images are resized to a consistent size of 150x150 pixels for uniformity.
- **Data Augmentation**: Techniques like rotation, width and height shifts, shearing, zooming, and flipping (both horizontal and vertical) are applied to enhance the model's ability to generalize.

### 2. Model Architecture
- **TensorFlow Model**: A model based on MobileNet, a pre-trained deep learning model, is utilized as the base. Custom layers are added on top of the MobileNet architecture to tailor it to the brain tumor classification task.
- **PyTorch Model**: A Convolutional Neural Network (CNN) is designed from scratch, consisting of multiple convolutional and fully connected layers to process the images and predict the tumor class.

### 3. Training and Evaluation
- **Training**: The models are trained on the preprocessed dataset using the Adam optimizer and categorical cross-entropy loss function. The training process is monitored through accuracy and loss metrics on both training and validation sets.
- **Evaluation**: The performance of the models is visualized through plots of training and validation accuracy and loss, providing insights into how well the models are learning the task.

### 4. Data Handling with PyTorch
- **Custom DataLoader**: A custom dataset class is implemented in PyTorch to handle data loading, including image preprocessing and augmentation.
- **Visualization**: Samples from the dataset are visualized to ensure that the data augmentation techniques are being applied correctly.

## Results

The project demonstrates the effectiveness of using deep learning for brain tumor classification. By leveraging both TensorFlow and PyTorch, different aspects of model performance are explored, providing a comprehensive understanding of the classification task.

## Author

This project was developed by **Deepank Yadav**.
yadavdeepank6@gmail.com

---

Feel free to explore the code and modify it for your specific use case. Contributions and feedback are welcome!