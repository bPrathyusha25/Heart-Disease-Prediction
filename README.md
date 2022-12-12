# Heart-Disease-Prediction
Heart disease can be managed effectively with a combination of lifestyle changes, medicine and, in some cases, surgery. With the right treatment, the symptoms of heart disease can be reduced and the functioning of the heart improved. The predicted results can be used to prevent and thus reduce cost for surgical treatment and other expensive.


![image](https://user-images.githubusercontent.com/105341413/206938566-ac6d21a3-a7c3-46bb-a984-35f0bcffc530.png)


The overall objective of our work will be to predict accurately with few tests and attributes the presence of heart disease. Attributes considered form the primary basis for tests and give accurate results more or less. Many more input attributes can be taken but our goal is to predict with few attributes and faster efficiency the risk of having heart disease. Decisions are often made based on doctors’ intuition and experience rather than on the knowledge rich data hidden in the data set and databases.


# Data Understanding

We have used a variety of tools, including Numpy, Pandas, Matplotlib, and Seaborn, to import the data from the data collection. We read the dataset after loading the data. 

![image](https://user-images.githubusercontent.com/105341413/206939142-247f2dff-e1b6-4280-88c2-2f3524d2f3c4.png)


![image](https://user-images.githubusercontent.com/105341413/206939206-5508292c-6d5e-42a1-a61e-024df7133b0a.png)


#  Exploratory Data Analysis (EDA) and Data Preparation

The aim of EDA is to find underlying patterns within the data, detect outliers and test assumptions with the final aim of finding a model that fits the data well.

There are four main types of EDA:
•Univariate non-graphical: make observations of the population and understand sample distributions of a single variable. (e.g. the measure of spread, the measure of central tendency, outlier detection)
•Univariate graphical: graphical analysis on a single variable. (e.g. Histograms, Boxplots, Stem and leaf)
•Multivariate non-graphical: techniques which show the relationship between two or more variables. (e.g. covariance, correlations)
•Multivariate graphical: graphically show the relationship between two or more variables. (e.g. bar plots, scatterplots)



# Data Evaluation

We go through numerous stages during the evaluation process, including:
By performing multiple analyses on the raw csv file using different software programs and uploading the data to Jupiter notebook, we can anticipate the output value (class).
After modeling each method, we calculated the four models' accuracy ratings. Of the three models, Random Forest has the best accuracy rating (90.16%), followed by Logistic Regression (85.25%). Decision trees, with an accuracy rate of 81.97%, had the lowest accuracy rate.


![image](https://user-images.githubusercontent.com/105341413/206939097-51473001-a30a-4daa-a222-254bb8c26a03.png)
