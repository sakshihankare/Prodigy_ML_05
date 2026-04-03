# Food Recognition & Calorie Estimation using Deep Learning

##  Overview

This project focuses on building a deep learning-based image classification system capable of identifying food items and estimating their calorie content. The model is trained on the Food-101 dataset and leverages transfer learning for efficient and fast performance.

##  Features

* Classifies food images into 101 categories
* Estimates calorie values for selected food items
* Uses transfer learning with MobileNetV2 for optimized performance
* Lightweight and fast training with reduced image size and batch size
* Includes performance visualization (accuracy and loss curves)

##  Tech Stack

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* KaggleHub

##  Model Details

* Base Model: MobileNetV2 (pre-trained on ImageNet)
* Image Size: 128x128
* Batch Size: 8
* Optimizer: Adam
* Loss Function: Sparse Categorical Crossentropy
* Regularization: Dropout + L2 Regularization
* Early Stopping used to prevent overfitting

##  Results

The model achieves reasonable performance considering the reduced dataset and lightweight configuration, making it suitable for quick experimentation and prototyping.

##  Visualizations

* Training vs Validation Accuracy
* Training vs Validation Loss

##  Future Improvements

* Improve accuracy with full dataset training
* Expand calorie database for all classes
* Fine-tune base model for better performance
* Deploy as a web or mobile application

##  Conclusion

This project demonstrates how deep learning can be applied to real-world problems like food recognition and calorie estimation while maintaining efficiency and scalability.
