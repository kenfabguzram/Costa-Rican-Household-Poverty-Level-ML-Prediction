# Costa-Rican-Household-Poverty-Level-ML-Prediction

This repository focuses on predicting poverty levels of Costa Rican households using machine learning techniques. It addresses a classification problem where the objective is to accurately categorize households into predefined poverty levels (1-5) based on socioeconomic and housing-related features.

## Key Features

- **Objective**: Predict poverty levels using household data.
- **Data Handling**: Includes data preprocessing, cleaning, and transformation pipelines.
- **Feature Engineering**: Implements methods to select and engineer variables to optimize model performance.
- **Modeling**: Explores several machine learning models, each tuned for optimal performance.
- **Evaluation**: Uses metrics like F1-Score, Precision, Recall, and AUC-ROC to assess models.
- **Interpretability**: Provides insights into the key factors driving predictions.

## Machine Learning Models

### 1. **K-Nearest Neighbors (KNN)**  
   - **Description**: A distance-based algorithm that classifies data points based on the labels of their nearest neighbors in the feature space.  
   - **Parameters**: Includes hyperparameters such as the number of neighbors (`n_neighbors`) and the distance metric (e.g., Euclidean).  

### 2. **Random Forest**  
   - **Description**: An ensemble learning method that builds multiple decision trees during training and outputs the class mode of the individual trees.  
   - **Advantages**: Handles high-dimensional data and prevents overfitting with techniques like bagging.  
   - **Parameters**: Includes the number of trees (`n_estimators`), depth of trees (`max_depth`), and split criteria (`criterion`).  

### 3. **XGBoost (Extreme Gradient Boosting)**  
   - **Description**: A powerful gradient boosting algorithm optimized for speed and performance. It builds trees iteratively, improving errors from previous models.  
   - **Advantages**: Regularization, parallel processing, and high accuracy for structured data.  
   - **Parameters**: Includes learning rate (`eta`), maximum depth of trees (`max_depth`), and number of boosting rounds (`n_estimators`).  

Each model was tested with tuned hyperparameters to identify the best-performing approach for this classification task.

## Tools and Libraries Used

- **Python**: Core programming language for analysis and modeling.
- **Scikit-learn**: For building and evaluating machine learning models.
- **XGBoost**: To implement advanced gradient boosting models.
- **Pandas & NumPy**: For data manipulation and computations.
- **Matplotlib & Seaborn**: For visualization.
- **Jupyter Notebook**: For interactive development.

## Project Highlights

- Tackles a real-world socioeconomic challenge using machine learning.
- Employs a systematic approach following the CRISP-DM methodology.
- Demonstrates best practices for feature engineering and hyperparameter tuning.

## How to Use

1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/Costa-Rican-Household-Poverty-Level-ML-Prediction.git
2. Run the pip code section to satisfy the requirements on your envirnoment.
