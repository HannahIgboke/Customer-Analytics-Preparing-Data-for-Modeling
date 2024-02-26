<div align="center">
  
  # Customer Analytics: Preparing Data for Modeling🤹‍♀️

</div>


## What is the Problem?

<p align="center">
    <img width="300" src="https://github.com/HannahIgboke/Customer-Analytics-Preparing-Data-for-Modeling/blob/main/Files/Problem.jpg" alt="The problem">
</p>


**A common problem when creating models to generate business value from data is that the datasets can be so large that it can take days for the model to generate predictions**. Ensuring that the dataset is stored as efficiently as possible is crucial for allowing these models to run on a more reasonable timescale without having to reduce the size of the dataset.


In this scenario, I have been hired by a major online data science training provider called Training Data Ltd. to clean up one of their largest customer datasets. This dataset will eventually be used to predict whether their students are looking for a new job or not, information that they will then use to direct them to prospective recruiters.


I have been given access to customer_train.csv, which is a subset of their entire customer dataset, so I can create a proof-of-concept of a much more efficient storage solution. They have also requested that the DataFrame should be filtered to only contain students with 10 or more years of experience at companies with at least 1000 employees, as their recruiter base is suited to more experienced professionals at enterprise companies.


# The solution


<p align="center">
    <img width="300" src="https://github.com/HannahIgboke/Customer-Analytics-Preparing-Data-for-Modeling/blob/main/Files/Solution.jpeg" alt="The Solution">
</p>


Reduce the memory usage of this DataFrame by optimizing the data types used to store its columns.


For a step by step approach to this problem, check [here](https://github.com/HannahIgboke/Customer-Analytics-Preparing-Data-for-Modeling/blob/main/Files/Customer%20analytics.ipynb).
