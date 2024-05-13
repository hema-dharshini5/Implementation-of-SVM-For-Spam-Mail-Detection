# Implementation-of-SVM-For-Spam-Mail-Detection

## AIM:
To write a program to implement the SVM For Spam Mail Detection.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
```
1.Start the program
2.Import the python pandas library as pd
3.Read the contents of the Spam csv file
4.Display the first 5 rows of the dataset using head()
5.Assign x as v1 values and y as v2 values
6.From sklearn library select the feature extraction and import CountVectorizer
7.CountVectorizer will convert the Text to Numerical Data
8.From sklearn library import Support Vector Classifier (ie. SVC)
9.Predict the x_test using SVC
10.Print the accuracy of the SVM Model 11.Stop the program
```
## Program:
```
/*
Program to implement the SVM For Spam Mail Detection..
Developed by: Hema dharshini N
RegisterNumber:  212223220034
*/
/*
import chardet
file='/content/spam.csv'
with open(file, 'rb') as rawdata:
  result = chardet.detect(rawdata.read(100000))
result

import pandas as pd
data=pd.read_csv("/content/spam.csv",encoding = 'Windows-1252')

data.head()

data.info()

data.isnull().sum()

x=data["v1"].values

y=data["v2"].values

from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=0)

from sklearn.feature_extraction.text import CountVectorizer
cv = CountVectorizer()

x_train=cv.fit_transform(x_train)
x_test=cv.transform(x_test)

from sklearn.svm import SVC
svc=SVC()
svc.fit(x_train,y_train)
y_pred=svc.predict(x_test)
y_pred

from sklearn import metrics
accuracy=metrics.accuracy_score(y_test,y_pred)
accuracy
*/
```

## Output:

Result output

![ml ep 9 1](https://github.com/hema-dharshini5/Implementation-of-SVM-For-Spam-Mail-Detection/assets/147117728/f6d81040-672e-4f3f-ba9c-e7b799d8c12b)

data.head()
![ml ep 9 2](https://github.com/hema-dharshini5/Implementation-of-SVM-For-Spam-Mail-Detection/assets/147117728/9e237ba6-faf8-4531-80a6-fd8d498714bb)


 data.info()

![ml ep 9 3](https://github.com/hema-dharshini5/Implementation-of-SVM-For-Spam-Mail-Detection/assets/147117728/8a4eb0b3-35e6-40cb-a4d9-eef2ef716be6)

data.isnull().sum()


![ml ep 9 4](https://github.com/hema-dharshini5/Implementation-of-SVM-For-Spam-Mail-Detection/assets/147117728/8a6c0be7-5a4a-4193-97fd-ffcc2909a7f6)


 Y_prediction value

![ml ep 9 5](https://github.com/hema-dharshini5/Implementation-of-SVM-For-Spam-Mail-Detection/assets/147117728/bc0b8b0d-184b-4198-ba03-66b8a34c670f)


Accuracy value


![ml ep 9 6](https://github.com/hema-dharshini5/Implementation-of-SVM-For-Spam-Mail-Detection/assets/147117728/21a27655-5d61-4af2-9138-aa153437806c)





## Result:
Thus the program to implement the SVM For Spam Mail Detection is written and verified using python programming.
