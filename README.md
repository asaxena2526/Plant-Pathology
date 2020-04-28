# Plant-Pathology

Image classification task using computer-vision based models.

##  Problem Statement

Misdiagnosis of the many diseases impacting agricultural crops can lead to misuse of chemicals leading to the emergence of resistant pathogen strains, increased input costs, and more outbreaks with significant economic loss and environmental impacts. Current disease diagnosis based on human scouting is time-consuming and expensive, and although computer-vision based models have the promise to increase efficiency, the great variance in symptoms due to age of infected tissues, genetic variations, and light conditions within trees decreases the accuracy of detection.

##  Objective

Objectives are to train a model using images of training dataset to 
1) Accurately classify a given image into different diseased category or a healthy leaf.
2) Accurately distinguish between many diseases, sometimes more than one on a single leaf.

## Data Description

Data resource : https://www.kaggle.com/c/plant-pathology-2020-fgvc7/data

├── data<br/>
│   ├── images<br/>
│   ├── sample_submission.csv<br/>
│   ├── test.csv<br/>
│   └── train.csv

### images
A folder containing the train and test images, in jpg format.

### train.csv

* image_id: the foreign key for the parquet files
* multiple_diseases: one of the target labels
* healthy: one of the target labels
* rust: one of the target labels
* scab: one of the target labels

### test.csv

* image_id: the foreign key for the parquet files

### sample_submission.csv

* image_id: the foreign key for the parquet files
* multiple_diseases: one of the target labels
* healthy: one of the target labels
* rust: one of the target labels
* scab: one of the target labels






