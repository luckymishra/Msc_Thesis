# Msc_Thesis
Final submission - Cohort 8 (Dec 2020 - Aug 2021)

Several experiments have been conducted to understand the behaviour of machine learning algorithms with retail data, such as accuracy achieved on fully cleanse data, partially cleanse data and uncleansed datasets. I have only considered the model classification result from experiment 12 in the thesis report hence only uploading that. In this scenario, the cancelled order has not been removed from the dataset manually and outliers are only treated statistically.

Order of executing the files should according to the following steps by keeping all files into the same folder.

Step 1- Download the transaction data "online_retail_II.xlsx"  from https://archive.ics.uci.edu/ml/datasets/Online+Retail+II

Step 2- Run Pandas_Profile.ipynb (pandas profile output)

Step 3- Run Msc_CVL_code EDA.ipynb (Entire EDA process )

Step 4- Run Msc_CVL_code Clustering ML Selection_withC.ipynb (Experiment of RFM manual and RFM lifetime with k-means,dbscan and GMM ,cluster generation )

Step 5- Experiment_12 clean_with_C_RFM_M-ALL (Model building, using Voting classification, explain voting classification prediction)
