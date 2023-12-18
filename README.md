# Demographic Data Analyzer

This is the boilerplate for the Demographic Data Analyzer project. Instructions for building your project can be found at https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/demographic-data-analyzer

# My collaboration in the project:

This Python code utilizes the Pandas library to perform demographic analysis on a dataset extracted from the 1994 census. The dataset includes information about age, work class, education, marital status, occupation, and other demographic attributes.

## Objective
The code answers various questions about the dataset, including:

 - The number of people of each race represented in the dataset.
 - The average age of men.
 - The percentage of people with a Bachelor's degree.
 - The percentage of people with advanced education (Bachelor's, Master's, or Doctorate) earning more than 50K.
 - The percentage of people without advanced education earning more than 50K.
 - The minimum number of hours a person works per week.
 - The percentage of people working the minimum number of hours per week earning more than 50K.
 - The country with the highest percentage of people earning more than 50K.
 - The most popular occupation among those earning more than 50K in India.

## Usage
To use the code, provide the correct path to the CSV file containing census data. Ensure you have the Pandas library installed before running the code.

```python
# Read the dataset from the CSV file
df = pd.read_csv('path/to/file.csv')

# Call the function to calculate and print demographic statistics
calculate_demographic_data()
```
The code provides an overview of demographic statistics from the dataset, answering the above questions and displaying the results in a formatted manner.
