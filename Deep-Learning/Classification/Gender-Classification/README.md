# Gender Classification using Neural Networks

In this project we will be woring on classifying face images as either belonging to Male(1) class or Female(0) class.

## Dataset

We will use dataset from [Analytics Vidya - Gender Classification Competetion](https://datahack.analyticsvidhya.com/contest/gender-classification/#ProblemStatement)


### Data Description

- train.zip: contains 2 csvs and 1 folder containing all images
- train.csv – [‘image_names’, ‘class’] contains the image name and class name
- image – contains images for both train and test sets
- test.csv: [‘image_names’] contains just the image names for the test set
- sample_submission.csv: [‘image_names’,’class’] contains the exact format for a valid submission

> Note: 
>
> The dataset is not available in this repository. You can download it from the link above.
> After downloading the dataset, extract the zip file inside the input folder.

## What we will cover in this project

We will be covering the following topics in this project:

- Loading the dataset
- Pre-processing the data
- Creating training and validation set
- Defining the MLP model architecture using Keras and PyTorch in two separate notebooks
- Compiling the model
- Training the model
- Evaluating model performance
- Improving the MLP model
- Defining the CNN model architecture using Keras and PyTorch in two separate notebooks
- Improving the CNN model
- Evaluating model performance
- Use Transfer Learning to improve model performance