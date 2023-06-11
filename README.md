# Driver Distraction Classification Model with Transfer Learning and CNN

This repository contains code for a driver distraction classification model using transfer learning and Convolutional Neural Networks (CNNs). The model is designed to classify images of drivers into different distraction categories based on the input images.

## Table of Contents
1. [Introduction](#introduction)
2. [Usage](#usage)
3. [Model Performance](#model-performance)
4. [Contributing](#contributing)
5. [License](#license)

## Introduction
The driver distraction classification model is developed to assist in identifying different distraction types of drivers using images. The model employs transfer learning techniques with pre-trained CNN models like VGG16 and EfficientNet. The repository includes code for data preprocessing, model training, evaluation, and deployment.


## Usage
1. Prepare the dataset:
- Place the driver images in the 'imgs/train' folder, organized into subfolders based on the distraction classes.
- Update the 'driver_imgs_list.csv' and 'sample_submission.csv' files with the relevant information.

2. Data exploration and preprocessing:
- Run the Jupyter Notebook or Python script to explore the dataset and preprocess the images.

3. Model training:
- Choose the desired model architecture (CNN, VGG16, or EfficientNet) by uncommenting the respective sections in the code.
- Run the training code to train the model using the preprocessed dataset.

4. Model evaluation:
- Evaluate the trained models by running the corresponding code sections for each model architecture.
- The evaluation includes plotting training and validation loss/accuracy and displaying confusion matrices.

5. Model selection and deployment:
- Evaluate the models based on performance metrics and select the best model.
- The selected model can be saved for further use or deployment.

## Model Performance
The performance of the trained models is evaluated using validation data. The evaluation metrics include loss and accuracy values. The models are compared based on these metrics, and the best-performing model is selected.

## Contributing
Contributions to the project are welcome! If you have any ideas, improvements, or bug fixes, please open an issue or submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

