# Performing exploratory data analysis on Haberman's Breast Cancer Survival Dataset using Python:

### What is EDA?
Exploratory data analysis (EDA) is used by data scientists to analyze and investigate data sets and summarize their main characteristics, often employing data visualization methods. It helps determine how best to manipulate data sources to get the answers you need, making it easier for data scientists to discover patterns, spot anomalies, test a hypothesis, or check assumptions. (source - ibm.com)

### Data Description:
The dataset contains cases from a study that was conducted between 1958 and 1970 at the University of Chicago's Billings Hospital on the survival of patients who had undergone surgery for breastcancer.

You can download the dataset from kaggle "https://www.kaggle.com/gilsousa/habermans-survival-data-set".

### Attribute Information:
The dataset consists of the following attributes.
1. Age of patient at time of operation (numerical)
2. Patient's year of operation (year - 1900, numerical)
3. Number of positive axillary nodes detected (numerical)
4. Survival status (class attribute)
   - 1 = the patient survived 5 years or longer
   - 2 = the patient died within 5 year

### Objective:
Setting the objective is the key in EDA which will structure your thoughts in the entire analysis. Here the objective is to predict whether the patient will survive after 5 years or not based upon the patient’s age, year of treatment and the number of positive lymph nodes.
