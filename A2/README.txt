ECSE 557 Introduction to Ethics of Intelligent Systems
Assignment #2: Data and Privacy
README

The only pre-requisite to running this Python notebook is to ensure that all packages and their corresponding dependices have been downloaded. 
Refer to the top of the notebook to see which packages are needed for this assignment. The IBM package already has the "pip install" function called in the first cell of the notebook.

The code is organized in the following order:
1. Install the IBM DP package
2. Import all necessary packages
3. Read the data from my personal Github using Pandas built-in functions
4. Define K-anonymity and L-diversity functions
5. Manipulate data and caluclate K-anonymity and L-diversity to create 5-anonymous dataset from the first twenty rows
6. Encode complete dataset so all feature data is in integer or float format. Split data into training and testing data
7. Perform data analysis (class distribution, feature histograms and correlation heatmap)
8. Create standard logistic regression classifier and perform initial prediction and accuracy calculations.
9. Create differentially private logistic regression classifier and perform initial prediction and accuracy calculations.
10. Compare the accuracies of the two clasifiers side-by-side.
11. Fine-tune epsilon hyper-parameter and plot results to find optimal epsilon.

More specific details for each cell are provided in the code, either through text blocks of comments.