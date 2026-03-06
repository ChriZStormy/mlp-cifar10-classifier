```markdown
# CIFAR-10 Multi-Layer Perceptron (MLP) Classifier 🖼️

A deep learning project implementing a Multi-Layer Perceptron (MLP) neural network to classify the **CIFAR-10** dataset. This repository demonstrates foundational computer vision techniques using standard fully connected layers before transitioning into Convolutional Neural Networks (CNNs).

## 🎯 Project Overview
The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes (dogs, cats, cars, ships, etc.). This project handles the data pipeline—flattening the 3D image tensors into 1D vectors (3072 features)—and passes them through a custom Multi-Layer Perceptron to predict the correct class.

## 🚀 Key Features
* **Data Pipeline:** Custom data loading, tensor transformations, and normalization for the CIFAR-10 dataset.
* **MLP Architecture:** Design of a fully connected neural network with hidden layers and non-linear activations.
* **Training & Validation Loop:** Implementation of the training loop using Cross-Entropy Loss and optimization algorithms (e.g., Adam/SGD).
* **Performance Evaluation:** Tracking of training loss, validation accuracy, and classification metrics.

## 🛠️ Tech Stack
* **Deep Learning Framework:** PyTorch / Keras (Ajusta esto según lo que hayas usado)
* **Data Processing:** Torchvision / NumPy
* **Visualization:** Matplotlib (for loss/accuracy curves)

## 📈 Results
*(Note: Insert a screenshot here of your Loss/Accuracy graph or your final accuracy percentage on the test set)*
- **Final Test Accuracy:** XX%
- **Loss Convergence:** Reached stability at epoch XX.

## ⚙️ How to Run
Open the Jupyter Notebook `MLP_CIFAR10_Practica.ipynb` and run the cells sequentially to download the dataset, train the network, and evaluate the model.
