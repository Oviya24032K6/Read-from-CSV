# Read-from-CSV

## AIM:
To write a python for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas as pd
### Step 2:
Read the CSV file using_csv method
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the required contents from the file.
### Step 5:
Print the output
## PROGRAM:
```
# DEVELOPED BY: OVIYA P
# REGISTER NUMBER: 212223110033

Program to read contents from a csv file 
import pandas as pd 
df=pd.read_csv('csv1.csv') 
print(df.head(10)) 
print(df.tail(5)) 
print("Number of rows:",len(df.axes[0])) 
print("Number of columns:",len(df.axes[1]))

```
## OUTPUT:
![output](image.png)


## RESULT:
Thus the program is wriiten in read csv file format
