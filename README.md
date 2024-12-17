# ESE417 Final Project

## Project Title  
**Wine Quality Prediction using Machine Learning Models**

---

## Table of Contents  
- [Project Title](#project-title)  
- [Introduction](#introduction)  
- [Project Objectives](#project-objectives)  
- [Project Structure](#project-structure)  
- [Methodology](#methodology)  
- [Results](#results)  
- [How to Run the Project](#how-to-run-the-project)  
- [Dependencies](#dependencies)  
- [References](#references)  

---

## Introduction  
 In this project we want to use the ANN, SVM, RF to predict the quality of red wine depended on the 
 different features. 
---

## Project Objectives  
1. Perform data cleaning and preprocessing on wine quality datasets.  
2. Build machine learning models to predict wine quality.  
3. Evaluate the performance of SVM, Random Forest, and ANN models.  
4. Analyze model results and provide insights.
---

## Project Structure  

Below is the folder and file structure for the project:

```plaintext
ESE_417/
│
├── .idea/                        # IDE configuration files
├── .ipynb_checkpoints/           # Jupyter Notebook checkpoints
│
├── Data/                         # Data files and preprocessing scripts
│   ├── Data_Cleaning.ipynb          # Notebook for data cleaning and preprocessing
│   ├── Data_Without_Outlier.csv     # Cleaned dataset without outliers
│   ├── Original_Data.csv            # Original raw dataset
│   ├── winequality-red-4.csv        # Wine quality dataset (red wine)
│   ├── winequality_description-3.txt  # Description of dataset
│
├── ANN.ipynb                     # Jupyter Notebook for ANN model implementation
├── RandomForest.ipynb            # Jupyter Notebook for Random Forest model
├── SVM.ipynb                     # Jupyter Notebook for SVM model
│
├── Description of final project of ESE417 FL2024.pdf  # Project description document
│
└── README.md                     # Project documentation (current file)