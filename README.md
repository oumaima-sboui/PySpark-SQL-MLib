# PySpark-SQL-MLib

## Table of contents
* [About the project](#About-the-project)
* [About the dataset](#About-the-dataset)
* [Parts](#Parts)



## About the project
In this project we used some tools of PySpark library which is an interface for Apache Spark in Python. 
It  allows you to write Spark applications using Python APIs, 
PySpark supports most of Spark’s features such as Spark SQL, DataFrame, Streaming,
MLlib (Machine Learning which includes a variety of models) and Spark Core. For more read this [documentation](https://spark.apache.org/docs/latest/api/python/) 
In this code we will cover Spark SQL, DataFrame,MLlib.

## About dataset

the used dataset is the famous titanic one ,this dataset is taken from [kaggle's datasets](https://www.kaggle.com/datasets/brendan45774/test-file?resource=download).  
There are 418 Rows and 12 Columns in the Dataset :
 * PassengerId: integer 
 * Survived: integer 
 *  Pclass: integer 
 *  Name: string 
 * Sex: string 
 * Age: double 
 *  SibSp: integer 
 * Parch: integer 
 * Ticket: string 
 * Fare: double 
 * Cabin: string 
 * Embarked: string 


## Parts
* from PySpark SQL we have used commands and queries for data processing and manipulation.
* from PySpark MLlib  we have deployed the linear regression model training and its related commands.
