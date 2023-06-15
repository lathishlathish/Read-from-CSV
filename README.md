# Read-from-CSV

## AIM: 
To write a python program to read contents from a CSV file. 
## ALGORITHM:
### Step 1: Import pandas module as pd.
### Step 2: Using pd.read_csv() method read the CSV file.
### Step 3: Using df.head() print the first 10 rows of the CSV file.
### Step 4: Using df.tail() print the last 5 of the CSV file.
### Step 5: Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

## PROGRAM:
```
#Program to read contents from a CSV file.
#Developed by: LATHISH KANNA .M
#RegisterNumber: 212222230073
```
```
import pandas as pd
f=pd.read_csv('nba.csv')
print(f.head(10))
print(f.tail())
print('Number of Rows:',len(f.axes[0]))
print('Number of column:',len(f.axex[1]))
```
## OUTPUT:
![output 1](https://github.com/deepikasrinivasans/Read-from-CSV/assets/119393935/123bdb38-0da1-441f-af04-ed41d23c6a67)
## RESULT:
Hence the program is executed successfull.
