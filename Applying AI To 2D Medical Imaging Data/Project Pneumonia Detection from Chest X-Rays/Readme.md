# Pneumonia Detection from Chest X-Rays
## Project Overview
In this project, you will apply the skills that you have acquired in this 2D medical imaging course to analyze data from the NIH Chest X-ray Dataset and train a CNN to classify a given chest x-ray for the presence or absence of pneumonia. This project will culminate in a model that can predict the presence of pneumonia with human radiologist-level accuracy that can be prepared for submission to the FDA for 510(k) clearance as software as a medical device. As part of the submission preparation, you will formally describe your model, the data that it was trained on, and a validation plan that meets FDA criteria.

You will be provided with the medical images with clinical labels for each image that were extracted from their accompanying radiology reports.

The project will include access to a GPU for fast training of deep learning architecture, as well as access to 112,000 chest x-rays with disease labels acquired from 30,000 patients.

## About the Dataset
The dataset provided to you for this project was curated by the NIH specifically to address the problem of a lack of large x-ray datasets with ground truth labels to be used in the creation of disease detection algorithms.

The data is mounted in the Udacity Jupyter GPU workspace provided to you, along with code to load the data. Alternatively, you can download the data from the kaggle website and run it locally. You are STRONGLY recommended to complete the project using the Udacity workspace since the data is huge, and you will need GPU to accelerate the training process.

There are 112,120 X-ray images with disease labels from 30,805 unique patients in this dataset. The disease labels were created using Natural Language Processing (NLP) to mine the associated radiological reports. The labels include 14 common thoracic pathologies:

Atelectasis
Consolidation
Infiltration
Pneumothorax
Edema
Emphysema
Fibrosis
Effusion
Pneumonia
Pleural thickening
Cardiomegaly
Nodule
Mass
Hernia
The biggest limitation of this dataset is that image labels were NLP-extracted so there could be some erroneous labels but the NLP labeling accuracy is estimated to be >90%.

The original radiology reports are not publicly available but you can find more details on the labeling process [here](https://arxiv.org/abs/1705.02315).

## Project Work
This project contains the following work.

1-  Exploratory Data Analysis <br/>
2 - Building and Training The AI Model <br/>
3 - Clinical Workflow Integration <br/>
4 - FDA Preparation and Submission <br/>
