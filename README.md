# Glass_Indentification

![image](https://github.com/ShreyaPatil1199/Glass_Indentification/assets/135635788/65a78bbc-0652-4b2f-8240-5ebfcc17993d)

The dataset contains various features such as refractive index, percentage of different elements like sodium,  magnesium, aluminium, silicon, potassium, calcium, barium, and iron, as well as the type of glass. The objective of the  project is to build a machine-learning model that can effectively identify the type of glass based on these chemical  properties. This classification task is crucial in real-world applications, especially in forensic investigations, where identifying the type of glass found at crime scenes can provide valuable evidence. By employing various classification algorithms and techniques, the project seeks to achieve high accuracy and robustness in predicting the glass type, thereby contributing to the field of material identification and forensic sciences.

![Python 3](https://img.shields.io/badge/Python-3-blue.svg)

## Table of Contents

  - [Objective](#objective)
    
  - [Dataset Description](#Dataset-Description)

  - [Missing Attribute Values](#Missing-Attribute-Values)

  - [Prerequisites](#Prerequisites)

  - [Getting Started](#Getting-Started)

## Objective

  The objective of the Glass Identification project is to develop a robust machine learning model that can accurately classify different types of glass based on their 
  chemical composition, with a particular focus on attributes such as refractive index and the percentages of various chemical elements. This classification model aims to 
  contribute to the field of material identification and forensic sciences by providing a valuable tool for identifying glass samples found in real-world scenarios, 
  including forensic investigations. The project seeks to achieve high classification accuracy and reliability by employing various data analysis and machine learning 
  techniques, ultimately aiding in the precise categorization of glass samples for diverse applications, such as building materials, vehicle components, and more.

## Data Description

  ### Dataset
  The dataset comprises various features and attributes related to different types of glass samples. These attributes include:
    
  **ID number**: A unique numeric identifier for each instance in the dataset, ranging from 1 to 214.
    
  **RI (Refractive Index)**: The refractive index of the glass.
    
  **Na (Sodium)**: The percentage of sodium in the glass, measured in weight per cent in the corresponding oxide.
  
  **Mg (Magnesium)**: The percentage of magnesium in the glass.
  
  **Al (Aluminum)**: The percentage of aluminium in the glass.
  
  **Si (Silicon)**: The percentage of silicon in the glass.
  
  **K (Potassium)**: The percentage of potassium in the glass.
  
  **Ca (Calcium)**: The percentage of calcium in the glass.
  
  **Ba (Barium)**: The percentage of barium in the glass.
  
  **Fe (Iron)**: The percentage of iron in the glass.
  
  **Type of Glass (Class Attribute)**: This is the target variable, representing the type of glass. It has the following categories:
  
      1: Building Windows - Float Processed
      
      2: Building Windows - Non-Float Processed
      
      3: Vehicle Windows - Float Processed
      
      4: Vehicle Windows - Non-Float Processed (Note: None in this database)
      
      5: Containers
      
      6: Tableware
      
      7: Headlamps

## Missing Attribute Values

  The dataset does not contain any missing attribute values, ensuring a clean and complete dataset for analysis and modelling.

## Prerequisites

  Make sure you have the necessary libraries and dependencies installed. You can typically install them using pip or conda. Refer to the requirements.txt file for details.

## Getting Started

  Clone this repository to your local machine.
  Navigate to the project directory.
  Follow the Jupyter notebooks in the notebooks directory for step-by-step instructions on data preprocessing, EDA, model training, and evaluation.

