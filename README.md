# Week-Seven-Lab-Repository
This is repository dedicated to storing code that has been taken from lab seven, which can be meant for future reference. 

## Lab 7: Feature Engineering & Anomaly Detection in Financial Data
Overview: This week, we are going to practice with two actual data science interview problem sets. Part 1 was used for a remote interview session where candidates were asked to complete 8 questions. Part 2 was used for a 'take-home project,' where candidates were given one day to complete the tasks and present their results during the following in-person interview.

### Part 1
The panel dataset contains commercial customers' financial information and days past due indicator from 2000 to 2020. The goal is to build a binary classifier to predict customers 90+ days past due (90+DPD) probability.
- [x] Load both training and testing sets.
- [x] ] Winsorize "feature_3" by limiting the extreme values to 1 percentile (left tail) and 99 percentile (right tail) on the training set. Name it "feature_3_winsor". Make appropriate treatments on the testing set.
- [x] Identify missing values for "feature_3_winsor". Then, impute the missings with median value on the training set. Name the new feature "feature_3_impute". Make appropriate treatments on the testing set.
- [x] Identify missing values for "feature_2". Then, for each "id", impute the missings with the value from previous year, if not available, use the value from next year. Name the new feature "feature_2_impute". Make appropriate treatments on the testing set.
- [x] Standardize "feature_1", "feature_2_impute", "feature_3_impute", "feature_4" for the training set. Make appropriate treatments on the testing set. Name the features "feature_1_standard", "feature_2_standard", "feature_3_standard", "feature_4_standard"

### Part 2
**Question 1:** Loading the Data
- [x] Please load the data, which is in line-delimited JSON format.
- [x] Please describe the structure of the data. Number of records and fields in each record?
- [x] Please provide some additional basic summary statistics for each field. Be sure to include a count of null, minimum, maximum, and unique values where appropriate.

**Question 2:** Plotting the Data
- [x] Plot a histogram of the processed amounts of each transaction, the ‘transactionAmount’ column
- [x] Report any structure you find and any hypotheses you have about that structure.

**Question 3:** Data Wrangling
- [x] Can you programmatically identify reversed and multi-swipe transactions?
- [x] What total number of transactions and total dollar amount do you estimate for the reversed transactions? For the multi-swipe transactions? (please consider the first transaction to be "normal" and exclude it from the number of transaction and dollar amount counts)
- [x] Did you find anything interesting about either kind of transaction? 



