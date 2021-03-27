# Lead Scoring Case Study using Logistic-Regression

### Problem Statement : 
X Education wants to increase their conversion rate so as to optimally convert people into taking their courses.
The following steps were performed in order to achieve the goal.
1. Data Cleaning: 
    - Dropping high % columns and highly skewed columns.
2. EDA:
    - Outliers were checked and 95% quartile range was preserved
    - Relationship between variables and customers who converted were observed
3. Data Preparation
    - Varaibles with Yes/No columns were converted to 1:0
    - Dummy Varibles created with hot encoding
4. Train Test Split Data
    - Data was spilt into 70: 30 rule , with 70 % being used for training
    - Standard scaler was used to scale numerical columns
5. Model Building
    - Feature selection using RFE was used and in every iteration variables were removed based one P and VIF.
    - The resultant model had a Sensitivity of 82% and Specifity of 76 % with an accuracy of 78%
6. Model Evaluation: Evaluation resulted in Sensitivity of 82% and Specifity of 77 % with an accuracy of 79%
7. Precision and Recall were also evaluated
### Learnings Gathered :
- The Data Dictionary is of high importance as it gives definition of each variable in terms of business, for example there were some columns that were added by the sales team which would actually have an effect on the outcome however they should not be part of the model evaluation as they are not the properties of the customer.
- Columns that are highly skewed are to be investigated and appropriate measures needs to taken. The measures could be to drop the columns or to assign them to certain variables and then proceed with the process.
- Accuracy may not necessarily be the sole measure of the model, based on the problem statement , as in this case one might concentrate on increasing the Sensitivity of the model in order to convince prospective customers.
