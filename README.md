# Pet Adoption Status Prediction

This project aims to predict the adoption status of pets using various machine learning models, including LSTM, KNN, K-Means Clustering, and XGBoost. The project performs Exploratory Data Analysis (EDA), preprocessing, training, evaluation, and prediction using the provided dataset.

**Dataset**: https://www.kaggle.com/datasets/rabieelkharoua/predict-pet-adoption-status-dataset

## Table of Contents

- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Models Implemented](#models-implemented)
- [Results](#results)

## Dataset

The dataset contains information related to pets and their adoption status. The features include various attributes such as pet age, type, and other factors that might influence adoption.

## Project Structure

├── pet_adoption_data.csv        # Dataset file

├── pet_adoption_prediction.ipynb # Jupyter notebook with code implementation

├── README.md                    # Project README file

└── results                      # Directory to store model results


## Models Implemented

1. **LSTM (Long Short-Term Memory)**:

-  Used for sequential data analysis.
-  Model is trained and evaluated on the adoption status data.
  
2. **KNN (K-Nearest Neighbors)**:

- A simple, instance-based learning model.
- Predicts adoption status based on the closest neighbors.
  
3. **K-Means Clustering**:

- An unsupervised learning algorithm.
- Groups data into clusters to analyze patterns.
  
4. **XGBoost**:

- An advanced gradient boosting model.
- Used for high performance and accuracy in prediction tasks.

## Results

**LSTM Model**: Achieved an accuracy of 87%. 

**KNN Model**: Achieved an accuracy of 76%.

**K-Means Clustering**: Achieved a silhouette score of 97%.
 
**XGBoost Model**: Achieved an accuracy of 95%.

## License

This project is open-source and available under the MIT License.
