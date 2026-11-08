# Customer Churn Storyboard – Week 4 EDA

## Project overview
This project explores customer attrition in the telecommunications industry using the IBM Telco Customer Churn sample dataset. It uses Python, pandas, seaborn, and matplotlib to clean the data, calculate churn rates, visualize patterns, and translate findings into business recommendations.

## Business questions
1. What is the overall customer churn rate?
2. How does contract type relate to customer churn?
3. Does payment method show an association with customer churn?

## Tools
- Python
- pandas and NumPy
- seaborn and Matplotlib
- Google Colab / Jupyter Notebook

## Dataset
IBM Telco Customer Churn sample dataset:
https://github.com/IBM/telco-customer-churn-on-icp4d

The notebook downloads the CSV when it is run. An internet connection is required for the dataset download.

## Project workflow
1. Import libraries and download the dataset.
2. Inspect columns, data types, missing values, and duplicates.
3. Clean text fields and convert `TotalCharges` to numeric.
4. Calculate the overall churn baseline.
5. Compare churn rates by contract type.
6. Compare churn rates by payment method.
7. Save charts and summary tables.

## Visualizations
Run the notebook from top to bottom to generate the following chart images:

### Overall customer churn
![Overall customer churn](charts/overall_churn.png)

### Churn rate by contract type
![Churn by contract](charts/contract_churn.png)

### Churn rate by payment method
![Churn by payment method](charts/payment_churn.png)

## Key findings
The notebook calculates the exact churn baseline and the highest-churn contract and payment groups from the downloaded data. Copy the resulting percentages and group names from the executed notebook into this section after running it.

- Overall churn rate: **[Add calculated percentage]**
- Contract group with highest churn: **[Add calculated group and rate]**
- Payment method with highest churn: **[Add calculated group and rate]**

## Business recommendations
- Monitor the overall churn baseline over time.
- Investigate high-churn contract segments and test retention offers.
- Review the customer billing experience for payment groups with higher churn.
- Measure retention initiatives before and after implementation.

## Important interpretation note
The analysis identifies associations in historical data. It does not prove that contract type or payment method causes a customer to churn.

## How to run
1. Open `Customer_Churn_Analysis.ipynb` in Google Colab or Jupyter.
2. Run all cells from top to bottom.
3. Confirm that the three chart images appear in the `charts/` folder.
4. Replace the placeholders in this README with the actual outputs from your run.
5. Upload the notebook, README, chart images, and summary CSV files to a **public** GitHub repository.

## Author
Data Science Internship – Week 4 Project
