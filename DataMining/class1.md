### Data mining
Data Mining is a technology that blends traditional data analysis methods with sophisticated(built for complex scenarios) algorithms for processinng large volumes of data.

Data Mining is the process of automatically discovering useful information in large repositories.

What is not Data Mining?
Any process which has the definitive outcome is not called data mining.

###Data Mining and Knowledge Discovery
Data mining is an integral part of knowledge discovery in database.
Input data --> Data Preprocessing --> Data mining --> Data post processing --> Information

Purpose of pre processing is to transform the raw input data into an appropriate format for subsequent analysis.
Steps involved in pre processing include fusing data from multiple sources, cleaning data to remove noise and duplicate observations and selecting features and records that are relavant to the data mining task at hand.

"Closing the loop" is the phrase often used to refer to the process integrating data mining results into decision support systems.
Sohisticated - atyadhunnika
Homogeneous - ekaroopada
Heteroheneous - Vaividhyamaya       
Hypothesis - a supposition or proposed explanation made on the basis of limited evidence as a starting point for further investigation.(Kalpane)
culminate - reach a climax or point of highest development.

## Data mining tasks
Predective tasks
```
Objective of this tasks is to predict the value of a particular attribute  based on the values of other attributes. The attribute to be predicted is known as the target or dependent variable while the attributes used for making the predections are known as the explanatory or dependent variable.
```
Descriptive tasks   
```
Here the objective is to derive the patterns (correlations, trends,clusters, trajectoriees and anamolies) that summarize the underlying relationship in data. Descriptive data mining tasks are often exploratory in nature and frequently require post processing techniques to validate and explain the results.
```
Four of the core Data mining tasks
```
1. Predective Modelling
2. Cluster analysis
3. Association analysis
4. Anomaly detection
```
Predective modelling
```
1. Classification -- Used for descrete(Individual) target variables
Ex: predecting whether an onlinee user will make a purchase or not at an online book store is classification task because thee target variable is binary valued
2. Regression -- Used for continuous target variable
Ex: Forecasting the futur price of a stock is a regression task because the price is a continous valued attribute. 
Ex:Predecting the type of a flower depending on the length and breadth of the petals
```
Associationn analysis
```
This is used to descover patterns that describe associated features in the data.
Ex: Market basket analysis
Using the checkout data collected at the POS in a grocery store we can we can apply Association analysis and find out the items which are bought together, this will enable the cross selling opportunnity. For instaqnce person who buys bread mostly will buy butter 
```

Cluster analysis
```
This method seeks to find groups of closely related observations so that observations that belonngs to the same cluster are more similar to each other than observations that belongs to other clusters.
Ex: Document clustering(News article) depending on the number of times words are repeated
```

Anamoly detection 
```
Anamoly detection is the task of identyfying observations whose characteristics are significantly different from the rest of the data. Such observations are known as anamolies or outliers.
A good anamoly detector should have a high deteection rate and a low false alarm rate.
Ex: Credit card fraud detection

```
 Exercises
 ```
1. Discusswhether or not eachof the following activities is a data mining task.
    (a) Dividing the customers of a company accordingto their gender.
        No
    (b) Dividing the customers of a company according to their profitability.
    Answer: No. This is an accounting calculation, followed by the application
        of a threshold. However, predicting the profitability of a new customer
        would be data mining.
    (c) Computing the total salesof a company. 
        No 
    (d) Sorting a student database based on student identification numbers. 
        No
    (e) Predicting the outcomes of tossing a (fair) pair of dice. No
    Answer: No. Since the die is fair, this is a probability calculation. If
        the die were not fair, and we needed to estimate the probabilities of each
        outcome from the data, then this is more like the problems considered by
        data mining. However, in this specific case, solutions to this problem were
        developed by mathematicians a long time ago, and thus, we wouldnOt ˜
        consider it to be data mining.
    (f) Predicting the future stock price of a company using historical records.
    Yes
    Answer: Yes. We would attempt to create a model that can predict the
        continuous value of the stock price. This is an example of the area of
        data mining known as predictive modelling. We could use regression for
        this modelling, although researchers in many fields have developed a wide
        variety of techniques for predicting time series.
    (g) Monitoring the heart rate of a patient for abnormalities.
        Yes
        Answer: Yes. We would build a model of the normal behavior of heart rate
            and raise an alarm when an unusual heart behavior occurred. This would
            involve the area of data mining known as anomaly detection. This could
            also be considered as a classification problem if we had examples of both
            normal and abnormal heart behavior.
    (h) Monitoring seismic waves for earthquake activities.
        Answer: Yes. In this case, we would build a model of different types of
            seismic wave behavior associated with earthquake activities and raise an
            alarm when one of these different types of seismic activity was observed.
            This is an example of the area of data mining known as classification.
    (i) Extracting the frequencies of a sound wave
        No, This is signal processing
```
