# Vighnesh-Chorge-Iris-Flower-Classifier-using-Neural-Networks
A neural network model built with Keras to classify Iris flower species based on sepal and petal features. Uses one-hot encoding and ReLU-activated dense layers to train on the classic Iris dataset with over 90% accuracy.


# 🌸 Iris Flower Classification using Neural Networks

This project implements a neural network using Keras to classify Iris flower species (Setosa, Versicolor, Virginica) based on four features: sepal length, sepal width, petal length, and petal width.

## 🚀 Features

- Feedforward neural network (Multi-layer Perceptron)
- One-hot encoding for target labels
- ReLU activation and Softmax output
- Trained using Adam optimizer and categorical crossentropy
- Achieves high accuracy on the Iris dataset

## 📦 Dependencies

- scikit-learn  
- keras  
- tensorflow  
- numpy  

Install with:

```bash
pip install scikit-learn keras tensorflow numpy
````

## 🧪 How to Run

1. Clone this repository
2. Run the Python script:

```bash
python iris_nn.py
```

## 📊 Dataset Info

* **Source**: Built-in `sklearn.datasets.load_iris()`
* **Classes**:

  * 0: Setosa
  * 1: Versicolor
  * 2: Virginica
* **Features**: 4 numeric input attributes

## ✅ Results

* 3-layer neural network
* Trained for 200 epochs
* Final test accuracy: \~95% (may vary slightly)

## 🔧 Possible Improvements

* Add dropout for regularization
* Hyperparameter tuning
* Visualize training loss and accuracy

```
