# House-price-prediction

Steps Followed
The following steps were implemented during the project:
1. Data Preprocessing
- Loaded the dataset and checked for missing values.
- Imputed missing values in numerical and categorical columns.
- Encoded categorical variables using one-hot encoding.
- Scaled numerical features to standardize the data.
2. Exploratory Data Analysis
- Analyzed relationships between features and property prices.
- Conducted location-based analysis to identify trends in different zones.
- Visualized data distributions and outliers to refine feature selection.
3. Model Development
- Used Random Forest Regressor as the primary model.
- Split the dataset into training (80%) and testing (20%) subsets.
- Built a pipeline to preprocess data and train the model.
4. Model Evaluation
- Evaluated the model using metrics such as R² score and RMSE.
- Achieved high accuracy with R² > 90% on the test dataset.
- Identified areas for improvement, such as hyperparameter tuning
