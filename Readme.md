# Airline Delays Dataset

## Overview

This repository contains a dataset focusing on airline delays, aiming to explore association rules between various features and the target variable (delays). The dataset includes information related to flights, airports, and other relevant factors that might contribute to delays in the airline industry.

## Dataset Description

The dataset encompasses a variety of features, both continuous and categorical, providing a comprehensive view of factors that may influence flight delays. Features include details about departure and arrival times, airport information, weather conditions, and more.

Airlines Dataset Inspired in the regression dataset from Elena Ikonomovska
Data: [Airlines Dataset](https://users.iit.demokritos.gr/~izavits/datasets/Airlines.arff.zip)
The dataset is in "arff" format. You will easily understand the features and their values by inspecting the file.

## Preprocessing Techniques

To enhance the analysis, the dataset undergoes preprocessing steps, specifically focusing on continuous variables. Two distinct methods are employed to make continuous variables more amenable to association rule mining:

1. **Discretization using k-means and decision trees:** Continuous variables are transformed into discrete bins using the k-means clustering algorithm and decision trees. This step is crucial for uncovering patterns in the data.

2. **Custom binning:** In addition to automated methods, the dataset undergoes binning through a custom approach, allowing for a more tailored discretization of continuous variables.

## Association Rule Mining Methods

The repository implements two distinct methods to discover association rules within the dataset:

1. **Apriori Method:** A classic association rule mining algorithm, the Apriori method, is employed to identify interesting relationships between different features and the target variable (delays).

2. **FP-Growth Method:** The FP-Growth method is utilized as an alternative approach to uncover patterns in the dataset. This algorithm is known for its efficiency in handling large datasets and can reveal frequent itemsets in a more streamlined manner.

## Getting Started

Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Conclusion

This dataset and associated code provide a valuable resource for understanding the intricate relationships between different factors and airline delays. The implemented preprocessing techniques and association rule mining methods aim to uncover meaningful insights that could contribute to improving the efficiency and reliability of airline operations. 
