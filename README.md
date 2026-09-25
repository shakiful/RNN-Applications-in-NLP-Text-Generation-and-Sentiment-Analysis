# CS5720 Neural Network and Deep Learning - Home Assignment 2

**University of Central Missouri**  
**Course:** CS5720 Neural Network and Deep Learning (Fall 2026)  
**Student Name:** Md Shakiful Islam Khan  

## Project Overview
This repository contains the coding solutions for Home Assignment 2, focusing on the practical implementation of Recurrent Neural Networks (RNNs) for natural language processing and Convolutional Neural Networks (CNNs) for image processing and feature extraction. The tasks are implemented using Python, TensorFlow/Keras, and OpenCV.

## Repository Contents
* `Home_Assignment_2_Code.ipynb`: The main Jupyter Notebook containing all the Python code, outputs, and inline explanations for Questions 1 through 5.
* `README.md`: Project documentation and setup instructions.

## Topics Covered

### Q1: Implementing an RNN for Text Generation
* **Description:** An LSTM-based Recurrent Neural Network designed to predict and generate the next character in a text sequence.
* **Key Concepts:** One-hot encoding, LSTM layers, softmax activation, and temperature scaling to control the randomness of text generation.

### Q2: Sentiment Classification Using RNN
* **Description:** An LSTM model trained on the IMDB sentiment dataset to classify movie reviews as positive or negative.
* **Key Concepts:** Tokenization, sequence padding, binary crossentropy, confusion matrix generation, and the importance of the precision-recall tradeoff in classification.

### Q3: Convolution Operations with Different Parameters
* **Description:** A manual demonstration of convolution operations on a 5x5 input matrix using a 3x3 kernel. 
* **Key Concepts:** TensorFlow's `conv2d` function, applied with varying strides (1 and 2) and padding schemes ('VALID' and 'SAME').

### Q4: CNN Feature Extraction with Filters and Pooling
* **Task 1:** Edge detection on a grayscale image using OpenCV and Sobel-X/Sobel-Y filters.
* **Task 2:** Application of 2x2 Max Pooling and Average Pooling operations on a randomly generated 4x4 matrix using TensorFlow.

### Q5: Implementing and Comparing CNN Architectures
* **Task 1:** Implementation of a simplified AlexNet architecture using Keras Sequential API.
* **Task 2:** Creation of a custom Residual Block and the construction of a simple ResNet-like model using the Keras Functional API.

## Dependencies
To run the code in this repository, ensure you have the following Python libraries installed:
* `tensorflow`
* `numpy`
* `opencv-python` (`cv2`)
* `matplotlib`
* `scikit-learn`

## How to Run
1. Clone this repository to your local machine or download the `.ipynb` file.
2. Open the notebook using **Jupyter Notebook**, **JupyterLab**, or upload it to **Google Colab**.
3. Run the cells sequentially. 
4. *Note for Q4:* The notebook includes a script to automatically download a sample image (`lena.jpg`) for the OpenCV edge detection task. If running locally without internet access, ensure a file named `sample.jpg` is placed in the same directory as the notebook.
