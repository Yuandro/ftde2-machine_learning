# Fast Track Data Engineer 2 - Machine Learning Homework

## Objective :
- Create a machine learning model to predict whether a potential customer will decide to purchase a car insurance policy offered by a salesperson.
- Use an algorithm other than KNN to analyze the available data.
- Save the results of the model's analysis as a pickle file at the end of the process.

## Tools :
- Python: For coding the machine learning model.
- Libraries: pandas, scikit-learn and pickle.
- Google Colab: For working interactively.

## Data set information (Prediction Insurance.csv)
- id: Unique identification for each entry or customer in the dataset.
- Gender: Customer's gender (e.g., 'Male' or 'Female').
- Age: Customer's age in years.
- Driving_License: Status of driving license ownership (0 for not owning, 1 for owning).
- Region_Code: Code representing the customer's residential region, typically a number indicating a geographic area.
- Previously_Insured: Status indicating whether the customer already has insurance (0 for not having, 1 for having).
- Vehicle_Age: Age of the customer's vehicle (e.g., 'New', '1-2 Year', 'More than 2 Years').
- Vehicle_Damage: Indication of whether the customer's vehicle has been previously damaged (e.g., 'Yes' or 'No').
- Annual_Premium: Annual premium the customer must pay for insurance (in relevant currency).
- Policy_Sales_Channel: Numeric code indicating the sales channel for the policy, such as agent, online, etc.
- Vintage: Number of days since the customer started engaging with the insurance company.
- Response: Customer's response to the insurance offer (0 for uninterested, 1 for interested).

## Step by step :
- Load the dataset: Use pandas to read the CSV file.
- Data Preprocessing: Handle Missing Values and Encode Categorical Columns
- Split the Dataset: 80% for training and 20% for testing
- Train the Model: using Logistic Regression
- Check for Overfitting
- Save the Model