# MSDS-DTSA5511-Final_Project

## Project Description and Objective

I have always been fascinated by bees. I find it amazing how they navigate so skillfully between flowers as well as how they can find their way in any condition and in unfamiliar areas. I also admire how they work cooperatively and so well-organized to the benefit of their own colony. It is also a well-known fact that without bees, there would be no human civilization since they are responsible for the pollination of the food that all creatures consume.

On the other hand, I am terrified of wasps, especially yellow jackets. I know they can be almost as important as bees in the pollination role but I have been stung by wasps multiple times in my life and I know how painful it can be! Those experiences unfortunately caused me to have a kind of aversion to them.

Given the above, I thought it would be fun to create a deep learning project to correctly classify images of bees and wasps. To make it more interesting, I will also add images of other insects and even non-insects and try to classify them correctly as well.

Therefore, the objective of this project involves the development of a deep learning CNN model for a multi-class image classification task. The objective is to accurately classify images of bees, wasps, insects, and other non-insects based on their visual features.

The dataset used in this project includes 11,414 labeled images of bees, wasps, insects, and other non-insects. The data has been split into training and validation sets, which have been used to test various models and hyperparameter optimizations. The objective is to develop a deep learning model that can perform as well as possible to a pre-trained ResNet model.

In terms of evaluation metrics, the ROC-AUC will be the primary metric used to assess the performance of the model but I will also compute accuracy, mse and F1-score for all models tested. I will also plot the confusion matrix and ROC-AUC curve for the final model as well.

## Data Description

The dataset used in this project contains 11,414 labeled close-up photos of bees, wasps, other insects, and other non-insects, obtained from Kaggle. The images have varying resolutions and are composed of 3 color channels. Each image in the dataset is labeled with a filename, label, and other attributes that are not relevant to this project.

To ensure the accuracy of the dataset, it has been hand-curated by an expert biologist, Callum Robertson. This ensures that the dataset is of high quality and is well-suited to the needs of the project.

The images in the dataset have been selected to represent a diverse range of species and visual features. This enables the model to learn to recognize a wide range of features that can be used to classify different types of insects accurately. By including images of bees, wasps, and other insects, as well as non-insects, the dataset is representative of the real world and can be used to train a model that can accurately classify images of various types of creatures.

The dataset used in this project has been expertly curated to ensure its quality and suitability for the task at hand. While most of the images are of high quality, some intentionally lower-quality images have been included in the dataset to make the project more challenging.

These lower-quality images may have lower pixel resolution or other image quality issues. However, including them in the dataset ensures that the deep learning model is robust and can accurately classify images of bees, wasps, insects, and other non-insects even in challenging conditions.

* Link to the original dataset on Kaggle: https://www.kaggle.com/datasets/jerzydziewierz/bee-vs-wasp
* Callum Robertson's profile https://www.linkedin.com/in/callum-robertson-358014109/

## Files Included

* DTSA5511-Final_Project.ipynb - Jupyter Notebook
* DTSA5511-Final_Project.pdf - pdf version of the Jupyer Notebook
* DTSA5511-Final_Project-Video - video presentation of the results
