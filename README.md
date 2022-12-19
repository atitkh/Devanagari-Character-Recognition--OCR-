# Devanagari Character Recognition (OCR)

This repository contains a project for optical character recognition (OCR) of Devanagari script, which is used to write the Nepali, Sanskrit, Hindi, and Marathi languages. The OCR system is built using deep learning techniques and is designed to accurately identify and classify Devanagari characters.

## Data Preprocessing

The OCR system is trained on a dataset of images of Devanagari characters. Before training the model, these images must be preprocessed to ensure that they are suitable for use in the OCR system. This includes resizing the images to a uniform size, converting them to grayscale, and removing any noise or distractions from the images.

## Model Training

The OCR system uses a convolutional neural network (CNN) to classify the Devanagari characters. The CNN is trained using the preprocessed data and is optimized using techniques such as data augmentation and dropout regularization.

## Evaluation

After training the model, it is evaluated on a separate test dataset to measure its accuracy and performance. The OCR system is designed to achieve high accuracy in character classification.

## Future Work

There is still room for improvement in the OCR system, and future work could include:

1. Improving the preprocessing of the training data to further reduce noise and distractions
2. Experimenting with different CNN architectures and optimization techniques to improve performance
3. Expanding the dataset to include a wider range of Devanagari characters and fonts
