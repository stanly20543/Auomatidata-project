## **Automatidata Project**

Automatidata is consulting for the New York City Taxi and Limousine Commission (TLC).<br>
New York City TLC is an agency responsible for licensing and regulating New York City's taxi cabs and for-hire vehicles. <br>

This project is designed to help Automatidata and TLC develop a regression model that helps estimate taxi fares before the ride.<br>


### **Part1: Clean and investigate data**

 -**Target**:<br> 
 To get clear insights, TLC's data must be analyzed, key variables identified, and the dataset ensured it is ready for analysis.<br>

 -**Conclusion**: <br>
 After looking at the dataset, there are two variables that are most likely to help build a predictive model for taxi ride fares:
 `total_amount` and `trip_distance` because those variables show the cost of taking a taxi<br>

### **Part2: Explore and analyze data**

-**Target**:<br>
 Exploratory data analysis and data visualization<br>

-**Conclusion**:<br>
As a result of the conducted exploratory data analysis, considering `trip_distance` and `total_amount` as key variables to depict a taxi cab ride.<br>

### **Part3: Statistic analysis**

-**Target**:<br>
 To analyze the relationship between fare amount and payment type with A/B test.<br>
 
-**Conclusion**:<br>
There is a statistically significant difference in the average total fare between customers who use credit cards and customers who use cash. Customers who used credit cards showed a higher total amount compared to cash.<br>


### **Part4: Build linear regression model**

-**Target**:<br>
 To build a regression model for ride fares based on a variety of variables.<br>

-**Conclusion**:<br>
 From multiple linear regression model to calculate the amount fare of trips : fare increased $1.982 for every 1 mile traveled and increased $0.323 for every minutes trip rides.


### **Part5: Build tree-base model**

-**Target**:<br>
 to identify which variables or factors influence the amount of gratuity a rider gives a driver.<br>
 Suggest a generous tipper: those who tipps >= 20% 

-**Conclusion**:<br>
 From the model, `VendorID`, `predicted_fare`, `mean_duration`, and `mean_distance` are the most important features.<br>
 `VendorID` is the most predictive feature. It indicate that one of the two vendors tends to attract more generous customers. It need to perform statistical tests on the behavior of different vendors to examine.
