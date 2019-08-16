# Arvato-Capstone-Project-
### Introduction

This project was part of my capstone project for the Udacity’s Data Scientist Nanodegree. It is based on real life data provided by Bertelsmann Arvato Analytics. I analyzed demographics data for customers of Arvato Financial Services, a mail-order sales company in Germany and compared it to the general population demographics. I applied unsupervised learning techniques to for customer segmentation to identify customers that form the core customer base for the company. The using supervised learning techniques; I created a model to predict those people that are most likely to become customers for the company. 
### Data
4 datasets were provided:
•	Udacity_AZDIAS_052018.csv: Demographics data for the general population of Germany; 891 211 persons (rows) x 366 features (columns).
•	Udacity_CUSTOMERS_052018.csv: Demographics data for customers of a mail-order company; 191 652 persons (rows) x 369 features (columns).
•	Udacity_MAILOUT_052018_TRAIN.csv: Demographics data for individuals who were targets of a marketing campaign; 42 982 persons (rows) x 367 (columns).
•	Udacity_MAILOUT_052018_TEST.csv: Demographics data for individuals who were targets of a marketing campaign; 42 833 persons (rows) x 366 (columns).
The first two datasets were used for comparison analysis – how customers are similar or differ to the general population. The results from this analysis were then used to create predictions on the MAILOUT files. 
Another file (feat_info) was also provided which includes a list of attributes, description and corresponding data values. This dataset had 324 attributes.

### Libraries
Pandas, Numpy, Sklearn, Time, Seaborn, Pickle, matplotlib

### Summary/Report of findings
A detailed report can be found at: https://medium.com/@njoks2/customer-segmentation-report-for-arvato-financial-services-cd1142ee5aef

### Acknowledgements
I would like to than Bertelsmann Arvato Analytics for providing the data used for this project and for all the mentors at Udacity. 
