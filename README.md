# Fashion-MNIST Image Classification (PyTorch)

This is a beginner-friendly machine learning project that demonstrates how to
train and evaluate a simple neural network using PyTorch.

The goal of this project is to understand the full machine learning workflow:
data loading, model training, evaluation, and visualization.

---

## Dataset

This project uses the **Fashion-MNIST** dataset, which consists of 28×28 grayscale
images of clothing items such as shirts, trousers, shoes, and bags.
There are **10 different classes** in total.

---

## Model

The model is a **simple fully connected neural network** built with PyTorch.

- Input: 28×28 images (flattened)
- Hidden layers with ReLU activation
- Output layer with 10 classes

The architecture is intentionally kept simple for learning purposes.

---

## Training

- Optimizer: Adam  
- Loss Function: CrossEntropyLoss  
- Batch size: 32  
- Epochs: 5  

The model was trained for a small number of epochs to keep training fast and
focus on understanding the training process rather than maximizing accuracy.

---

## Evaluation

The model is evaluated on a separate test dataset using accuracy as the metric.

**Test Accuracy:** ~87%

Evaluation is performed using:
- `model.eval()`
- `torch.no_grad()`

to ensure no gradients are computed during testing.

---

## Visualizations

The project includes visualizations such as:
- Sample images
