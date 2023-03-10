The only pre-requisite to running this Python notebook is to ensure that all packages and their corresponding dependices have been downloaded. 
Refer to the top of the notebook to see which packages are needed for this assignment. The AIF360 package already has the "pip install" function called in the first cell of the notebook.

The code is organized in the following order:
1. Install the AIF360 pacakage
2. Import all necessary packages
3. Define the compute_metrics() function
4. Encode complete dataset so all feature data is in integer or float format. Split data into X and y datasets, and training and testing data
5. Create standard logistic regression classifier and perform initial prediction and accuracy calculations.
6. Define privileged and unprivileged groups
7. Create BinaryLabelDatasets instances for each group and calculate fairness metrics on training data.
8. Create BinaryLabelDatasets instances for each group and calculate fairness metrics on testing and predicted data.
9. Perform LFR pre-processing (fit and transform dataset) and re-calculate fairness metrics.

More specific details for each cell are provided in the code, either through text blocks of comments.