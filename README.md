# MNIST Dataset Classification using Neural Network

## Aim

To build and evaluate a Neural Network model for handwritten digit classification using the MNIST dataset.

## Dataset

The MNIST dataset consists of 70,000 grayscale images of handwritten digits (0–9).

* Training Images: 60,000
* Testing Images: 10,000
* Image Size: 28 × 28 pixels
* Number of Classes: 10

## Methodology

1. Upload and extract the dataset.
2. Load image and label files.
3. Visualize sample images.
4. Normalize pixel values.
5. Build a feedforward neural network.
6. Train the model using Adam optimizer.
7. Evaluate performance on unseen test data.
8. Visualize accuracy and loss curves.
9. Generate confusion matrix.
10. Perform sample predictions.

## Neural Network Architecture

* Input Layer: 784 neurons (Flatten Layer)
* Hidden Layer 1: 128 neurons (ReLU)
* Hidden Layer 2: 64 neurons (ReLU)
* Output Layer: 10 neurons (Softmax)

## Results

* Test Accuracy: 97.43%
* Test Loss: 0.105

The model successfully classified handwritten digits with high accuracy and demonstrated strong generalization performance.

## Conclusion

The Neural Network effectively learned digit patterns from the MNIST dataset and achieved excellent classification performance with approximately 97.43% accuracy on unseen test data.
