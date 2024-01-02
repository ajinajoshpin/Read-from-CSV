# Read-from-CSV

## AIM:

To write a python program for reading content from a CSV file.

## EQUIPMENTS REQUIRED:
Hardware – PCs
Anaconda – Python 3.7 Installation / Google collab
## ALGORITHM:
### Step 1:
Import pandas as pd.

## Step 2:
Read the CSV file using read_csv method.

## Step 3:
Use head and tail method to get the required contents from the file.

## Step 4:
Use len() method to get the number of rows and columns.

## Step 5:
Display the result.
## PROGRAM:
```
#Program to read contents from a csv file

#Developed by: ajina joshpin

#RegisterNumber:23013547


import pandas as pd

df=pd.read_csv('data.csv')

print(df.head(10))

print(df.tail(5))

print("Number of rows:",len(df.axes[0]))

print("Number of columns:",len(df.axes[1]))

```

## OUTPUT:
![Screenshot 2024-01-02 151514](https://github.com/ajinajoshpin/Read-from-CSV/assets/148514578/c07c081e-0982-4c40-ba7d-5bd632f68412)

![Screenshot 2024-01-02 151528](https://github.com/ajinajoshpin/Read-from-CSV/assets/148514578/4b3692a3-f107-40c3-9001-fc575922dd93)


## RESULT:
the program has been executed successfully
