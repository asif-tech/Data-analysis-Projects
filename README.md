# Customer Churn Analysis using RFM

## Description
This project focuses on analyzing customer churn using the RFM (Recency, Frequency, Monetary) analysis technique. By cleaning and preparing customer data, we aim to identify key patterns and factors that influence customer retention and churn, providing actionable insights for business decisions. The analysis is performed using Python with libraries such as Pandas and NumPy.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation
To run this project locally, follow these steps:

```bash
# Clone the repository
git clone https://github.com/asif-tech/Data-analysis-Projects.git

# Change into the project directory
cd Data-analysis-Projects/Customer-Churn

# (Optional) Create and activate a virtual environment
python -m venv venv
source venv/bin/activate # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt


Usage
To use this project, run the Jupyter Notebooks provided:
Open the following notebooks to explore the analysis and results:

1. Customer_Segmentation_Customer_Adress_Data_DQA_and_Data_Cleaning.ipynb
2. CustomerDemographic_DQA_and_Data_Cleaned.ipynb
3. NewCustomer_DQA_and_data_Cleaned.ipynb
4. TransactionData_DQA_and_Cleaned.ipynb
5. RFM_Analysis.ipynb

#Features
Data Preprocessing: Clean and prepare customer data from multiple CSV files.
Data Quality Assessment (DQA): Perform data quality checks on four different data sources.
RFM Analysis: Calculate Recency, Frequency, and Monetary values for each customer.
Customer Segmentation: Segment customers based on their RFM scores.
Visualization: Generate charts and graphs to visualize customer segments and insights.

#Project Structure
The project is organized as follows:
Customer-Churn/
│
├── Customer_Segmentation_Customer_Adress_Data_DQA_and_Data_Cleaning.ipynb
├── CustomerDemographic_DQA_and_Data_Cleaned.ipynb
├── NewCustomer_DQA_and_data_Cleaned.ipynb
├── TransactionData_DQA_and_Cleaned.ipynb
├── RFM_Analysis.ipynb
├── data/
│   ├── new_customer_list.csv
│   ├── old_customer_list.csv
│   ├── transaction_list.csv
│   └── merged_transaction_customer.csv
├── requirements.txt
└── README.md

data/: Contains the CSV files used for the analysis.
.ipynb files: Jupyter Notebooks for data quality assessment, data cleaning, and RFM analysis.

#Contributing
Contributions are welcome! To contribute to this project, follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -m 'Add new feature').
Push to the branch (git push origin feature-branch).
Open a Pull Request.

#Contact
For questions or support, please contact:

Email: asifnawaz.an79@gmail.com
GitHub: asif-tech
