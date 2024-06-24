<h1><b>What Drives the Price of a Car?</b></h1>

<h3>Overview:</h3>
<p>
In this application, we will explore a dataset from kaggle. The original dataset contained information on 3 million used cars but the provided dataset contains information on 426K cars to ensure speed of processing. The goal is to understand what factors make a car more or less expensive. As a result of analysis, we  should provide clear recommendations to our client -- a used car dealership -- as to what consumers value in a used car. We used standard CRISP-DM framework - a standard industry process to work through a data problem.
</p>

<h3>Repo Structure</h3>
The What_Drives_the_Price_of_a_Car.ipynb file contains python code related to data analysis, visualization.
The data folder has vehicles.csv file that contains sample data used in this application.
The carpriceregressionereport.docx file contains brief report about this application.

<h3>Business Understanding</h3>
<p>
In the "What Drives the Price of a Car" project, we will be analyzing a subset of the Vehicle Dataset from Kaggle, which contains around 426K samples of used cars. The main objective of this analysis is to identify the factors that impact car prices. By conducting this analysis, we will provide valuable recommendations to our client, a used car dealership, regarding the features and qualities that consumers value in a used car. This will help the dealership make more informed decisions and improve their understanding of customer preferences.

Throughout the analysis, we will explore various aspects of the dataset, such as the car's manufacturer, model, year, mileage, condition, and other relevant attributes. It is important to keep in mind the specific needs and objectives of the client to ensure that the final recommendations are relevant, practical, and aligned with their goals.

Thank you Kaggle for allowing us to use your dataset https://www.kaggle.com/datasets.
</p>

<h3>Data Understanding: Exploratory Data Analysis (EDA)</h3>

<h3>Data Preparation</h3>
<p>
Drop features & duplicates
Handle Missing Values
Handle Outliers, correct data types
Feature Encoding
Handling inconsistent data (example: price shouldn't be less than 1)
Visualize cleaned Data
</p>

<h3>Modeling</h3>

<h3>Evaluation</h3>
<p>
Interpret the Coefficients and Y-Intercept

Coefficient Value: The value of each coefficient represents the expected change in the target variable for a one-unit change in the corresponding feature, assuming all other features remain constant.
Intercept: The intercept represents the expected value of the target variable when all features are zero.

year, fuel_status,size features have positive coefficients which means, unit increase in these features result in increase of target variance as per features coefficient value.
Other features have negative coefficients which means, unit increase in these features result in decrease of target variance as per features coefficient value. year: 0.025344
Intercept: -40.41. When all features are zero, the expected value of the target variable (disease progression) is -40.41 units
</p>

<h3>Deployment</h3>
<p>
1. Save the trained model to a file for future use.
2. Load the saved model and use it to make predictions on new data.
</p>

<h3>Conclusion</h3>
<p>
*  Year & Transmission features have strong positive impact on price of a vehicle.
*  Fuel feature has strong negative impact on vehicle price.
*  Maximum available vehicles belong to Gas fuel type category.
*  Odometer has negative impact on vehicle price means vehicle price decreases with odometer value increases
*   There exist vehicles with value 0 and duplicate samples which are outliers for dataset
</p>


