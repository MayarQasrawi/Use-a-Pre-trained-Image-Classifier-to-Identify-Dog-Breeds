# Use a Pre-trained Image Classifier to Identify Dog Breeds 🐶 

## 📋 Project Description

This Python project uses pre-trained image classifiers to identify dog breeds from images. It demonstrates how to leverage existing deep learning models to perform image classification without training a model from scratch.

## 🔑 Project Structure

- **check_images.py**: Main script that processes command line arguments and runs the classifier
- **classify_images.py**: Contains the classifier logic to process images and identify breeds
- **calculates_results_stats.py**: Calculates statistics on the classification results
- **print_results.py**: Formats and prints the results to the console
- **adjust_results4_isadog.py**: Adjusts results to check if classified labels are dogs
- **get_input_args.py**: Handles command line arguments
- **get_pet_labels.py**: Extracts pet names from image filenames
- **classifier.py**: Contains the pre-trained classifier models

## 🧠 Features

- Uses pre-trained CNN models (ResNet, AlexNet, VGG)
- Classifies images against known dog breeds
- Validates if the classified objects are actually dogs
- Calculates classification accuracy statistics
- Processes both dog and non-dog images


## 📊 Output

The program outputs:
- Number of images processed
- Number of correct dog classifications
- Number of correct breed classifications
- Number of correct non-dog classifications
- Overall classification accuracy
