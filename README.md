[CarPriceRegressionReport.docx](https://github.com/user-attachments/files/15950100/CarPriceRegressionReport.docx)
## <h1><b>What Drives the Price of a Car?</b></h1>

## <h3>Overview:</h3>
<p>
In this application, we will explore a dataset from kaggle. The original dataset contained information on 3 million used cars but the provided dataset contains information on 426K cars to ensure speed of processing. The goal is to understand what factors make a car more or less expensive. As a result of analysis, we  should provide clear recommendations to our client -- a used car dealership -- as to what consumers value in a used car. We used standard CRISP-DM framework - a standard industry process to work through a data problem.
</p>

## <h3>Repo Structure</h3>
* The What_Drives_the_Price_of_a_Car.ipynb file contains python code related to data analysis, visualization.
* The data folder has vehicles.csv file that contains sample data used in this application.
* The carpriceregressionereport.docx file contains brief report about this application.

## <h3>Business Understanding</h3>
<p>
In the "What Drives the Price of a Car" project, we will be analyzing a subset of the Vehicle Dataset from Kaggle, which contains around 426K samples of used cars. The main objective of this analysis is to identify the factors that impact car prices. By conducting this analysis, we will provide valuable recommendations to our client, a used car dealership, regarding the features and qualities that consumers value in a used car. This will help the dealership make more informed decisions and improve their understanding of customer preferences.

Throughout the analysis, we will explore various aspects of the dataset, such as the car's manufacturer, model, year, mileage, condition, and other relevant attributes. It is important to keep in mind the specific needs and objectives of the client to ensure that the final recommendations are relevant, practical, and aligned with their goals.

Thank you Kaggle for allowing us to use your dataset https://www.kaggle.com/datasets.
</p>

## Key Highlights
* Year & Transmission features have strong positive impact on price of a vehicle.
* Fuel feature has strong negative impact on vehicle price.
* Odometer has negative impact on vehicle price means vehicle price decreases with odometer value increases
* Year, Condition, Cylinders, Transmission, Size have positive correlation with Price
* There exist group of 2 features that have positive impact on price of a vehicle and they are Cylinders & Condition, Size & Condition, Drive and Cylinders, Size and Cylinders.
* Odometer, Title, Fuel, Drive has negative correlation with Price
* Maximum available vehicles belong to Gas fuel type category.
* There exist vehicles with 0 value price and duplicate samples which are dataset outliers 

## Next steps and Recommendations
* Year and Odometer plays significant role in Vehicle price. Keep vehicles of recent year and less Odometer value vehicles
* Clean title brings higher value to Vehicle.
* Continue to gather new samples for recent years data, evaluate & tune model to improve price prediction and determines the factors that drives Vehicle Price.


### Note
Please consult CarPriceRegressionReport.docx for a thorough analysis of the project.



