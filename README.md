#  PyTorch FashionMNIST Classifier

A beginner-friendly computer vision project using PyTorch. This notebook demonstrates a full image classification pipeline on the The [FashionMNIST](https://pytorch.org/vision/stable/generated/torchvision.datasets.FashionMNIST.html) dataset consists of 28x28 grayscale images of 10 fashion categories:
- T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot

##  Model Architecture

- Input: 28×28 images (flattened to 784)
- Hidden layers: Linear + ReLU
- Output: 10-class prediction using `nn.CrossEntropyLoss`

##  What inside

- How to load and visualize image data with `torchvision`
- How to define a neural network using `torch.nn`
- How to train a model using `DataLoader`, loss functions, and optimizers
- How to evaluate accuracy on test data
- How to organize a basic PyTorch project



