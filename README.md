# Meteo Data Mining Project

## Overview
This project focuses on leveraging data mining techniques to analyze meteorological (meteo) data. The objective is to extract meaningful insights and patterns from the data that can aid in understanding weather phenomena and predicting future weather conditions.

## Methodology
1. **Data Preprocessing**: The raw meteo data is preprocessed to handle missing values, outliers, and any noise present in the dataset. This step ensures the data is in a suitable format for analysis.

2. **Feature Engineering**: Relevant features are selected or engineered from the raw data to improve the performance of the models. This step involves domain knowledge and understanding of meteorology to identify key variables.

3. **Clustering (K-Means)**: The K-Means clustering algorithm is applied to the preprocessed data to group similar instances together. This helps in identifying distinct weather patterns and clusters within the dataset.

4. **Target Generation**: Based on the clusters obtained from K-Means, a target column is generated, which represents different weather patterns or conditions. This target column serves as the label for the classification models.

5. **Model Training**: Three classification algorithms - Support Vector Machine (SVM), Classification and Regression Trees (CART), and k-Nearest Neighbors (KNN) - are trained on the preprocessed data with the generated target column.

6. **Model Evaluation**: The trained models are evaluated using appropriate metrics such as accuracy, precision, recall, and F1-score. This step helps in assessing the performance of each model and selecting the best-performing one for deployment.

7. **Deployment**: The chosen model is deployed for real-time or batch prediction of weather patterns based on new incoming data.

## Repository Structure
- **DataMeteo12 Complet.csv**: Contains the raw meteo data
- **1 - KMeans for Meteo12**: Jupyter notebooks detailing the data preprocessing, feature engineering, appling K-Means Model.
- **2 - SVM for Meteo12**: Jupyter notebooks for appling SVM Model.
- **3 - KNN for Meteo12**: Jupyter notebooks for appling KNN Model.
- **4 - CART for Meteo12**: Jupyter notebooks for appling CART Model.
- **Final Report**: .

--- 

Feel free to adjust or expand upon any section to better fit your project's specifics!
