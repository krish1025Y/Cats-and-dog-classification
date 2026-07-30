# 🐱🐶 Cat vs Dog Image Classification

A Convolutional Neural Network (CNN) built using **PyTorch** to classify images as either **Cat** or **Dog**.

## 🚀 Features

* Image preprocessing using Torchvision
* CNN architecture built from scratch
* Binary image classification
* Training and validation accuracy tracking
* Testing on external images not included in the dataset
* Confidence score for predictions

## 🧠 Model Architecture

The CNN consists of:

* 3 Convolutional layers
* ReLU activation functions
* Max Pooling layers
* Fully Connected layers
* 2 output classes: `Cat` and `Dog`

## 🛠️ Technologies Used

* Python
* PyTorch
* Torchvision
* NumPy
* PIL
* Jupyter Notebook

## 📊 Results

Current validation accuracy: **~67%**

The model was also tested using external images to evaluate how it performs on images outside the training, validation, and test datasets.

## 📁 Project Structure

```text
Cat-Dog-CNN/
│
├── CNN.ipynb
├── README.md
└── dataset/
```

## ▶️ How to Run

1. Clone the repository.
2. Install the required dependencies:

```bash
pip install torch torchvision pillow numpy
```

3. Open the Jupyter Notebook:

```bash
jupyter notebook
```

4. Run the notebook cells to train and test the model.

## 📌 Future Improvements

* Increase dataset size
* Add data augmentation
* Reduce overfitting
* Improve validation accuracy
* Experiment with pretrained CNN architectures
