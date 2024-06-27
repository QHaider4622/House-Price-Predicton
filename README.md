# House Pricing Analysis and Prediction

This project focuses on analyzing house pricing data and building machine learning models to predict house prices. The dataset used in this project is from [Kaggle](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset/data).

## Dataset

The dataset contains various features of houses and their corresponding prices. You can find more details about the dataset [here](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset/data).

## Project Structure

1. **Data Exploration and Preprocessing**
    - Initial data inspection
    - Handling missing values
    - Feature engineering
    - Data visualization

2. **Model Building**
    - Splitting the data into training and testing sets
    - Model selection and training
    - Hyperparameter tuning
    - Model evaluation

3. **Results and Visualizations**
    - Performance comparison of different models
    
## Data Exploration and Preprocessing

### Initial Data Inspection

Here, we load the dataset and inspect its structure, check for null values,dupliactes, and understand the data types of different features.

### Handling Missing Values

We apply techniques such as imputation or removal of rows/columns with missing values.

### Feature Engineering

We create new features that could help improve the model performance, such as polynomial features or interaction terms.

### Data Visualization

We visualize the data to understand the distribution of features and their relationship with the target variable (house prices).

#### House Price Distribution and Spread
![House_Price_Visuilizations](https://github.com/QHaider4622/House-Price-Predicton/assets/79516393/de2ac86a-add4-4021-a9b7-9f45d0ddc90a)


#### Correlation Heatmap of Numerical Features
![Heatmap](https://github.com/QHaider4622/House-Price-Predicton/assets/79516393/534a5225-f95d-49f4-a42f-2b1db55fc6d2)

## Model Building

### Splitting the Data

The dataset is split into training and testing sets using a 80-20 split.

### Models Used

We experimented with the following models:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Gradient Boosting Regressor**
- **Support Vector Machine Regressor**

### Hyperparameter Tuning

We used GridSearchCV to tune the hyperparameters of the models.

### Model Evaluation

The models were evaluated using metrics such as R2 Score, Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE).

## Results 

### Performance Comparison
![Evalution-Martrices](https://github.com/QHaider4622/House-Price-Predicton/assets/79516393/9d455201-e722-42f8-b1e4-0ab5b04cf883)

### Best Performing Model

The best performing model was **Linear Regression** with an R2 Score of **0.649** and a Mean Absolute Error of **9.796797e+05**.


## References
- [Kaggle Dataset](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset/data)

