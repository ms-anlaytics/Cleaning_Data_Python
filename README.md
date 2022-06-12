# Project Cleaning Data


Description of Research
•	Research Decision: Identifying reasons a customer might leave the company is a realistic concern, as it saves the company money in retaining its current customers. Describing Variables: The dataset includes customers who left, services they used, account information about the customer, and customer demographics information. 
•	Data-Cleaning Purpose: The cleaning plan checks the data for missing values and replaces data where possible by imputing or assigning a variable to the data. 
•	Data-Cleaning Approach: Qualifying the data as either categorical or continuous is an essential first step in finding any weaknesses in the dataset. 
•	Choosing programming language and libraries: Python is used for the project because it can be applied inside a Jupiter Notebook and can easily verify the results of changes made to the dataset. Pandas and NumPy are used to import, display, and manipulate data using a Data Frame of the CSV file. 
•	Findings and Methodology: The data exploration results revealed that missing data exists in the categorical and continuous collections made in the previous sections.

  Example 1. Continuous Data Results
  | Variable | Result | 
  | --- | --- |
  | Children | 0.2495 |
  | Income | 0.2490 |
  | Age | 0.2475 |
  | Bandwidth_GB_Year | 0.1021 |
  | Tenure | 0.0931 |


  Example 2. Categorical Data Results
  | Variable | Result | 
  | --- | --- |
  | Techie | 0.2477 |
  | Phone | 0.1026 |
  | TechSupport | 0.0991 |

•	Methodology: Since categorical data is not quantitative, an average of the variables cannot substitute in place of missing variables, after dropping the missing categorical fields results in 70% of data remaining for study in the dataset without the errors occurring from missing values of category data. 
•	Summary of Outcome: The data was imported into a Jupiter Notebook and reviewed for completeness. The total size of the dataset was determined to begin testing for missing data by identifying data columns as either categorical or continuous data to use a statical central tendency to impute the data or delete the missing rows of data as missing categorical data cannot be imputed via statistics as is. Next, outliers within the dataset were examined for possible adverse effects because they can skew the data. 
•	Limitations: Treating the missing categorical data as qualitative. Labeling the variable with a familiar name does provide a way to measure the impact of the missing categorical information and preserve the rest of the data without deleting it. Imputing continuous data is somewhat more manageable.
•	Decisions Making: The limitation of having missing data impacts the accuracy of the data in general. Deciding to leave it in has a better outcome for the continuous data portion of the dataset as it limits the influence of using the mean to impute missing data in the continuous dataset.
•	Principle Component Analysis: After extracting 23, a scree plot identifies variable reduction using the sklearn.decomposition package from Python.
•	Benefits to the Organization: The organizational objective is to reduce churn, understanding which variables contain the most weight as a principal component adds to the precision of results in determining trends in the churn data. 
