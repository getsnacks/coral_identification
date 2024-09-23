# Coral Identification Model

This project implements a coral identification model using TensorFlow and Keras. The model has been trained on a dataset of coral images and to determine whether the corals are healthy or bleached.

## Requirements

To run the project, you need the following libraries:

- TensorFlow
- NumPy
- Matplotlib

## Dataset

The dataset is contained in the `coral_dataset_merged.zip` file. The model reads images from this dataset for training.

## Training the Model

To train the model, follow these steps:

1. Load the required libraries.
2. Extract the dataset and split it into training, validation, and test sets.
3. Create and compile the model.
4. Train the model.