# Data Visualization and Analysis with Matplotlib

## Project Description

Data visualization is an essential tool for making sense of complex datasets. In this project, I leverage Matplotlib to analyze and visualize real-world data related to a pharmaceutical company's study on potential cancer treatments. 

## Background

My client, Pymaceuticals, Inc., specializes in anti-cancer medications. I was given access to extensive data from an animal study focused on squamous cell carcinoma (SCC), a common form of skin cancer. The study involved 249 mice with SCC tumors that received various drug regimens over 45 days. The primary goal was to compare the performance of Pymaceuticals' drug of interest, Capomulin, against other treatment regimens.

## Project Tasks

### Data Preparation

- Merged mouse_metadata and study_results DataFrames into a single DataFrame.
- Checked for duplicate mouse IDs with duplicate time points and created a cleaned DataFrame.
- Displayed the number of unique mice IDs in the data.

### Generate Summary Statistics

- Created a DataFrame of summary statistics, including mean, median, variance, standard deviation, and SEM of tumor volume.

### Create Bar Charts and Pie Charts

- Generated bar charts displaying the total number of rows (Mouse ID/Timepoints) for each drug regimen.
- Generated pie charts showing the distribution of female versus male mice in the study.

### Calculate Quartiles, Find Outliers, and Create a Box Plot

- Calculated final tumor volume for select treatment regimens.
- Calculated quartiles, IQR, and identified potential outliers.
- Created a box plot to visualize the distribution of final tumor volume.

### Line Plot and Scatter Plot

- Generated a line plot of tumor volume versus time point for a specific mouse treated with Capomulin.
- Created a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin regimen.

### Correlation and Regression

- Calculated the correlation coefficient and linear regression model between mouse weight and average observed tumor volume for the Capomulin regimen.
- Plotted the linear regression model on the scatter plot.

## Project Results

This project allowed me to explore and analyze complex data, providing valuable insights into cancer treatment outcomes. The visualizations and statistical analysis performed with Matplotlib enhanced my understanding of the dataset and supported data-driven decision-making.

For detailed code and visualizations, please refer to the IPYNB file in the project repository.

## Technologies Used

- Python
- Matplotlib
- Pandas
- Jupyter Notebook
