# License Plate Recognition Project

## Introduction

This project is a comprehensive approach to License Plate Recognition (LPR), which involves detecting license plates in vehicle images and recognizing the alphanumeric characters on these plates. The project uses deep learning techniques for both detection and recognition tasks.

## Project Structure

The project is organized into the following modules:
1. *Data Preparation*: Loading and preprocessing the data.
2. *Model Building*: Defining and compiling the detection and recognition models.
3. *Model Training*: Training the detection and recognition models.
4. *Prediction and Evaluation*: Running the models on the test dataset and saving the results.

## Installation

To run this project, you'll need to install the following libraries:

sh
pip install opencv-python tensorflow pandas numpy matplotlib scikit-learn


## Dataset

The datasets are organized as follows:
- license_plates_recognition_train: Contains images of license plates.
- license_plates_detection_train: Contains images of vehicles with license plates.
- Licplatesrecognition_train.csv: Contains img_id and text (license plate text).
- Licplatesdetection_train.csv: Contains img_id, ymin, xmin, ymax, xmax.

The test images are located in the test folder.

## Modules

### 1. Data Preparation (data_preparation.py)

This module handles loading and preprocessing the datasets.

### 2. Model Building (model_building.py)

This module defines the architecture of the detection and recognition models.

### 3. Model Training (model_training.py)

This module trains the detection and recognition models using the preprocessed data.

### 4. Prediction and Evaluation (prediction_evaluation.py)

This module runs the trained models on the test dataset and saves the results to a CSV file.

## Running the Project

1. *Data Preparation*: Execute data_preparation.py to load and preprocess the data.
2. *Model Building*: Execute model_building.py to define the model architectures.
3. *Model Training*: Execute model_training.py to train the models.
4. *Prediction and Evaluation*: Execute prediction_evaluation.py to run the models on the test set and save the results.

## Results

The results will be saved in a CSV file named test_results.csv, containing the image names and the corresponding recognized license plate texts.

## Conclusion

This project demonstrates a complete pipeline for License Plate Recognition using deep learning. The process involves data preparation, model building, model training, and evaluation on a test set. This approach can be further improved by experimenting with different model architectures and hyperparameters.
