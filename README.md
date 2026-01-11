# Black Friday - Exploratory Data Analysis and Feature Engineering

This project aims to perform Exploratory Data Analysis on Black Friday Dataset. This dataset contain different types of Categorical Variables that are needed to be dealt with, posing a challenge when performing an EDA. The dataset also has a significant number of NULL values that will be imputed.

There are multiple categorical features such as:
* Gender - Male or Female
* Age - age groups
* City Category - A, B, or C
* Years Stayed in the Current City - 1, 2, 3 or 4+

In this project, we perform:
* Imports - pandas, numpy, matplotlib, and seaborn.
* Reading the csv.
* General dataset information/statistics.
* Unnecessary/Irrelevant features are dropped.
* Missing values are imputed.
* Features are converted to proper data types.

We make visualisation of each feature against the Purchase feature to see any relationship between them.

Finally, we split the data into Train and Test split, then the features are scaled using standard scaler, making the dataset ready for Model Training.