# CIFAR-10 Image Classification with PyTorch
This project implements a Convolutional Neural Network (CNN) in PyTorch to classify images from the CIFAR-10 dataset. The code was developed and tested in Google Colab.
Features
Dataset: CIFAR-10 (60,000 images, 10 classes)

Framework: PyTorch

Model: 2 Convolutional layers + MaxPooling + Dropout + Fully Connected layers

Training: SGD optimizer, CrossEntropy loss

Visualization: Display sample images with labels

Performance Metrics: Training and test accuracy, loss plots

Project Structure
├── data/ # Downloaded CIFAR-10 dataset
├── cnn_cifar10.ipynb # Google Colab notebook
├── README.md # Project description

How to Run
Clone this repository:
git clone https://github.com/your-username/cifar10-pytorch.git

Open in Google Colab or Jupyter Notebook.

Install dependencies (if running locally):
pip install torch torchvision matplotlib

Run the notebook cells step-by-step to:

Load CIFAR-10 data

Define and train the CNN

Evaluate the model

Sample Output
Example visualization of CIFAR-10 images with labels:

Loss curve during training:

Results
Test accuracy: ~62%

Training accuracy: ~65% (10 epochs)

License
This project is licensed under the MIT License - see the LICENSE file for details.

Author: Ayberk Caf
Date: 2025
