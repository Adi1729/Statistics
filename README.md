# Statistics
Contains questions on statistics required in machine learning based on as asked in interviews


## Variance
Variance gives us an idea about the distribution of data around the mean, and thus from this distribution, we can work out where we can expect an unknown data point. 

## Why variance is divided by (n-1)?
[Khan Academy - Variance](https://www.khanacademy.org/math/ap-statistics/summarizing-quantitative-data-ap/more-standard-deviation/v/another-simulation-giving-evidence-that-n-1-gives-us-an-unbiased-estimate-of-variance)

## Covariance and Corrlelation :

Covariance :\
Formaula = ![first equation](https://latex.codecogs.com/gif.latex?%5Cfrac%7B%5Csum%20%28X-%5Cbar%7BX%7D%29%28Y-%5Cbar%7BY%7D%29%7D%7BN%7D)

Assume X  = Height(cms) , Y = Weight(kgs) , Z = Age(Yrs)\

cov(X,Y) = 100 cms-Kgs\
cov(Y,Z) = 150 kgs-Yrs\
However, one can not compare two cavariance results as both has different units.\

Correlation:\
Formaula = ![second equation](https://latex.codecogs.com/gif.latex?%5Cfrac%7Bcov%28X%2CY%29%7D%7Bcov%28X%29cov%28Y%29%7D)                 -1<=cor<=1\
cor(X,Y) = 0.5\            
cor(X,Z) = 1\
Here, it can ne said X,Z covary much more than X,Z 


## F-tests 

Compares variance of two different population. 

<img src="https://github.com/Adi1729/Machine-Learning-Materials/blob/master/model_interpretation_ensemble.png" width = 80%,  height = 80%>

There are different types of t-tests for different purposes. Some of the more common types are outlined below.

   1. F-test for testing equality of variance is used to test the hypothesis of the equality of two population variances. The height example above requires the use of this test.
   
   2. F-test for testing equality of several means. The test for equality of several means is carried out by the technique called ANOVA.\
   For example, suppose that an experimenter wishes to test the efficacy of a drug at three levels: 100 mg, 250 mg and 500 mg. A test is conducted among fifteen human subjects taken at random, with five subjects being administered each level of the drug.\
To test if there are significant differences among the three levels of the drug in terms of efficacy, the ANOVA technique has to be applied. The test used for this purpose is the F-test.
   
   3. F-test for testing significance of regression is used to test the significance of the regression model. The appropriateness of the multiple regression model as a whole can be tested by this test. A significant F value indicates a linear relationship between Y and at least one of the Xs.





 



