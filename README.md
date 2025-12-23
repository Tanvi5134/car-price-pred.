Car Price Prediction using Machine Learning

Project Overview
This project predicts the selling price of a car based on various features such as year of manufacture, present price, kilometers driven, fuel type, seller type, transmission, and ownership.

It uses Machine Learning regression techniques to learn patterns from historical car data and make price predictions for new cars.

Problem Statement
Buying or selling a car requires knowing its fair market value.  
This project helps estimate a car’s price based on its specifications using a trained ML model.

Dataset
- Source: Kaggle
- File: `cardekho.csv`
- Number of records: varies by dataset

Key Features:
- Year  
- Present Price  
- Kms Driven  
- Fuel Type  
- Seller Type  
- Transmission  
- Owner  

Target Variable:
- **Selling_Price**
- 
Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Google Colab / Jupyter Notebook  

Methodology
1. Loaded and explored the dataset  
2. Removed irrelevant columns  
3. Encoded categorical variables using One-Hot Encoding  
4. Split data into training and testing sets  
5. Trained a **Linear Regression model**  
6. Evaluated model performance using MAE and R² score  
7. Predicted price for new car data  

Model Used
- Linear Regression

Evaluation Metrics:
- Mean Absolute Error (MAE)  
- R² Score  

Sample Prediction
text
Input:
Year: 2018  
Present Price: 7.5  
Kms Driven: 30000  
Fuel Type: Petrol  
Transmission: Manual  

Predicted Selling Price: ₹ X.XX Lakhs
