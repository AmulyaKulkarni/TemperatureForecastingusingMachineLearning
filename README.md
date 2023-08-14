# TemperatureForecastingusingMachineLearning

**Overview**

- This project focuses on developing machine learning models to predict the next-day maximum (Next_Tmax) and minimum (Next_Tmin) air temperatures based on a dataset provided by the Korea Meteorological Administration. The project involves data preprocessing, exploratory data analysis (EDA), feature engineering, model selection, hyperparameter tuning, and evaluation.

**Project Description**
- The project aims to predict next-day maximum and minimum air temperatures (Next_Tmax and Next_Tmin) using machine learning techniques. The dataset consists of weather-related features such as temperature, humidity, wind speed, and geographical variables. The models are developed using Gradient Boosting and Random Forest regression algorithms.

**Dataset**
- The dataset used for this project is provided by the Korea Meteorological Administration. It includes various attributes such as station information, date, temperature, humidity, wind speed, cloud cover, and more. The dataset is preprocessed and split into training and testing sets.

**Data Preparation**
- The dataset is loaded into a pandas DataFrame.
- Missing values are handled through imputation or removal.
- Date columns are converted to datetime format, and relevant features like day, month, and year are extracted.
- The dataset is split into input features and target variables (Next_Tmax and Next_Tmin).

**Exploratory Data Analysis (EDA)**
- Data visualization techniques are used to understand the distribution and relationships between variables.
- Correlation analysis helps identify important features affecting temperature predictions.
- Visualizations are created to compare predicted values with actual values.

**Feature Engineering**
- Additional features are derived from existing ones to improve model performance.
- Feature importance analysis guides the selection of relevant features for the models.

**Model Selection**
- Linear Regression, Random Forest, and Gradient Boosting models are selected for predicting Next_Tmax and Next_Tmin.
- Initial models are trained and evaluated on the testing dataset.

**Hyperparameter Tuning**
- RandomizedSearchCV is used to fine-tune the hyperparameters of the Gradient Boosting model.
- Cross-validation is performed to assess the model's generalization performance.
  
**Model Evaluation**
- Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared are used to evaluate model performance.
- Cross-validation scores are analyzed to identify overfitting.
- Predicting with Trained Models
- Trained models are saved using joblib for later use.
- New data can be preprocessed and fed into the trained models to make temperature predictions.
- 
**Getting Started**
- Clone this repository: git clone https://github.com/AmulyaKulkarni/temperature-forecast-project.git
- Install dependencies: pip install -r requirements.txt
- Run the Jupyter Notebook or Python scripts for data preprocessing, EDA, modeling, and evaluation.
- 
**Dependencies**

pandas
numpy
scikit-learn
matplotlib
seaborn
joblib

**Contributing**
If you'd like to contribute to the project, feel free to submit pull requests or open issues.
