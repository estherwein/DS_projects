# Gold mining yield at Zyfra company

Zyfra company develops efficiency solutions for heavy industry. Here, the company presents the separation steps required when mining gold that involves a number of separation processes at the end of which gravel is obtained with a high percentage of gold.

Separation processes:

1. The gravel which is composed of different types of metals enters the process of flutation. This process is based on the density of the metals in which the gravel is put into a heavy water solution and any material whose density is higher than the solution sinks, and the materials whose density is lower than the solution float above it and then exit through the tail. The precipitated substances are called rougher concntrate and they continue to two purification processes.
2. The rougher concentarte undergoes two purification processes in which the goal is to increase the gold concentration by filtering the other metals. After this process the final concentration is obtained.


The purpose of the project is to build a prototype of a machine learning model for Zyfra. The model should predict the amount of gold recovered from gold ore using data on extraction and purification. The model will help to optimize the production and eliminate unprofitable parameters.

**Datasets:**
* `gold_recovery_train.csv`
* `gold_recovery_test.csv`
* `gold_recovery_full.csv`

Evaluate the model using sMape (Symmetric Mean Absolute Percentage Error) - The best model obtained is LASSO with sMAPE = 6.31
