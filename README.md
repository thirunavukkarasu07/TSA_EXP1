# Ex.No: 01A PLOT A TIME SERIES DATA
###  Date: 12.08.2025

# AIM:
To Develop a python program to Plot a time series data (population/ market price of a commodity
/temperature.
# ALGORITHM:
1. Import the required packages like pandas and matplot
2. Read the dataset using the pandas
3. Calculate the mean for the respective column.
4. Plot the data according to need and can be altered monthly, or yearly.
5. Display the graph.
# PROGRAM:

```
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import warnings
warnings.filterwarnings("ignore")
df=pd.read_csv("C:\\Users\\admin\\time series\\housing_price_dataset.csv")
df.head()
plt.figure(figsize=(10, 6))
sns.scatterplot(data=df, x='YearBuilt', y='Price', color='darkorange', alpha=0.7)
plt.title('Relationship Between YearBuilt and Price')
plt.xlabel('YearBuilt')
plt.ylabel('Price')
plt.tight_layout()
plt.show()
```











# OUTPUT:

<img width="1238" height="740" alt="image" src="https://github.com/user-attachments/assets/15535053-c8f0-4bcf-9097-c2a8721dad9c" />






# RESULT:
Thus we have created the python code for plotting the time series of given data.
