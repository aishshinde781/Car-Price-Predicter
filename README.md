# Car-Price-Predicter

1. Objective:

In this project, we will be predicting the prices of used cars.we will be bulding machine learning model and see how the model performs.

2. Data used:

Here we have used the data from the kaggle. 

3. Data insepection:

In this section , we will explore the data. First let's see what columns we have in the data and their types along with missing values information.
 
 ![Screenshot (57)](https://user-images.githubusercontent.com/105923718/225853803-4d4bedac-a532-4032-959d-bae446c16677.png)
 
 We can observe that data have 892 rows and 6 columns.
 
 We can see that there are missing values in the data in 2 columns i.e km driven and fuel types.
 
 'Price' column/feature is going to be the target column or dependent feature in this project.
 
 4.Data preparation:
  
  Here we will clean the data and prepare it for training the model.
  
 'Year' column 
 
  After analyzing the year column we found that it does not contain any missing values but it has many non-year values so we can drop that rows which contain non-year values and convert the year column into a integer type.
  
'Price' column

 price column also have the same problem instead car price value there is a row which says Ask for price so we can drop that rows and convert that column into integer.
 
 'Kms-driven' column
 
 kms driven column has Nan values we can drop that Nan values.
 
 'Name' column
 
 in the name column the car name is two big and inconsistient so we keep first theree words of car name.
 

  
  
  
  
 
 
