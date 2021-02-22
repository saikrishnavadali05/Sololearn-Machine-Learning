
### Machine Learning Sololearn Notes

* Source : [Sololearn](https://www.sololearn.com/learning/1094)

## The Basics

# Welcome to Machine Learning

Machine Learning is a way of taking data and turning it into insights.
We use computer power to analyze examples from the past to build a model that can predict the result for new examples.

- Machine learning models every day : 
   * Netflix recommendations 
   * Amazon Pricing System 
   * credit card company calls based on suspicious activity (anamolous behaviour prediction models)

- Machine Learning can be used to :
   * create a chatbot
   * detect spam 
   * image recognition.

- Approach : 
   * Python (Programming Language)
   * Pandas (library) for reading data and data manipulation
   * Numpy (library) is used for computations of numerical data
   * Matplotlib (library) is used for graphing data
   * scikit-learn (library) is used for machine learning models
   * Basic Statistics

- Types : 
   * Supervised 
   * Unsupervised Learning. 
   
   1. **Supervised learning** is when we have a known target based on past data (for example, predicting what price a house will sell for) 
      * classification 
      * regression problems
   
   2. **Unsupervised learning** is when there isn't a known past answer (for example, determining the topics discussed in restaurant reviews).

- **Regression** is predicting a numerical value (for example, predicting what price a house will sell for) 
- **Classification** is predicting what class something belongs to (for example, predicting if a borrower will default on their loan).

- **Classification problems** are the problems where we’re predicting which class something belongs to.
   * Examples will include:
      * Predicting who would survive the Titanic crash
      * Determining a handwritten digit from an image
      * Using biopsy data to classify if a lump is cancerous

   * Techniques to tackle these classification problems: 
      * Logistic Regression
      * Decision Trees
      * Random Forests
      * Neural Networks

 *Sololearn course will focus on supervised learning and classification.*

 ## Statistics Review

 - Averages
   * The mean is the most commonly known average.
   * The median is the value in the middle. 

   ( If there is an even number of datapoints, to find the median (or 50th percentile), you take the mean of the two values in the middle.)

*In statistics, both the mean and the median are called averages. The layman’s average is the mean.*

- Percentiles

   * The median can also be thought of as the 50th percentile. 
   * The 25th percentile is the value that’s one quarter of the way through the data. This is the value where 25% of the data is less than it (and 75% of the data is greater than it).
   * Similarly, the 75th percentile is three quarters of the way through the data. 

If we look at these ages:
15, 16, 18, 19, 22, 24, 29, 30, 34 

   * 25th percentile is 18 (the 3rd datapoint).
   * 75th percentile is 29 (the 7th datapoint).                          
   * The full range of our data is between 15 and 34. 
   * The 25th and 75th percentiles tell us that half our data is between 18 and 29. 

The percentiles helps us gain understanding of how the data is distributed (or Data Distribution).

- Standard Deviation & Variance

   * Deeper understanding of the distribution of our data with the standard deviation and variance. 
   * The standard deviation and variance are measures of how dispersed or spread out the data is.

- Steps for calculating Standard Deviation and Variance:

   1. We measure how far each datapoint is from the mean.

      ```15, 16, 18, 19, 22, 24, 29, 30, 34```
      
      Recall that the mean is 23.

   2. Let's calculate how far each value is from the mean. 
   
      ```15 is 8 away from the mean (since 23-15=8).```
         Here's a list of all these distances:
         8, 7, 5, 4, 1, 1, 6, 7, 11

   3. We square these values and add them together. Divide this value by the total number of values and that gives us the variance.
         362 / 9 = 40.22 

   4. To get the standard deviation, we just take the square root of this number and get: 6.34