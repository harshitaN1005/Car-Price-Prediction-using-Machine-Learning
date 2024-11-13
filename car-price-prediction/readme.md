## Abstract

This **Car Price Prediction** project leverages machine learning to estimate the price of a car based on key features such as 
# Car Price Prediction Dataset Features

1. **ID**: A unique identifier for each car entry in the dataset. This feature is typically not used in modeling as it doesn't have predictive power regarding the price.

2. **Price**: The target variable representing the price of the car. This is the value we aim to predict.

3. **Levy**: This could represent an additional tax or fee imposed on the car, such as an environmental levy. Its value might impact the overall price.

4. **Manufacturer**: The brand or company that made the car, such as Toyota, BMW, or Ford. Different manufacturers often have different pricing tiers based on brand reputation and perceived quality.

5. **Model**: The specific model of the car. Models can vary widely within a single manufacturer in terms of features, performance, and price.

6. **Prod. year**: The year the car was manufactured. Generally, newer cars tend to be priced higher, although classic or vintage cars can be exceptions.

7. **Category**: The type or class of the car, such as SUV, sedan, coupe, etc. Different categories of cars have different market values.

8. **Leather interior**: A binary feature indicating whether the car has a leather interior. Cars with leather interiors are often priced higher due to the premium materials used.

9. **Fuel type**: The type of fuel the car uses, such as petrol, diesel, electric, or hybrid. Fuel type can influence both the price and the running cost of the vehicle.

10. **Engine volume**: The volume or capacity of the car's engine, often measured in liters (L). Larger engines generally imply more power and sometimes higher prices, although this can vary with the type of car.

11. **Mileage**: The total distance the car has been driven, usually measured in kilometers or miles. Higher mileage often indicates more wear and tear, potentially reducing the car's price.

12. **Cylinders**: The number of cylinders in the car’s engine. More cylinders usually mean more power, which can increase the car’s price.

13. **Gear box type**: The type of transmission, such as automatic, manual, or semi-automatic. The type of gearbox can affect the car's driving experience and maintenance costs, influencing its price.

14. **Drive wheels**: The type of drive system, such as front-wheel drive (FWD), rear-wheel drive (RWD), or all-wheel drive (AWD). Drive type can influence a car's performance and market value.

15. **Doors**: The number of doors on the car. This can affect the car's functionality and appeal to different buyer segments, impacting its price.

16. **Wheel**: This feature might indicate the type or size of the wheels, or it could specify whether the steering wheel is on the left or right side (in countries with left-hand or right-hand driving). Wheel type and size can affect the car's handling and aesthetics, influencing its price.

17. **Color**: The color of the car. Some colors might be more popular or rarer, which can influence demand and price.

18. **Airbags**: The number of airbags in the car, which is a safety feature. Cars with more airbags are generally considered safer and might be priced higher.

---

By understanding each of these features, we can better prepare the dataset for regression modeling, selecting relevant features and engineering new ones if necessary to improve the prediction accuracy.
 Using a dataset sourced from Kaggle and Scikit-Learn for model training, this project users to input specific car details and receive a price estimate. This predictive tool is designed to assist users in making more informed pricing decisions within the automotive market.
