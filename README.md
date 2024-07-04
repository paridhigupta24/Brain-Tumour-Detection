# Brain-Tumour-Detection using Convolutional Neural Networks.

This project focuses on creating a convolutional neural network (CNN) for detecting brain tumors using MRI images. 
The dataset used is sourced from Kaggle, consisting of 253 brain MRI images categorized into two folders: "yes" and "no".

Dataset Overview:

Total Images: 253 Brain MRI Images

Categories:

"yes": 155 Brain MRI Images with tumors

"no": 98 Brain MRI Images without tumors

The objective is to develop a robust CNN model leveraging TensorFlow and Keras to accurately classify brain MRI scans into tumorous and non-tumorous categories.

Repository Contents:

- Model Training: Jupyter Notebook detailing the CNN architecture, training process, and performance evaluation.
- Data Preparation: Scripts or notebooks for preprocessing, augmenting, and loading the MRI images.
- Evaluation: Metrics, graphs, and visualizations showcasing model performance and predictions.
- Deployment: Guidelines or scripts for deploying the trained model for inference.


Dataset Source: Kaggle - Brain MRI Images for Brain Tumor Detection

The image was trained for 24 epochs and these are the loss & accuracy plots:

![image](https://github.com/paridhigupta24/Brain-Tumour-Detection/assets/110227813/894f24dc-629f-4861-b981-92c2bb49dd1c)
![image](https://github.com/paridhigupta24/Brain-Tumour-Detection/assets/110227813/5b5f5c07-4f1c-4916-bee4-e1765ceeda6f)

The data was split in the following way:

1) 70% of the data for training.
2) 15% of the data for validation.
3) 15% of the data for testing.
