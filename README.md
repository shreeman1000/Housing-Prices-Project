# Housing-Prices-Project
This was a Project given by Verzeo during my internship. The objective was to perform data cleaning and data visualization on the housing prices dataset and then select and appropiate machine learning algorithm which works well on this Regression problem.
I tried the following algorithms and achieved the following accuracy -


| Model Name         | Accuracy               |
| ------------------ | ----------------------:| 
| Linear Regression  | -6.039029854117735e+24 |
| Ridge              | 0.8067516492186335     |
| E-Net              | 0.8203377224095642     |
| Lasso              | 0.80628791663266       |

Data cleaning consisted of replacing null values with either 0 in some cases like pool column where null represented no pool and with average values in other cases.
It also consisted of simple label encoding whihc i did manually for columns which had values like rating (poor = 0, average = 1) and so oalso the basic cleaning which is to normalize the dataset for better performance and faster convergance.
I found that E-Net worked best on this model and Linear Regression worked horribly as was expected as there are very little linear relations in a dataset with as many features as this.
