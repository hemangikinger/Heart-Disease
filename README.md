# Heart-Disease

![image-1](https://github.com/hemangikinger/Heart-Disease/blob/master/image-1.jpg)

World Health Organization has estimated 12 million deaths occur worldwide, every year due to Heart diseases. Half the deaths in the United States and other developed countries are due to cardio vascular diseases. The early prognosis of cardiovascular diseases can aid in making decisions on lifestyle changes in high risk patients and in turn reduce the complications. This research intends to pinpoint the most relevant/risk factors of heart disease as well as predict the overall risk using logistic regression.
Problem Definition:

Given clinical parameters about a patient, can we predict whether or not they have heart disease?
Introduction:

    We have a data which classified if patients have heart disease or not according to features in it. We will try to use this data to create a model which tries predict if a patient has this disease or not. In this kernel I have performed Exploratory Data Analysis on the Heart Diseases UCI and tried to identify relationship between heart disease and various other features. After EDA data pre-processing is done I have applied k-NN(k-Nearest Neighbors) method and Logistic Regression Algorithm to make the predictions.
    
![image-2](https://github.com/hemangikinger/Heart-Disease/blob/master/image-2.jpg)    

Importing required libraries

![image-3](https://github.com/hemangikinger/Heart-Disease/blob/master/image-3.jpg)    

Loading the data

![image-4](https://github.com/hemangikinger/Heart-Disease/blob/master/image-4.jpg)  

Features of the data set

![image-5](https://github.com/hemangikinger/Heart-Disease/blob/master/image-5.jpg)  

Dimensions of the dataset

![image-6](https://github.com/hemangikinger/Heart-Disease/blob/master/image-6.jpg)  

Checking for null values in the dataset

![image-7](https://github.com/hemangikinger/Heart-Disease/blob/master/image-7.jpg) 



The features described in the above data set are:

1. Count tells us the number of NoN-empty rows in a feature.

2. Mean tells us the mean value of that feature.

3. Std tells us the Standard Deviation Value of that feature.

4. Min tells us the minimum value of that feature.

5. 25%, 50%, and 75% are the percentile/quartile of each features.

6. Max tells us the maximum value of that feature.
Checking features of various attributes

1. Sex

![image-8](https://github.com/hemangikinger/Heart-Disease/blob/master/image-8.jpg) 

2. Chest Pain Type

![image-9](https://github.com/hemangikinger/Heart-Disease/blob/master/image-9.jpg) 

3. fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)

![image-10](https://github.com/hemangikinger/Heart-Disease/blob/master/image-10.jpg) 

4.exang: exercise induced angina (1 = yes; 0 = no)

![image-11](https://github.com/hemangikinger/Heart-Disease/blob/master/image-11.jpg) 

Exploratory Data Analysis

![image-12](https://github.com/hemangikinger/Heart-Disease/blob/master/image-12.jpg)

Plotting the distribution of various attribures

![image-13](https://github.com/hemangikinger/Heart-Disease/blob/master/image-13.jpg)

![image-14](https://github.com/hemangikinger/Heart-Disease/blob/master/image-14.jpg)

![image-15](https://github.com/hemangikinger/Heart-Disease/blob/master/image-15.jpg)

Making Predictions

![image-16](https://github.com/hemangikinger/Heart-Disease/blob/master/image-16.jpg)

Preprocessing - Scaling the features

![image-17](https://github.com/hemangikinger/Heart-Disease/blob/master/image-17.jpg)

1. k-Nearest Neighor Algorithm

![image-18](https://github.com/hemangikinger/Heart-Disease/blob/master/image-18.jpg)

![image-19](https://github.com/hemangikinger/Heart-Disease/blob/master/image-19.jpg)






