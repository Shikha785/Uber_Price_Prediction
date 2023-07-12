# Uber Price Prediction Project

This project focuses on predicting Uber prices using two datasets: 'weather' and 'cab_rides'. The goal is to develop a model that can accurately estimate the price of an Uber ride based on various weather conditions.

## Datasets

The project utilizes the following datasets:

1. **weather Dataset**: This dataset contains weather-related information such as temperature, location, clouds, pressure, rain, time_stamp, humidity, and wind. The weather data helps to capture the atmospheric conditions at different times and locations.

2. **cab_rides Dataset**: This dataset includes information about Uber rides, such as the pickup and drop-off locations, date, time, distance, and fare. It provides the historical data of Uber rides, which will be used for training and evaluating the prediction model.

## Approach

The project follows the following approach to predict Uber prices:

1. Data Collection: The 'weather' dataset and the 'can_rides' dataset are obtained from dropbox.{https://www.dropbox.com/s/brixkogrmhan6ed/cab_rides.csv ,https://www.dropbox.com/s/ncqb2ctkg7da11k/weather.csv.csv)

2. Data Preprocessing: The datasets are cleaned and processed to handle missing values, outliers, and inconsistencies. Features from both datasets are appropriately selected and transformed for further analysis.

3. Feature Engineering: Additional relevant features are created or derived from the existing datasets to enhance the predictive power of the model. For example, combining weather and time-related features to capture seasonal patterns.

4. Data Integration: The processed 'weather' dataset and 'cab_rides' dataset are merged based on common attributes such as location and timestamp.

5. Model Development: Regression models, such as linear regression is implemented to train a predictive model using the merged dataset. The model learns the relationship between weather conditions and Uber prices.

6. Model Evaluation: The trained model is evaluated using appropriate evaluation metrics such as mean squared error (MSE), root mean squared error (RMSE), or R-squared. The model performance is analyzed to assess its accuracy and generalization capabilities.

## Requirements

To run this project, ensure you have the following dependencies:

- Python 3.x
- Pandas
- NumPy
- Seaborn
- Scikit-learn
- Matplotlib
- Jupyter Notebook or any other compatible IDE

## Usage

1. Clone or download the project repository from GitHub.

2. Install the required dependencies mentioned above using the package manager of your choice (pip, conda, etc.).

3. Open the project in a Jupyter Notebook or your preferred IDE.

4. Run the notebook cells sequentially to execute the data preprocessing, feature engineering, model development, and evaluation steps.

5. Once the model is trained and evaluated, you can use it to make predictions on new instances by providing the corresponding weather data.

## Conclusion

This project demonstrates the use of weather data in predicting Uber prices. By leveraging historical 'Weather' and 'Uber Rides' datasets, we develop a predictive model that estimates Uber prices based on weather conditions. The model can help both Uber drivers and passengers in planning their rides and estimating fares accordingly.


## Contact
For any questions, suggestions, or issues regarding the project, feel free to contact shikha015kumari@gmail.com

Happy predicting and riding with Uber!
