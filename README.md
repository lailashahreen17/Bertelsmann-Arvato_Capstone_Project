# Bertelsmann-Arvato_Capstone_Project

## Project Motivation
This project applies Machine Learning algorithms to get information about potential customers out of demographic data. It is part of the Udacity Data Scientist Nanodegree and shows the main steps to solve the underlying business needs: data understanding, data preparation, modelling and evaluation. The data and outline of this project was provided by Arvato Financial Solutions, a Bertelsmann subsidiary. I had an opportunity to practice and showcase my unsupervised and supervised machine learning skills and complete the Udacity Data Science Nanodegree capstone project. While brushing off my skills, I also had learn to optimize my coding structures to minimize run time and save memory space.

The whole project was divided into four parts:

> In Part 0 the provided data is read in and all necessary Data Preparation steps are done.

> In Part 1 the demographic data of the company’s existing customers and the general population of Germany are compared with each other. Therefore unsupervised learning techniques are used to identify the parts of the population that best describe the core customer base of a mail-order company.

> In Part 2 another dataset with demographic information for targets of a marketing campaign of the company is provided. To predict which individuals are most likely to convert into becoming customers for the company supervised learning techniques are applied.

> In Part 3 the supervised learning model built in Part 2 is used to predict the response of a testing data set. This prediction is used to compete in a Kaggle competition. 

Finally the results were summarized in a Medium blog post found here: https://lailashahreen17.medium.com/how-to-acquire-new-customers-utilizing-machine-learning-9e59cb66c85f


## File Descriptions
README.md - This file describes the contents of this repo

.gitignore - The gitignore file

Arvato_capstone.ipynb - Jupyter Notebook file containing project code

DIAS Information Levels - Attributes 2017.xlsx and DIAS Attributes - Values 2017.xlsx - Excel files containing information on the features.

blog_images folder - folder containing images used in the Medium blog post

## Libraries Required
The code was written in python 3 and requires the following packages: 
1. numpy 
2. pandas 
3. matplotlib 
4. seaborn 
5. time 
6. sklearn collections


## Licenses and Acknowledgements
I am really grateful that the Udacity Data Scientist Nanodegree has provided necessary lessons and many useful resources to complete this project. Arvato provided the data which cannot be publicly shared.

## References
There were many googling and online support I have utilized to finish the project. Below are few references:

1. https://github.com/miriamwanjo/Arvato-Capstone-Project-/blob/master/Arvato%20Project%20Workbook%20(4).ipynb
2. https://github.com/ursulahneumann/Arvato_capstone/blob/master/Arvato_capstone.ipynb
3. https://stackoverflow.com/questions/34537048/how-to-count-nan-values-in-a-pandas-dataframe
4. https://www.kaggle.com/sid321axn/principal-component-analysis-pca
5. https://medium.com/@tobias.gorgs/how-to-use-machine-learning-for-customer-acquisition-bcd52f42042d
6. https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.GradientBoostingClassifier.html
7. https://stats.stackexchange.com/questions/77689/estimating-the-most-important-features-in-a-k-means-cluster-partition
8. https://stats.stackexchange.com/questions/69157/why-do-we-need-to-normalize-data-before-principal-component-analysis-pca/69159#69159
