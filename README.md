 
 
---------------------------------------------------------------------------------------------------------------------------------------------
Problem Description
The goal of this assignment is to apply basic data mining techniques (primarily summary statistics) on a
publicly available dataset and report the outcome and discovered information.
---------------------------------------------------------------------------------------------------------------------------------------------
Dataset
Title: Life Expectancy (WHO)
Source: Kaggle
URL: https://www.kaggle.com/datasets/kumarajarshi/life-expectancy-who
Description: This dataset, sourced from the World Health Organization (WHO) and the United Nations,
includes information on life expectancy along with various health, economic, and social factors for 193
countries from 2000 to 2015. There are 22 features in the dataset. Detailed description of each feature can
be found at the URL under the Data Card tab at the bottom of the page.
---------------------------------------------------------------------------------------------------------------------------------------------
Tasks
First, download the dataset and make it available to your Google Colab script for easy access by uploading it
to Colab’s session. Then, write Python code using the Pandas library to carry out the following tasks.
Task 1: Loading and Basic Information about the Dataset (2 + 2 + 4 + 2 = 10 points)
a. Load the dataset using Pandas.
b. Display the first 10 rows of the dataset.
c. Show basic information about the dataset size — number of rows and number of columns.
d. List the column names and their data types.
Task 2: Summary Statistics for Numeric Columns (5 + 20 = 25 points )
a. Identify all numeric columns in the dataset and display their names. You may need manual filtering.
b. For each numeric column, compute and display (you must use separate function calls to compute
these):
1. Mean
2. Median
3. Standard deviation
Southern Connecticut State University CSC477
4. Variance
5. Minimum value
6. Maximum value
7. 25th percentile (1st quartile)
8. 75th percentile (3rd quartile)
9. Skewness
10. Kurtosis
Display this information arranged in a Pandas dataframe, where the rows are numeric column
names and column names are these statistical measure names.
Task 3: Interpretation of Statistics for Information Discovery (3 x 5 = 15 points):
Investigate the dataset to discover three distinct information related to three feature variables(e.g., Life
expectancy, GDP, Adult Mortality, or any other three). State the information as comments in your code
block. Each discovered information must be supported by output from corresponding code.
As an example, if the median BMI is significantly different (based on a selected threshold) from the mean
BMI, you could say the BMI data is skewed (on which side it is depends on the relative positions of these
two measures), which would indicate there are more people with high BMIs than low BMIs (or vice-versa).
As another example, if you observed that the average Adult Mortality Rate is significantly higher for
developing countries than developed countries, then that would indicate developing countries should
emphasize more on healthcare. You cannot use either of these two examples in your solution.
Note: You will find code examples for completing many of these tasks inside scripts available on MS
Teams. Please explore Pandas’ online documentation or feel free to use the Internet for code samples
on how to carry out the other ones. However, you may not copy code from anywhere (it is considered a
case of plagiarism. Instead, learn how it is done and write the code yourself.
---------------------------------------------------------------------------------------------------------------------------------------------
Notebook Formatting Requirement:
The complete code and text for each task above must be located inside its own code cell preceded by a
markup cell containing the title of the task. Failing to adhere to this requirement for even a single task will
result in a 50-point deduction. For each sub-task, use comments to clearly label your code/answers.
---------------------------------------------------------------------------------------------------------------------------------------------
Submission Instructions:
Submit your response on Blackboard in a single Google Colab script (.ipynb file) with the following name:
<your_lastname>_CSC477-01_Assignment_01.ipynb, replacing <your_lastname> with your actual last name.
You will lose all points in this assignment if you submit a file that is not a valid ipynb file (content or formatwise).
Please make sure to follow the submission file naming and formatting requirements to avoid point-penalties.