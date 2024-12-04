# Deep Neural Network for Image Classification

This project implements a deep L-layer neural network for image classification tasks, specifically focusing on a "cat vs. non-cat" classification problem. It demonstrates key techniques in deep learning, such as building and training multi-layer neural networks, implementing preprocessing pipelines, and visualizing results.

## Features
- **L-Layer Neural Network Architecture**: Build and train a deep neural network using modular and reusable functions.
- **Data Preprocessing**: Efficient normalization and reshaping of image data for training.
- **Training and Optimization**: Gradient descent optimization techniques applied to minimize loss.
- **Visualization**: Clear visualizations of learning curves, predictions, and performance metrics using Matplotlib.

## Project Structure
- **Model Development**:  
  The deep learning model is implemented with reusable functions for forward propagation, backward propagation, and parameter updates. The architecture includes:  
  - A 2-layer neural network  
  - An L-layer deep neural network  
- **Dataset Processing**:  
  The dataset includes labeled images for binary classification. Preprocessing steps include resizing and normalizing pixel values.  
- **Results Analysis**:  
  After training, the model's predictions are compared to ground truth labels, and results are analyzed using visualization techniques.

## Key Libraries
The project makes use of the following libraries:
- `numpy`: For numerical computations and data manipulation.
- `matplotlib`: For creating visualizations of the training process and results.
- `scipy`: For advanced mathematical operations.

## Setup and Requirements
To run the project, ensure you have Python 3.x installed along with the required libraries. Install the dependencies using the following command:

```bash
pip install numpy matplotlib scipy
