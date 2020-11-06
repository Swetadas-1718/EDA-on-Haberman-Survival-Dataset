# Exploratory Data Analysis on Haberman's Survival Data Set

## Why EDA ?
Exploratory Data Analysis (EDA) is an approach for analyzing data sets to summarize their main characteristics, often with visual methods.It is always a good idea to explore a data set with multiple exploratory techniques. The goal of exploratory data analysis is to obtain confidence in your data.Generating accurate models on wrong data can be really dangerous.

## Understanding the Data Set
### Description:
The dataset contains cases from a study that was conducted between 1958 and 1970 at the University of Chicago’s Billings Hospital on the survival of patients who had undergone surgery for breast cancer.
### Features:
There are 4 attributes, out of which 3 are features and the one is class attribute. There are 306 datapoints. 
* age - Age of the patient during operation
* year - Patient's year of operation
* nodes - No of nodes axillary nodes found
* status - Survival status
    1 ---> Patient survived for 5 years or longer after operation!
    2 ---> Patient died with in 5 years !
### Domain Knowledge :
* Lymph nodes are small, bean-shaped organs that act as filters along the lymph fluid channels. As lymph fluid leaves the breast and eventually goes back into the bloodstream, the lymph nodes try to catch and trap cancer cells before they reach other parts of the body. Having cancer cells in the lymph nodes under your arm suggests an increased risk of the cancer spreading. 
  
  Source - https://www.breastcancer.org/symptoms/diagnosis/lymph_nodes

* The more lymph nodes that contain cancer cells, the more serious the cancer might be.
### Objective : 
  To predict the survival chances of patients who had undergone breast surgery.
