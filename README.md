# Read-from-CSV

## AIM:
To write a python program for reading the csv file content.

ALGORITHM:
Step 1:
Load the CSV into a DataFrame.

Step 2:
Print the number of contents to be displayed using df.head().

Step 3:
The number of rows returned is defined in Pandas option settings.

Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```
## Developed by:K.NIVETHA
## REGISTER NUMBER: 22009186

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```

## OUTPUT:

![PANDAS](https://user-images.githubusercontent.com/119559844/214965798-092846f4-ce58-42a9-be8e-a9aaad7f0a0f.png)


## RESULT:
Thus the program executed successfully for read csv file.
