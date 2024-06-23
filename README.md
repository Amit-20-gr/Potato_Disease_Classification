# Potato_Disease_Classification
In this project, I used a convolutional neural network (CNN) to identify potato diseases. The CNN classifies the potato condition into three categories: healthy, early blight, or late blight.
## Dataset

The dataset used for this project consists of images of potato leaves. The categories included are:

- Healthy
- Early Blight
- Late Blight

The images were pre-processed and split into training, validation, and testing sets to evaluate the model's performance.

## Model Architecture

A Convolutional Neural Network (CNN) was designed with the following architecture:

- Input Layer: Accepts images of potato leaves.
- Convolutional Layers: Several layers with ReLU activation and max-pooling.
- Fully Connected Layers: To perform the final classification.

## Training and Results
The model was trained using 10 epochs, achieving a notable accuracy of **94.6%**. The results suggest that the model can be further improved by increasing the number of epochs or fine-tuning other hyperparameters.
