# Read-from-CSV

## AIM:
To write a python program for reading the csv file content
## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
### Step 2:
Print the number of contents to be displayed using df.head()
### Step 3:
The number of rows returned is defined in Pandas option settings.
### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement
### Step 5:
Increase the maximum number of rows to display the entire DataFrame
## PROGRAM:
```python
#To write a python program for reading content from a CSV file.
#Developed by: MUKESH KUMAR S
#Register Number: 212223240099

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2024-05-14 123027](https://github.com/mukeshkumar1110/Read-from-CSV/assets/152305679/39fdc593-4698-4ce8-8bc3-7410df99015c)

## RESULT:
Thus the program is written to read the csv file.
