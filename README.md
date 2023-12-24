# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Display the result.

## PROGRAM:
```
Developed by:SHARMITHA V
Register No: 212223110048
To write a python program for reading content from a CSV file.

import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:
![image](https://github.com/sharmitha3/Read-from-CSV/assets/145974496/c180fa56-0c9c-4766-8dcb-bc13ef8ce13c)


## RESULT:
Thus python program for reading content from a CSV file is successful.
