# 🚗 **Used Car Price Prediction**

This project explores a dataset of 426,880 used cars and aims to identify the key factors influencing used car prices. The goal is to help a used car dealership understand what drives the price of a car, and provide actionable insights for managing their inventory and pricing strategy.

### **Project Overview**

This project follows the CRISP-DM framework, a standard data science process, to frame and solve the business problem. The key steps include:

1. **Business Understanding**: Reframing the task of identifying key drivers for used car prices into a data science problem.
2. **Data Understanding**: Exploring and cleaning the dataset to gain insights into data quality and its usefulness.
3. **Data Preparation**: Preprocessing and preparing the data for modeling by handling missing values, feature engineering, and encoding categorical features.
4. **Modeling**: Training different machine learning models such as Linear Regression, Random Forest, and Decision Tree to predict car prices.
5. **Evaluation**: Assessing model performance and deriving insights for business value.
6. **Deployment**: Presenting the findings and recommendations for use by the client.

### **Dataset**

The dataset contains 426,880 rows and 18 columns, covering various attributes such as:

- `price`: The target variable, which represents the selling price of the car.
- `year`: The manufacturing year of the car.
- `manufacturer`: The brand of the car.
- `condition`, `odometer`, `fuel`, `transmission`, `drive`, `paint_color`: Features describing the condition and technical specifications of the car.
- `region`, `state`: Geographical features indicating where the car was sold.

### **Key Features and Insights**

- **Year**: Newer cars tend to be priced higher.
- **Odometer Reading**: Cars with fewer miles on the odometer are valued more.
- **Condition**: Cars in better condition command higher prices.
- **Manufacturer**: Premium manufacturers tend to have higher resale values.

### **Models Used**

- **Linear Regression**: Captures the overall trends and linear relationships between car features and prices.
- **Random Forest Regressor**: Provides a non-linear approach and identifies important features like car year, odometer, and condition as the most influential in predicting prices.
- **Decision Tree**: Helps understand feature importance and decision-making paths for predicting car prices.

### **Project Structure**

The repository contains the following key files:

- `vehicles.csv`: The dataset used in this analysis.
- `data_preprocessing.ipynb`: Code for cleaning and preparing the dataset.
- `modeling.ipynb`: Code for training the models and analyzing the results.
- `README.md`: Project documentation (this file).

### **Technologies and Libraries**

- Python
- Pandas
- Scikit-Learn
- Matplotlib
- Jupyter Notebook

### **Results**

From the analysis and model training, the **Random Forest Regressor** provided the best results with high accuracy and insight into key price drivers. The most important factors for predicting car prices are:

1. **Car Year**
2. **Odometer**
3. **Condition**
4. **Manufacturer**

These features should be prioritized by the dealership when evaluating the value of used cars.

### **Conclusion and Recommendations**

- **For Dealerships**: When pricing used cars or managing inventory, focus on newer cars with lower mileage, better condition, and premium manufacturers. These cars tend to have higher resale values.
- **Next Steps**: Explore additional features such as demand trends by region or more granular car conditions to further refine price predictions.

### **How to Run**

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/used-car-price-prediction.git
   ```

2. Install required libraries:
   ```
   pip install -r requirements.txt
   ```

3. Run the notebooks for data preparation and model training:
   - `data_preprocessing.ipynb`
   - `modeling.ipynb`

4. Review the findings and model outputs.