## Machine-Learning-and-Statistics-Assessment-2021

Student : Michelle Moran
ID : G00387856
----------------------------------------------------------------------------------------------------------------------


##**Overview of Project**

The purpose of this assessment to demonstrate a learning of the module and to create sample work to show prospective employers. The overall assessment is split into 3 components: 

### **Part 1

 - GitHub Respository containing : 
     - README.md - details the respository  , why it exists , whats in it , and how to run the notebooks
     - requirements.txt- enabling any person to run my notebooks efficiently

### **Part 2
 - SciKit- Learn Jupyter Notebook - called scikit-learn.ipynb
     - clear and concise overview of scikit-learn python library
     - Demonstrations of 3 interesting scikit- learn algorithms
     - Plots and other visualisations of the above
     
### **Part3
 - Scipy Stats Jupyter Notebook - scipy-stats-ipynb:
     - Clear and concise overview of scipy- stats python library
     - An example hypothesis test using ANOVA 
         - Find a dataset to use ANOVA ensureing the assumptions underlying ANOVE are met 
         - Perform and display the results of ANOVA using scipy-stats
     - PLots and other visualisations of the above
--------------------------------------------------------------------------------------------------------------------------------------------------

###**Getting started**

Download and install Python and Anaconda, all files associated with this project are available at **git@github.com:g00387856/Machine-learning-and-Statistics.git**
-------------------------------------------------------------------------------------------------------------------------------------------------------

###**How to download the repository

Go to the URL for the repository at https://github.com/g00387856/Machine-learning-and-Statistics and click the green Code button. Follow instructions to clone to your local machine.

###**How to run the code

Python 3.8.8  was used to develop this project and is needed to run the code in the notebook. Python 3.8.8  can be downloaded from the official Python website at https://www.python.org/downloads/. It can also be downloaded using the Anaconda Python distribution at https://www.anaconda.com/distribution/.

The Jupyter Notebooks Scipy-Learn.ipynb and Scipy-Stats.ipynb can be viewed directly in this GitHub repository in a browser without Python 3 being installed. On occasion the Jupyter Notebook may not render correctly in which case the URL https://github.com/g00387856/Machine-learning-and-Statistics.git can be copied and pasted in to the Jupyter nbviewer at https://nbviewer.jupyter.org or by clicking this link. This will render a static version of the notebook in the browser. If the repository is downloaded it can be run locally by navigating to the folder and entering the command jupyter lab or jupyter notebook on the command line. This will open Jupyter in the browser. The Scipy-Learn.ipynb and Scipy-Stats.ipynb notebooks can be opened then within the Jupyter session. Once opened you can can select Restart and Run All from the Kernel menu.

-----------------------------------------------------------------------------------------------------------------------------------------------------

###**Packages used in this project**

The following packages were used to run statistical analysis and draw grpahs for this project.

Python https://www.python.org/downloads/
Anaconda https://www.anaconda.com/distribution/ - is the easiest way to perfrom Python data science machine learning on Linux, Windows and Mac OS.
iPython https://ipython.org/ - it an interactive command-line terminal for Python.
Numpy http://www.numpy.org/ - is the fundamental package for scientific computing within Python.
Jupyter Notebook https://jupyter.org/ - is an open-source web application that allows the creation and sharing of documents that contains live code, equations, visualisations and narriative text
import pandas as pd https://pandas.pydata.org/
import scipy.stats as stats https://docs.scipy.org/doc/scipy/reference/stats.html - module contains a large number of probability distributions as well as a growing library of statistical functions.
import matplotlib.pylab as plt https://matplotlib.org/ - is a comprehensive library for creating static, animated, and interactive visualisations in Python.
from sklearn.model_selection import ....https://scikit-learn.org/stable/ - is a simple and efficient tools for predictive data analysis.
Statsmodel https://www.statsmodels.org/stable/index.html - a Python module that provides classes and functions for the estimation of many different statistical models
Plotly https://plotly.com/python/getting-started/- an interactive, open-source plotting library that supports over 40 unique chart types covering a wide range of statistical, financial, geographic, scientific, and 3-dimensional use-cases

-------------------------------------------------------------------------------------------------------------------------------------------------------

### **PART 1 Contents of Github Repository**

1.README file
2.MLSProject.ipynb - Jupyter Notebook containing research, overview of data, models and references
3.Assessment.pdf - pdf document outlining the project 4 Powerproduction.csv - data used in analysis and running the models
4.Images - images used in the tasks
5.Requirements.txt

--------------------------------------------------------------
   

### **PART 2 - SciKit- Learn Jupyter

Contents :

 - Overview of the Scikit-Learn Python Library ##
 - Dataset : The World Happiness Report
 
#### Machine Learning SETUP:

    Step 1 :Importing Packages¶
    Step 2. Read in the Dataset¶
    Step 3 :PERFORMING EXPLORATORY ANALYSIS
    Step 3 :PERFORM DATA VISUALIZATION¶
    Step 4 :Data Preparation and preproccessing : For use in model 2 and 3 algorithms
    Step 5 :Scaling of the data : Standardization

#### 3 Examples of Model Algorithms : 
    1. SciKit-Learn Algorithm - K- Means Clustering¶
    NB: Data preparation and preproccessing was done separately for this model
    
    2.SciKit-Learn Algorithm - KNN
        -Plotting the Fit of Your Model¶
        - Tune and Optimize kNN in Python Using scikit-learn
        - Adding Weighted Average of Neighbors Based on Distance
        - Further Improving on kNN in scikit-learn With Bagging
        
    3.SciKit-Learn Algorithm - Linear Regression
        -Import the packages and classes you need.
        -Provide data to work with and eventually do appropriate transformations.
        - Create a regression model and fit it with existing data.
        - Check the results of model fitting to know whether the model is satisfactory.
        - Apply the model for predictions.
        
        
 ------------------------------------------------------------------------------------------------------------------------------       

### **PART 3  - Scipy Stats Jupyter Notebook

#### Contents :

 - Overview of the scipy.stats Python library ##
 - Chose a Dataset : The Diet Dataset 
 - Complete a hypothesis test using ANOVA on chosen dataset
     -  ,Ensuring the assumptions underlying ANOVA are met
     -   Perform and display the results of your ANOVA using scipy.stats.
 
####  Task outline:

 1.An overview of the Scipy-Stats Python library
 2.Overview of a one-way ANOVA
 3.Analysis of diets dataset. Download the dataset
 4.Import the diet data set with the function read.csv()
 5.Define a new column weight loss = the difference between the initial and final weights
 6.Display weight loss per diet type (column diet.type) by means of a boxplot.
 7.Perform a one-way ANOVA, respectively by means of the scipy-stats package in python- determine the null hypothesis
 8.Display and analyze the results: perform a post hoc test
 9.Present conclusions

#### One -way ANOVA  Null Hypothesis Question : 

Are the weight loss means for each of the diet type the same ? 
Is the weight loss the same for females and males  ? 

#### Assumptions examined : 
1. Determining the dependent variable -continous - Weight loss
2. Determining the independent variable - Categorical - Diet type /Gender
3. Independence of observations
4. Outliers - Boxplot
5. Normality - shapiro-wilks test
6. Homogenity of Variances - Levene test

#### One-Way Anova : 

Question : Is there weight loss observed with these 3 diets ? 

Hypothesis : Are the weight loss means the same for each of the diets  ?

Completed on the general population data and on gender 

Concluded that that the null hypothesis can be rejected for the female population data  as the differences between the male wasnt significant

#### Post hoc on the female data - Null Hypothesis Question : 

Question asked :Which diet is the better for weight loss in females ? 

Hypothesis : Is the weight loss the same foe each of the diets completed by females ?

Test used was the TUKEY HSD test. 



.

