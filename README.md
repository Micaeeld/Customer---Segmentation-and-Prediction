##### Use https://nbviewer.org to upload the file in case of errors
---

# Exploratory analysis and clustering of customer data
This notebook presents an exploratory analysis and clustering of a company's customer data. The dataset was obtained from Kaggle, and contains information about customers, such as age, gender, marital status, income level, among others.

## Data set
The dataset consists of 2000 rows and 8 columns. Columns include:

Age: customer age
Gender: Customer's gender (male or female)
Marital status: client's marital status (single, married or divorced)
Level of education: level of education of the client
Income Level: Customer's income level
Number of children: number of children of the client
Region: region where the customer resides
Annual spend: how much the customer spends annually on the company

## Exploratory analysis
Exploratory analysis was performed to better understand customer characteristics and identify patterns and trends in the data. Some of the questions that were explored during the analysis include:

- What are the demographic characteristics of the customers?
- What is the breakdown of annual customer spending?
- Is there any correlation between customer characteristics and annual spend?

## Data preparation
Before creating the clustering model, the data was pre-processed and prepared for training. Some of the data preparation steps include:

- Cleaning of missing data and outliers
- Coding of categorical features
- Clustering
To identify possible groups of customers, the K-means algorithm was used to perform clustering. Several techniques were used to select the optimal number of clusters, such as silhouette analysis and the elbow method.

Customer groups were created based on their characteristics, such as age, gender, marital status, income level and number of children. Each customer group was analyzed and characterized based on its main characteristics.

## Conclusion
This notebook presented an exploratory analysis and clustering of a company's customer data. Exploratory analysis helped to better understand customer characteristics and identify patterns and trends in the data. Clustering made it possible to identify groups of customers with similar characteristics, which could help the company create more targeted marketing and sales strategies for each group.

Although the dataset is relatively small, the analysis and clustering were successful in identifying potential customer groups based on their characteristics. This notebook may be useful for other companies that want to perform a similar analysis of their own customer data.

## Contribution

Contributions are welcome! If you find any bugs or have any suggestions for improvement, please open an issue in the repository or submit a pull request.
a pull request.
