### **Practical Application 2 for Certificate in machine learning.**

# **Objective**

### The objective of this assignment was to analyze a used car dataset from Kaggle and identify the factors that influence the price of a car, and then explain these findings to used car dealers.

**Process: From Raw Data to Actionable Insights**

Our journey began with a comprehensive exploration of a massive used car dataset from Kaggle, employing a rigorous process to ensure accuracy and relevance:

1. **Data Acquisition:** We started by gathering the complete dataset, providing a broad view of the used car market.  
2. **Data Profiling:** We carefully examined the data's characteristics, understanding its structure, variables, and potential biases.  
3. **Exploratory Data Analysis (EDA):** We delved deep into the data, uncovering hidden patterns and relationships through visualizations and statistical analysis.  
4. **Data Refinement:** To ensure the reliability of our analysis, we implemented a series of targeted data cleaning steps:  
   * **Age Filtering:** We focused on vehicles manufactured from 1990 onwards, ensuring a relevant and statistically significant sample.  
   * **Anomaly Removal:** We eliminated entries with illogical values, such as zero prices or odometer readings, and incomplete records.  
   * **Variable Reduction:** We removed non-essential identifiers (VIN, ID) and location-specific variables (region) that did not contribute to price prediction.  
   * **Feature Significance Assessment:** We evaluated the impact of factors like state, paint color, manufacturer, and transmission, discarding those with negligible influence on price.  
   * **Outlier Management:** We applied additional filtering to price and odometer readings, removing extreme outliers that could skew our models.  
5. **Model Development:** We constructed and tested multiple regression models, utilizing both the full feature set and refined subsets based on feature correlation analysis. This allowed us to compare model performance and identify the most influential factors.  
6. **Model Evaluation:** We rigorously assessed the performance of each model, focusing on key metrics to determine their accuracy and predictive power. We acknowledged the computational challenges posed by high dimensionality and complex algorithms, particularly in parameter optimization.

**Key Findings: The Price Drivers Revealed**

Our analysis of over 300,000 used car sales unveiled the following critical factors that significantly influence used car prices:

* **Odometer Reading (Mileage):** This is the most dominant factor. Higher mileage directly translates to lower prices, reflecting the vehicle's wear and tear.  
* **Model Year:** Newer vehicles command higher prices, with age being a primary determinant of value. While classic cars can be exceptions, this is the general rule.  
* **Fuel Type:** Diesel vehicles consistently hold higher resale values compared to gasoline or other fuel types, likely due to their perceived durability and fuel efficiency.  
* **Vehicle Type (Body Style):** Sedans tend to retain their value better than other body styles, indicating consistent demand and desirability.  
* **Engine Cylinders:** Vehicles with a higher number of cylinders generally fetch higher prices, reflecting their increased power and performance.

**Additional Insights:**

* **Drive Type:** Front-wheel drive vehicles tend to maintain their value slightly better than four-wheel drive vehicles, suggesting a preference for fuel efficiency and everyday practicality.  
* **Specific Model:** While the model does play a role, its impact is less pronounced than the other factors mentioned above. The overall condition, mileage, and age are more significant drivers of price.

**Impact for Used Car Dealers:**

These findings provide used car dealers with a powerful framework for pricing and inventory management. By focusing on the key factors identified, dealers can:

* Accurately assess the value of used vehicles.  
* Make informed purchasing decisions.  
* Optimize pricing strategies to maximize profitability.  
* Clearly explain to customers how specific features impact the vehicle's value.  
* Focus on vehicles that tend to hold their value better.

By leveraging these data-driven insights, used car dealers can gain a competitive edge in the market and achieve greater success

