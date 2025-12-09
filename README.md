# Facial Recognition Case Study
Using a CNN Model to identify Your Photos Among Celebrity Images 

Welcome to the Facial Recognition Case Study. In this project you will build a complete image based machine learning pipeline that trains a model to recognize your photos. You will combine your own images with a large celebrity dataset, prepare the data, explore it, clean it, and then train a convolutional neural network that learns to separate your class from the celebrity class.


## Repository Structure

├── Data
│   ├── Data Instructions.md
├── Supplemental Scripts
│   ├── CNN_source1.pdf
    ├── CNN_source2.pdf
├── README.md
├── Scripts
│   ├── Facial Recognition (1).ipynb
├── CS3Rubric.md
├── CS3_Hook.md


## 1. Download Celebrity Dataset
Go to the data instructions file in the data folder. It explains how to download the celebrity dataset and where to get it.
After you download the dataset, upload the entire folder to your Google Drive.

## 2. Collect Group Member Images
Gather 25 pictures of each group member.
Upload these pictures to a separate folder in your Google Drive.
Make sure the photos show the face clearly and are not blurry.

## 3. Mount Google Drive in Google Colab
Open Google Colab.
Run the code provided in the scripts folder to mount your Google Drive.
You should be able to see your celebrity dataset and your group folders from Colab after this step.

## 4. Resize the Group Images
Use the script in the scripts folder to resize all group member images to the correct dimensions.
This makes them consistent with the celebrity images and prepares them for modeling.

## 5. Clean the celebrity dataset
Run the celebrity cleaning script in the scripts folder.
This will remove blurry images, filter out unreadable files, and prepare the dataset for EDA and modeling. 

## 6. Conduct EDA
Use the EDA code in the scripts folder to explore the dataset.

## 7. Randomly select 500 celebrity images 
After cleaning, randomly select 500 images from the celebrity dataset.
This is done to help with balance and to make the dataset easier to work with.

## 8. Train the CNN model
Use the training script from the scripts folder.
This script will 

- combine the group data and celebrity data
- create an 80 percent training and 20 percent testing split
- build a CNN model
- train the model on your dataset

Run all cells in order.

## 9. Show Outputs and Evaluation Metrics
At the end of training, display the model accuracy, confusion matrix, and sample predictions from the test set.


