# Predicting Airplane Delays

This repository contains a Jupyter notebook that aims to predict airplane delays using machine learning. The goals of this notebook are to process and create a dataset from downloaded ZIP files, perform exploratory data analysis (EDA), and establish a baseline model that can be improved upon.

## Business Scenario

You work for a travel booking website that wants to improve customer experience by predicting flight delays. The company aims to notify customers in advance if their flight is likely to be delayed due to weather conditions. The dataset provided includes scheduled and actual departure and arrival times reported by certified US air carriers from 2014 to 2018.

## Dataset

The dataset contains scheduled and actual departure and arrival times reported by certified US air carriers that account for at least 1 percent of domestic scheduled passenger revenues. The data are in 60 compressed files, each containing a CSV for the flight details in a month for the five years (from 2014 - 2018). The data can be downloaded from this link: [https://uc...]

## Steps to Run the Code

### 1. Setup

First, ensure that you have the necessary libraries and tools installed. This project requires:

- Python 3.x
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- pathlib2
- zipfile

You can install the required libraries using the following command:

```sh
pip install pandas numpy matplotlib seaborn pathlib2

### 2. Download and Extract Data
Download the ZIP files containing the dataset and place them in a folder named dataset. The notebook includes code to extract CSV files from these ZIP files.

### 3. Run the Notebook
Open the Jupyter notebook onpremises.ipynb and run the cells sequentially. The notebook is divided into the following sections:

Problem formulation and data collection
Data preprocessing and visualization
Model building and evaluation
### 4. Data Preprocessing
The notebook includes code to preprocess the data, including extracting CSV files from ZIP files and loading them into pandas DataFrames.

### 5. Exploratory Data Analysis (EDA)
Perform EDA to understand the data better and visualize important features.

### 6. Model Building
Build a machine learning model to predict flight delays. The notebook includes code to train and evaluate a classification model.

### 7. Evaluation
Evaluate the model using metrics such as confusion matrix, classification report, and AUC score.

### Conclusion
This notebook provides a comprehensive workflow for predicting airplane delays using machine learning. By following the steps outlined above, you can replicate the results and build your own predictive model for flight delays.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

