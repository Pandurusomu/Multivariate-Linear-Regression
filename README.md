# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1  : import pandas as numpy
<br>

### Step2  :  read the csv file using read_cas
<br>

### Step3  :  perform the requierd operation to slove hte problem
<br>

### Step4 : find hte coefficient and intercept
<br>

### Step5 :  finally print the value
<br>

## Program:
```
import pandas as pd
from sklearn import linear_model
df=pd.read_csv(r'C:\Users\admin\OneDrive\for python\py\maths.py\cars.csv')
x=df[['Weight','Volume']]
y=df['CO2']
regr=linear_model.LinearRegression()
regr.fit(x,y)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
predictedCO2=regr.predict([[3300,1300]])
print("Predicted CO2 for the corresponding weight and volume",predictedCO2)





```
## Output:
![WhatsApp Image 2024-01-03 at 07 16 21_a7c72f26](https://github.com/Pandurusomu/Multivariate-Linear-Regression/assets/148988619/16ebd535-9bef-484b-b7fc-620e506ad9b6)


<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
