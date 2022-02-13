# Telecom Project - 0.91 ROC-AUC

**Description**

Telecom - a company that provides Telephone and Internet services to its customers, wanted, as part of the customer retention project, to be able to observe the behavior of its customers and based on their data understand whether customer plans to leave the company or not, in order to be able to retain customers whose data indicate that they intend to leave, by offering attractive conditions and affordable packages that will encourage them to remain customers of the company.

**Datasets:**
- contract.csv - contract information
- personal.csv - the client's personal data
- internet.csv - information about Internet services
- phone.csv - information about telephone services


**Specifying project requirements**
* Predict customers who plan to leave the company in order to offer them special plans to retain them
* The target feature is 'EndDate' column equals 'No'
* The primary metric of model success is AUC-ROC above 0.75


**Downaload the data and study the genenral information**


**Data preprocessing, for each dataset:**
* Check and fill in NaN values 
* Check and remove duplicates rows 
* Check and convert types of columns
* Add, remove or engineering features according to datasets
* Merge all the datasets to one table 
* Change the Boolean columns (contain Yes/No values) using OHE in order to get numeric values for the train model


**Create and train the model**
* Split the data into train and test at a ratio of 70:30, since the data contains less than 10K observations, this is the accepted ratio
* Build a scalable data pipeline - We will use tree-based models like RandomForest or distance-based models like KNN or advanced models like catboosting, since this is a classification task, and linear models will probably not give a good result in this type of task
* Tune the hyperparameters using CV in order to find the better values of hyperparameters
* Build a dummy model in order to test what quality is obtained with the natural probability of the data


**Evaluation the model**
* This is a classification task whose purpose is to detect TP or TN, so we will use an ROC-AUC metric to evaluate the model.
* Another metric for evaluating the model will be accuracy in order to check how many correct observations the model predicted in relation to the total number of input samples.

**Testing and evaluation**
* Test the test set with the models built
* Evaluate the results with the same metrics above

**Conclusion**
* Choosing the winning model
* A summary of all the various stages and models selected and a general summary of the entire project
