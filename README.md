# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output

Developed By: Sriram G

Register Number: 212222230149

```
import pandas as pd
df =pd.read_csv("SAMPLEIDS.csv")
print(df)
```
![model](1.png)
```
df.head(5)
```
![model](2.png)

```
df.describe()
```
![model](3.png)

```
df.info()
```
![model](4.png)

```
df.tail()
```
![model](5.png)

```
df.shape
```
![model](6.png)

```
df.columns
```
![model](7.png)
```
df.isnull().sum()
```
![model](8.png)
```
df.fillna(value=10)
```
![model](9.png)
```
df.fillna(method='ffill')
```
![model](10.png)

## IQR
![image](https://github.com/Sriram8452/exno1/assets/118708032/f83683b9-a177-4242-8d91-a32a9b26fb75)

![image](https://github.com/Sriram8452/exno1/assets/118708032/590c1f1a-a378-4f4f-a6ab-6f3d9df24c13)

![image](https://github.com/Sriram8452/exno1/assets/118708032/8e88d84d-03f2-4a5c-80ee-dbd666f4bf4d)

![image](https://github.com/Sriram8452/exno1/assets/118708032/47fdaa52-3902-4107-8fbe-9cb35542d30c)

![image](https://github.com/Sriram8452/exno1/assets/118708032/2d2e1c58-93f2-4aa8-b5e3-c5d11451e5b8)

![image](https://github.com/Sriram8452/exno1/assets/118708032/c3fbf290-dea1-4429-bcc0-3220ab0ea42c)

![image](https://github.com/Sriram8452/exno1/assets/118708032/806a7f90-977b-40fb-962d-8e7ce6c1a00e)

## Z_Score
![image](https://github.com/Sriram8452/exno1/assets/118708032/2f2ee367-2c60-4be1-a7cb-945353ce64e9)

![image](https://github.com/Sriram8452/exno1/assets/118708032/2ec82215-a3a3-42d2-8fe5-9c41ff777c60)

![image](https://github.com/Sriram8452/exno1/assets/118708032/9edfc79d-c23f-479e-acc6-414ebb0c7e87)

![image](https://github.com/Sriram8452/exno1/assets/118708032/62f3cc80-1377-43cb-9de9-c6971945f0d4)

![image](https://github.com/Sriram8452/exno1/assets/118708032/8be85606-1c4b-4e7e-9c4c-5937b6172fca)

![image](https://github.com/Sriram8452/exno1/assets/118708032/73df2b3c-f05c-4234-8659-ca778f79fe93)


# Result
 
The Data Cleaning Process was executed successfully
