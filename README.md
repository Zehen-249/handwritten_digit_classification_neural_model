# Handwritten Digit Classification Neural Model
This project is a neural network-based classifier for recognizing handwritten digits from images. The model is trained using TensorFlow and Keras and achieves high accuracy on the test set.
## The handwritten digits classifier is built using a neural network with the following architecture:
- Input Layer: 400 units (corresponding to 20x20 pixel images)
- Hidden Layer 1: 400 units with ReLU activation
- Dropout Layer 1: Dropout rate of 0.1
- Hidden Layer 2: 250 units with ReLU activation
- Dropout Layer 2: Dropout rate of 0.1
- Output Layer: 10 units with softmax activation (corresponding to 10 digit classes)
  The model is trained on a dataset of 5000 images (4000 for training and 1000 for testing).

## Dataset

The dataset consists of 20x20 pixel grayscale images of handwritten digits. Each image is represented as a flattened array of 400 values. The labels are integers from 0 to 9.

## Requirements

- numpy
- matplotlib
- scikit-learn
- tensorflow
- seaborn

You can install the required libraries using pip:
```bash
pip install numpy matplotlib scikit-learn tensorflow seaborn

```
