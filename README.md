# Repository for documenting credit scorecard model development process learnt

The Jupyter Notebook (Credit Scorecard with scorecardpy)  and data (hmeq_data.csv) in this repository are provided as part of lab practice in the Financial Analytics module taught in the Singapore Management University(SMU)'s School of Computing and Information Systems(SCIS).
The Jupyter Notebook contain Python codes on the process to developing a credit scorecard model, which helps to determine the credit score of loan applicants and the likelihood of them defaulting on loans. It brings value to financial institutions offering lending services because majority of these financial institutions' revenue comes from lending and thus reducing the default rates of loan applicants would reduce revenue losses.

Here is an outline of the process of developing a credit scorecard model:
- Data Exploration
- Data Preparation/Pre-processing
- Initial Characteristic Analysis ( Weight of Evidence(WOE) binning and univariate screening)
-Training and evaluating machine learning model (in this case logistic regression)
- Credit scorecard generation

The python package `scorecardpy` (https://github.com/ShichenXie/scorecardpy)  is used to make the process of credit scorecard model development more efficient.
I have consolidated and added new content such as the use of Synthetic Minority Oversampling(SMOTE) Technique to deal with the imbalanced target classes and use of the Population Stability Index (PSI) to monitor the performance of the credit scorecard model.

Note: Please put the 2 files together in the same folder!
