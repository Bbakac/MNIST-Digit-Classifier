# MNIST Digit Classifier

This project is a simple implementation of a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset using TensorFlow and Keras. The code includes data preprocessing, model building, training, evaluation, and visualization of predictions.

## Requirements

- Python 3.7 or higher
- TensorFlow 2.x
- NumPy
- Matplotlib

## Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Bbakac/MNIST-Digit-Classifier.git
   cd MNIST-Digit-Classifier
   ```
   ```bash
   pip install tensorflow numpy matplotlib
   ```

Running the Project
Start Jupyter Notebook:
 ```bash
jupyter notebook MNIST-Digit-Classifier.ipynb
```

Train the model:
The script will build a Sequential model with the following architecture:

Input layer with shape (28, 28, 1)
Conv2D layer with 32 filters and kernel size (3, 3) with ReLU activation
MaxPooling2D layer with pool size (2, 2)
Flatten layer
Dense layer with 128 units and ReLU activation
Output Dense layer with 10 units and softmax activation
The model is compiled using the Adam optimizer and categorical cross-entropy loss function. It is trained for 10 epochs with a batch size of 32.

Evaluate the model:
After training, the model is evaluated on the test dataset. The loss and accuracy are printed to the console.

Make predictions:
The model makes predictions on the first 5 images from the test dataset. The predictions and actual labels are printed and visualized using Matplotlib.

Results
After training, the model is evaluated on the test dataset, and the accuracy and loss are printed to the console. The script also visualizes the model's predictions for the first 5 test images.





