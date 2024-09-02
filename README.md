# Syntactic Processing Assigment Solution
‘BeHealthy’ has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organise appointments, track past medical records and provide e-prescriptions.

So, companies like ‘BeHealthy’ are providing medical services, prescriptions and online consultations and generating huge data day by day.

A person with a non-medical background cannot understand the various medical terms which is used in the prescription and online consultation. 

The solution to build a custom NER model to get the list of diseases and their treatment from the dataset so that non-medical background person also can find out the treatement for the specific disease.

The solution is divided into the following sections:

1. Workspace setup
2. Data preprocessing
3. Concept identification
4. Define feature for CRF
5. Getting the features
6. Define input and target variables
7. Build the CRF Model
8. Evaluation
9. Identifying Diseases and Treatments using Custom NER

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- This project explores the given dataset to idenify treatments for a disease 
- The project uses data provided in train_sent & test_sent files for the analysis
- With this porject we are trying to indentify key treatments for the diseases 

## Conclusions
- 1 : The treatment for the disease name 'hereditary retinoblastoma' is 'radiotherapy'

## Technologies Used
- Pandas - For Data Manipulation
- Spacy - NLP Library
- Scikit Learn - CRF Suite - To build custom NER Model

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@nikhilmlai] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
