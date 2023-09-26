# Rock, Paper, Scissors Image Classification using TensorFlow
This repository contains a simple image classification project that uses TensorFlow to classify images of rock, paper, and scissors. The project consists of several steps, including data preparation, model creation, training, and prediction.

### Dataset
I use the Rock, Paper, Scissors dataset, which can be downloaded from the following link:
[Rock, Paper, Scissors Dataset]( https://github.com/dicodingacademy/assets/releases/download/release/rockpaperscissors.zip)

The dataset contains images of rock, paper, and scissors, which are divided into training and validation sets.

### Data Preprocessing
I perform data augmentation on the images using the ImageDataGenerator class from TensorFlow to improve model generalization. Data augmentation includes operations like rotation, horizontal flipping, shear, zoom, and brightness adjustments.

### Model Architecture
I create a convolutional neural network (CNN) model using the Sequential API from TensorFlow.

### Model Compilation
I compile the model by specifying the loss function, optimizer, and evaluation metrics.

### Model Training
I train the model using the training and validation datasets. I also use callback functions to adjust the learning rate during training and log the training process.

### Model Evaluation
After training, I evaluate the model's accuracy on the validation dataset.

## Making Predictions
I can use the trained model to make predictions on new images.

Note: The upload widget is only available when the cell has been executed in the current browser session. Please rerun the cell to enable it.

Feel free to use and modify this code for your image classification projects!
