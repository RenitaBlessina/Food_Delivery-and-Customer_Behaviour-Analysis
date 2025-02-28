# Food-Delivery-and-Customer_Behaviour-Analysis
## Introduction

The Food Delivery and Customer Behavior Analysis project aims to understand food delivery and customer behavior patterns to improve sales conversion rates through targeted marketing strategies. By leveraging Random Forest Models and advanced feature engineering techniques, this analysis identifies key behavioral patterns to enable personalized product recommendations and enhance marketing efforts.

## Dataset

- **Name:** Call Center Restaurant Orders Dataset
- **Description:** This dataset contains details of the orders placed by customers and includes information such as the time the customer placed the order, the time the order was placed at the restaurant, the time the driver arrived at the restaurant, delivery time, and more.

## Project Objectives

1. Analyzie food delivery patterns.
2. Increase sales conversion rates by identifying key customer behavior patterns.
3. Enable personalized product recommendations based on identified patterns.
4. Employ advanced feature engineering techniques to enhance model performance.

## Methods

### Data Preprocessing

1. **Data Cleaning**: Handling missing values, duplicates, and inconsistent data entries.
2. **Feature Engineering**: Creating new features to capture customer behavior patterns, such as average order value, frequency of orders, time between orders, and customer segmentation.
3. **Exploratory Data Analysis (EDA)**: Visualizing data distributions, correlations, and identifying significant patterns and trends.

## Possible Sources of Bias

- **Location Bias:** Bias towards or against certain delivery locations based on factors such as safety concerns, familiarity, or perceived tipping habits.
- **Customer Bias:** Prioritization of deliveries to specific customers perceived as more generous with tips.
- **Time-of-Day Bias:** Preferences for working during specific times of the day or week.
- **Weather Bias:** Impact of adverse weather conditions on driver behavior.
- **Operational Bias:** Bias in the allocation of resources and operational decisions, such as prioritizing profitability over service quality.

## Visualization and Analysis

1. **Line Plot:** Time taken by the driver to arrive at the restaurant in minutes for each record.
2. **Histogram:** Distribution of time taken by the driver to arrive at the restaurant.
3. **Kernel Density Estimation:** Smooth estimate of the probability density function for the dataset.

### Analysis Techniques

1. **Random Forest Models**: To predict customer behavior and identify key patterns influencing sales conversion rates.
2. **Model Evaluation**: Using metrics such as accuracy, precision, recall, and F1-score to evaluate model performance.
3. **Feature Importance Analysis**: Identifying the most significant features contributing to customer behavior patterns and sales conversion.

### Tests Performed

1. **Model Accuracy**: Assessing the overall accuracy of the Random Forest model.
2. **Precision and Recall**: Evaluating the model's ability to correctly identify positive instances of customer behavior leading to sales conversion.
3. **F1-Score**: Measuring the balance between precision and recall.
4. **Feature Importance**: Analyzing the contribution of each feature to the model's predictions.

## Results

- 23.09% of the time, drivers arrive 30 minutes late for food or order pickup from a restaurant after the food is ready for pickup.
- **Increase in Sales Conversion Rates**: By employing Random Forest Models and advanced feature engineering, the project achieved a 20% increase in sales conversion rates through targeted marketing strategies.
- **Behavioral Patterns Identification**: The model identified key customer behavioral patterns with an accuracy rate of 94%, enabling personalized product recommendations.
- **Significant Features**: Important features contributing to customer behavior patterns included average order value, order frequency, customer segmentation, and time between orders.

## Conclusions

- This project provides valuable insights into the dynamics of meal pickups in the food delivery industry and also the customer behaviour.
- By understanding the challenges and opportunities in this phase of the delivery process, food delivery platforms and restaurants can make informed decisions and implement effective strategies to enhance          customer satisfaction.      
- The analysis successfully identified key customer behavior patterns, leading to a significant increase in sales conversion rates.
- Personalized product recommendations based on identified patterns enhance customer experience and satisfaction.
- Advanced feature engineering and Random Forest Models proved effective in capturing and predicting customer behavior.

## Future Research

1. **Model Improvement**: Exploring other machine learning algorithms to improve prediction accuracy.
2. **Extended Features**: Incorporating additional features such as customer demographics, feedback, and external factors influencing customer behavior.
3. **Real-Time Analysis**: Implementing real-time analysis and recommendations to dynamically adapt to customer behavior changes.
4. **Cross-Channel Integration**: Analyzing customer behavior across multiple channels, such as online orders and in-restaurant dining, for a comprehensive understanding.

## Running the Jupyter Notebook

To run the Jupyter Notebook for this project, follow these steps:

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/RenitaBlessina/Food_Delivery-and-Customer_Behaviour-Analysis
   cd Food_Delivery-and-Customer_Behaviour-Analysis
   ```

2. **Create a Virtual Environment:**

   ```bash
   python -m venv env
   ```

3. **Activate the Virtual Environment:**

   - On Windows:

     ```bash
     .\env\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source env/bin/activate
     ```

4. **Launch Jupyter Notebook:**

   ```bash
   jupyter notebook
   ```

5. **Open and Run the Notebook:**

   Open the `Customer_Behavior_Analysis.ipynb` notebook file and run the cells to execute the analysis.
