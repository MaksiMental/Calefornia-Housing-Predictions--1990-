# Predicting District Median Housing Price in California (1990)

## Problem Framing

The goal of this project is to predict the median housing price for districts in California using the California Housing Prices dataset from 1990. The dataset contains various features such as population, median income, housing median age, and more for each district. Our task is to build a machine learning model that can accurately predict the median housing price based on these features.

### Dataset

The California Housing Prices dataset from 1990 consists of various attributes for each district, including:

1. longitude: A measure of how far west a house is; a higher value is farther west

2. latitude: A measure of how far north a house is; a higher value is farther north

3. housingMedianAge: Median age of a house within a block; a lower number is a newer building

4. totalRooms: Total number of rooms within a block

5. totalBedrooms: Total number of bedrooms within a block

6. population: Total number of people residing within a block

7. households: Total number of households, a group of people residing within a home unit, for a block

8. medianIncome: Median income for households within a block of houses (measured in tens of thousands of US Dollars e.g. 3 => 30.000$)

9. medianHouseValue: Median house value for households within a block (measured in US Dollars)

10. oceanProximity: Location of the house w.r.t ocean/sea

The target variable is the median housing price for each district.


### Approach

We will follow these general steps to address the problem:

1. Data Exploration and Preprocessing: Explore the dataset to understand its structure and identify any missing values or outliers. Preprocess the data as necessary, including handling missing values, scaling numerical features, encoding categorical variables, etc.

2. Feature Engineering: Extract meaningful features from the existing data or create new features that may improve the model's performance.

3. Model Selection and Training: Select appropriate machine learning algorithms for regression tasks and train them on the preprocessed dataset.

4. Model Evaluation: Evaluate the performance of the trained models using appropriate evaluation metrics such as mean squared error (MSE), root mean squared error (RMSE), mean absolute error (MAE), etc.

5. Fine-tuning: Fine-tune the hyperparameters of the selected models to improve their performance further.

6. Model Deployment: Deploy the final trained model for making predictions on new data.

### Contributing

Contributions to this project are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

