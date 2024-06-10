# Association-Rule-Learning-and-PCA-for-Digit-Classification
Project Overview
This project is divided into two main tasks:

Association Rule Learning:

Implementing the Apriori algorithm to generate frequent itemsets.
Developing functions to learn and write association rules that meet specified minimum support and confidence thresholds.
Using a toy dataset to demonstrate the generation of association rules.
Principal Component Analysis for Logistic Regression:

Loading the 7-vs-9 digit recognition dataset.
Implementing logistic regression to classify the digits.
Using Principal Component Analysis (PCA) to reduce the dimensionality of the dataset.
Plotting the error rate of logistic regression on the validation set as a function of the number of principal components.
Task 1: Association Rule Learning
Data Description:

Dataset: A toy dataset with items represented by numbers.
Items List: ['Jurassic Park', 'Star Wars', 'Forrest Gump', 'Home Alone', 'Toy Story']
Examples List: [[1, 2, 4], [1, 4], [1, 3, 4], [0, 1], [0, 3], [1, 3, 4], [0, 2, 3], [3], [1, 3, 4], [1]]
Total Items: 5
Key Responsibilities and Accomplishments:

Frequent Itemset Generation: Implemented the Apriori algorithm to find frequent itemsets.
Association Rule Learning: Developed functions to generate rules based on minimum support and confidence.
Data Structures: Utilized set and frozenset for efficient itemset operations.
Skills & Tools: Python, Apriori algorithm, association rule learning.
Task 2: Principal Component Analysis for Logistic Regression
Data Description:

Dataset: USPS digit dataset (7-vs-9) with 16x16 grayscale images.
Classes: Binary classification of digits 7 and 9.
Preprocessing: Data z-score normalized.
Key Responsibilities and Accomplishments:

Data Loading: Loaded the 7-vs-9 digit recognition dataset.
Dimensionality Reduction: Applied PCA to reduce dataset dimensionality.
Model Implementation: Implemented logistic regression for digit classification.
Error Analysis: Plotted the error of logistic regression on the validation set as a function of the number of principal components (1 to 100).
Skills & Tools: Python, NumPy, Matplotlib, logistic regression, PCA, data visualization.
