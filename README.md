# Exploratory-Data-Analysis
Mastercard X Forage - Job simulation Exercise 

Mastercard x Forage Job Simulation - Exploratory Data Analysis (EDA) Script
This script performs basic exploratory data analysis (EDA) on a sample dataset, likely related to store promotions. It utilizes Python libraries like pandas, seaborn, matplotlib, and numpy.

Functionality:

Reads data from a sample Excel file (GreenTrail Store Data.xlsx).
Creates a Pandas DataFrame from the data.
Provides a glimpse of the first few rows (df.head()) and summary statistics (df.describe())
Converts promotion start and end dates to datetime format for better manipulation.
Generates histograms for all numerical columns in the dataset.
Creates count plots to visualize occurrences of categorical variables like Store Type, Promotion Type, and Location.
Uses seaborn's boxplot function to visualize the distribution of numerical features.
Calculates the covariance and correlation matrices to identify potential relationships between variables.
Note:

This script assumes the data file (GreenTrail Store Data.xlsx) is located in the /content/sample_data directory. Update the path if needed.
The script provides a basic framework for EDA. You can further customize it to explore specific aspects of the data relevant to the job simulation.
Libraries Used:

pandas
seaborn
matplotlib.pyplot
numpy
Getting Started:

Ensure you have Python and the mentioned libraries installed.
Replace the data file path if it differs on your system.
Run the script to perform the EDA.
This script provides a starting point for analyzing the provided dataset. You can extend it to perform more in-depth analysis based on the specific job simulation requirements.
