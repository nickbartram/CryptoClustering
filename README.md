# README for Module 19 Challenge (CryptoClustering)

## Introduction

This challenge looks at the change in crypto currencies' value over time. It uses machine learning to analyze the data (preprocessing, training, predicting, and plotting).

## Data

The data consists of a CSV file (`crypto_market_data`) that contains data related to crypto currency value over time. It is a relatively small CSV file with only 41 rows and 8 columns. Each row represents a different crypto currency, and the columns are values over different time increments.

## Methodology

Pandas is used to quickly read the data from the CSV file. Next sklearn is used to preprocess the data using `StandardScaler`. The data is visualized using `hvplot` regularly in this challenge. `KMeans` is used to to group and cluster the data points. `PCA` is used to horizontally compress the data, or reduces the number of features down to 3. 

## Results

The results are somewhat unclear. The data was successfully grouped using `KMeans`, and the data's features were eventually reduced using `PCA`. However, the clusters did not break away into perfectly distinct groups whether using `PCA` or not. 

## Conclusion

There is still some investigating to be done here. It's somewhat unclear exactly what makes these clusters distinct, and there boundaries are also somewhat unclear. Using `PCA` did help to make at least one cluster much more distinct. 

## References

Class materials were used extensively for this assignment, as well as:

* stackoverflow.com
* Xpert Learning Assistant
* ChatGPT.com

## Usage

This `.ipynb` file should be easy to use. Hit `Run All` at the top of the file in VSCode and everything should run fine.
