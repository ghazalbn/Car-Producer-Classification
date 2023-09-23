# Car Producer Classification

This project focuses on classifying car producers using deep learning techniques. The code provided here includes data preparation, model creation, training, and prediction using both a custom CNN model and transfer learning from a pre-trained MobileNetV2 model. Additionally, it demonstrates the use of Grad-CAM to visualize model attention.

## Table of Contents

- [Data Preparation](#data-preparation)
- [Define Global Variables](#define-global-variables)
- [Custom CNN Model](#custom-cnn-model)
- [Callbacks](#callbacks)
- [Training the Custom CNN Model](#training-the-custom-cnn-model)
- [Training and Validation Plots](#training-and-validation-plots)
- [Making Predictions](#making-predictions)
- [Transfer Learning from MobileNetV2](#transfer-learning-from-mobilenetv2)
- [Training the Transfer Learning Model](#training-the-transfer-learning-model)
- [Training and Validation Plots (Transfer Learning)](#training-and-validation-plots-transfer-learning)
- [Making Predictions (Transfer Learning)](#making-predictions-transfer-learning)
- [Grad-CAM Visualization](#grad-cam-visualization)
- [License](#license)

## Data Preparation <a name="data-preparation"></a>

In this section, we read and preprocess the images and create the necessary training, validation, and test sets.

## Define Global Variables <a name="define-global-variables"></a>

You can modify these global variables as needed for your project.

- Number of Classes: 5
- Number of Epochs: 20
- Batch Size: 32
- Input Shape: (224, 224, 3)
- Target Size: (224, 224)
- Base Folder: ./data/

## Custom CNN Model <a name="custom-cnn-model"></a>

Here, we define the architecture of the custom CNN model for car producer classification.

## Callbacks <a name="callbacks"></a>

We define callbacks for early stopping, learning rate reduction, and model checkpointing.

## Training the Custom CNN Model <a name="training-the-custom-cnn-model"></a>

We train the custom CNN model using the prepared data and callbacks.

## Training and Validation Plots <a name="training-and-validation-plots"></a>

Plots for training and validation accuracy as well as training and validation loss are displayed.

## Making Predictions <a name="making-predictions"></a>

We load the trained custom CNN model and make predictions on the test data.

## Transfer Learning from MobileNetV2 <a name="transfer-learning-from-mobilenetv2"></a>

In this section, we implement transfer learning using the MobileNetV2 pre-trained model.

## Training the Transfer Learning Model <a name="training-the-transfer-learning-model"></a>

We train the transfer learning model using the prepared data and callbacks.

## Training and Validation Plots (Transfer Learning) <a name="training-and-validation-plots-transfer-learning"></a>

Plots for training and validation accuracy as well as training and validation loss for the transfer learning model are displayed.

## Making Predictions (Transfer Learning) <a name="making-predictions-transfer-learning"></a>

We load the trained transfer learning model and make predictions on the test data.

## Grad-CAM Visualization <a name="grad-cam-visualization"></a>

For some random images from different classes, we visualize the heatmaps based on the Grad-CAM algorithm.

## License <a name="license"></a>

This project is licensed under the [MIT License](LICENSE). Feel free to adapt and use the code and resources provided here for your own projects, subject to the terms and conditions of the MIT License.

